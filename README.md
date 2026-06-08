# Student Record Management API

A RESTful API built with Java Spring Boot and MySQL.

## Tech Stack
- Java 17
- Spring Boot 3.5.14
- Spring Data JPA
- MySQL
- Maven

## Endpoints
| Method | Endpoint | Description |
|--------|----------|-------------|
| GET | /students | Get all students |
| GET | /students/{id} | Get student by ID |
| POST | /students | Add new student |
| PUT | /students/{id} | Update student |
| DELETE | /students/{id} | Delete student |

## Setup
1. Create MySQL database: `CREATE DATABASE studentdb;`
2. Update `application.properties` with your MySQL credentials
3. Run with `mvn spring-boot:run`
