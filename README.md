# EcommerceServiceDiscovery

EcommerceServiceDiscovery is a Spring Boot application that serves as a service discovery server using Netflix Eureka. It is designed to register and manage microservices in an e-commerce ecosystem.

## Features

- **Eureka Server**: Acts as a service registry for microservices.
- **Spring Boot**: Built with Spring Boot for rapid development and deployment.
- **Maven**: Dependency management and build automation.
- **DevTools**: Provides hot-reloading for development.

## Requirements

- **Java 23** 
- **Maven**

## Getting Started

### Clone the Repository

```bash
git clone https://github.com/rajvicky16/EcommerceServiceDiscovery.git
cd EcommerceServiceDiscovery
```

 ### Build the Project
 Run the following command to build the project:
 ```bash
 mvn clean install
 ```

### Configuration
- `server.port:` The port on which the application runs.
- `eureka.client.registerWithEureka:` Disables self-registration.
- `eureka.client.fetchRegistry:` Disables fetching the registry.
  
### Run the Application
You can use the following command to start the application:
 ```bash
 mvn spring-boot:run
 ```
