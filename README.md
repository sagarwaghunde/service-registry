# Service Registry using Spring Cloud Netflix Eureka

This repository contains a sample application demonstrating how to implement a Service Registry using Spring Cloud Netflix Eureka.

## Applications

- [Eureka Server](./eureka-server): Eureka Server application responsible for service registration and discovery.
- [Eureka Client (Service Provider)](./eureka-client): Eureka Client application that registers itself with the Eureka Server.

## Used in Projects

This Service Registry example is utilized in the following projects:

- [API Gateway](https://github.com/sagarwaghunde/api-gateway)
- [Department Microservice](https://github.com/sagarwaghunde/springboot-microservice-department)
- [Employee Microservice](https://github.com/sagarwaghunde/springboot-microservice-employee)

## Prerequisites

- Java 8 or higher
- Maven
- Spring Boot

## Getting Started
1. Clone this repository to your local machine:

   ```bash
   git clone https://github.com/sagarwaghunde/service-registry.git

2. Navigate to the project directory:
   ```bash
   cd service-registry
3. Build the project using Maven:
   ```bash
   mvn clean install
4. Run the Eureka Server application:
   ```bash
   mvn spring-boot:run
5. Open your browser and navigate to the Eureka Server dashboard:
   ```bash
   http://localhost:8761/
