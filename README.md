# Distributed-flight-booking-system


## Basic Features:
- Authentication and authorization:
  1. User login, registration
  2. Authentication and authorization based on OAuth 2.0 
     
- Flight management:
  1. Creation, deletion, modification and query (CRUD) of flight information
  2. Flight query interface (supports conditional query, date filtering, departure and destination matching)
     
- Booking management:
  1. Air ticket booking: create booking order, payment status update.
  2. Asynchronous notification: after successful booking, asynchronous processing is triggered through the message queue (inventory deduction, SMS notification)
     
## Technology Stack: 
- Spring Boot, Spring Cloud, Spring Data JPA & MySQL, Spring Security + OAuth2, Spring Boot AMQP & RabbitMQ
- Eureka/Consul, RabbitMQ, RESTful API
- Docker, Kubernetes
