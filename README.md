# Banking Portal API

A backend banking platform focused on secure authentication and financial operations.

FinEdge is a personal backend engineering project built to explore secure API development, authentication, database design, and scalable Spring Boot architecture. Instead of being a simple CRUD application, the goal is to evolve it into a production-style banking backend.

---

## Why I Built This

Most beginner banking projects stop at CRUD operations.

FinEdge is being developed as a long-term project to practice real backend engineering concepts such as authentication, authorization, transaction management, and clean architecture.

---

## Current Features

- Secure user registration
- JWT-based authentication
- Password encryption using BCrypt
- MySQL persistence with JPA
- Layered architecture
- Request validation

---

## Tech Stack

- Java 17
- Spring Boot
- Spring Security
- Spring Data JPA
- MySQL
- Maven
- JWT (JJWT)
- Lombok

---

## Project Structure

```text
controller/
service/
repository/
entity/
dto/
config/
security/
exception/
```

---

## Development Roadmap

### Authentication
- [x] User Registration
- [x] User Login
- [x] JWT Generation

### Banking
- [ ] Account Creation
- [ ] Deposit
- [ ] Withdrawal
- [ ] Fund Transfer
- [ ] Transaction History

### Security
- [ ] JWT Request Filter
- [ ] Role-Based Authorization
- [ ] Refresh Tokens

### Developer Experience
- [ ] Swagger Documentation
- [ ] Docker
- [ ] Unit Tests
- [ ] CI/CD

---

## Running Locally

```bash
git clone https://github.com/virag185/FinEdgeAPI.git
```

Create a MySQL database named:

```sql
CREATE DATABASE finedge_db;
```

Configure your local database credentials inside:

```text
application.properties
```

Run:

```bash
./mvnw spring-boot:run
```

---

## Status

FinEdge is under active development. New banking features and security improvements are added incrementally.

---

## Author

Virag Khade

Backend Development • Java • Spring Boot