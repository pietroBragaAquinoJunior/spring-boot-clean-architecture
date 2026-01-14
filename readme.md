# Spring Boot Clean Architecture API

REST API built with Spring Boot, following **Clean Architecture (Ports and Adapters)** principles, with strong focus on maintainability, testability and performance.

---

## 🧱 Architecture
- Clean Architecture (Ports and Adapters / Hexagonal)
- Business rules isolated from frameworks and infrastructure
- Clear separation between domain, application and adapters

---

## ⚙️ Tech Stack
- Java
- Spring Boot
- JPA (Hibernate)
- Flyway
- MapStruct
- Spring Validation
- JUnit & Mockito

---

## 🚀 Key Highlights
- Clean Architecture implementation
- Solution for **N+1 query problem** using optimized JPQL and `JOIN FETCH`
- Global exception handling with `@RestControllerAdvice`
- Database versioning with Flyway
- Unit and integration tests

---

## ▶️ Running locally
```bash
git clone https://github.com/pietroBragaAquinoJunior/spring-boot-clean-architecture
cd spring-boot-clean-architecture
./mvnw spring-boot:run
