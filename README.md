# Member Management Application

## APIs

- GET /api/v1/members/{id}
- PUT /api/v1/members/{id}
- DELETE /api/v1/members/{id}
- GET /api/v1/members
- POST /api/v1/members
- POST /api/v1/auth/login

## Features
- CRUD operations for Member Management APIs
- JWT-based authentication and role-based authorization
- In-memory caching to improve response performance
- Comprehensive Unit testing with Mockito and JaCoCo coverage reporting
- Integration testing using Testcontainers
- Centralized exception handling with global exception handler
- Logging with unique request traceID for debugging

## Technologies used
- Java 17
- Spring Boot 3.5.6
- PostgreSQL 17.6
- Flyway (Database migration)
- JWT (JSON Web Tokens)
- Docker + Testcontainers (Integration testing)
- JUnit 5 & Mockito (Unit testing)
- JaCoCo

## Tools used
- Lombok
- JaCoCo
- AssertJ
- JUnit 5 / Spring Boot Test / Spring Security Test
- Postman
- IntelliJ IDEA

## Build Tools / Plugins
- Gradle
- Spring Boot Gradle Plugin 3.5.6
- Spring Dependency Management Plugin 1.1.7
- Java Plugin
- JaCoCo Plugin 0.8.12

## Screenshots:-


### Code coverage report
[CodeCoverage](docs/images/CodeCoverageReport.png)


### Build Successful Screenshot
[Running](docs/images/BuildSuccessful.png)


### Application running screenshot
[Running](docs/images/AppRunning.png)
