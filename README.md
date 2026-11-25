
<h1 align="center">Nitish Pala</h1>

<h3 align="center">
Java Backend Developer | Software Engineer
</h3>

<p align="center">
  Java • Spring Boot • REST APIs • Kafka • Redis • SQL
</p>

<p align="center">
  Hyderabad, India | Ex-D. E. Shaw | Ex-Amazon Intern
  <br/>
  <b>Open to Work | Immediate Joiner</b>
</p>

<p align="center">
  <a href="https://linkedin.com/in/nitishpala">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/>
  </a>
  <a href="https://leetcode.com/u/pala139/">
    <img src="https://img.shields.io/badge/LeetCode-FFA116?style=for-the-badge&logo=leetcode&logoColor=black" alt="LeetCode"/>
  </a>
  <a href="mailto:nitishpala.dev@gmail.com">
    <img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/>
  </a>
  <a href="https://codeforces.com/profile/nitish1391016">
    <img src="https://img.shields.io/badge/Codeforces-445FE2?style=for-the-badge&logo=codeforces&logoColor=white" alt="Codeforces"/>
  </a>
</p>

---

## About Me

Backend-focused software engineering professional with nearly
**3 years of professional experience at D. E. Shaw India**
and previous internship experience at **Amazon**.

Experienced in REST API development, service integration,
financial data processing, CI/CD, production troubleshooting,
and application reliability.

My primary technical focus is **Java backend development**,
with an interest in building secure, scalable, reliable,
and maintainable software systems.

- **Backend:** Java, Spring Boot, REST APIs, Hibernate
- **Data & Messaging:** SQL, MySQL, PostgreSQL, Kafka, Redis
- **Engineering:** Concurrency, Transactions, System Design, CI/CD
- **Problem Solving:** 527 LeetCode problems | Rating 1661
- **Availability:** Immediate Joiner

Currently seeking **Java Backend Developer, Software Engineer,
and SDE1 opportunities**.

---

## Technical Skills

### Languages

![Java](https://img.shields.io/badge/Java_17-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=mysql&logoColor=white)

### Backend Development

![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![Spring Security](https://img.shields.io/badge/Spring_Security-6DB33F?style=flat-square&logo=springsecurity&logoColor=white)
![Hibernate](https://img.shields.io/badge/Hibernate-59666C?style=flat-square&logo=hibernate&logoColor=white)
![REST APIs](https://img.shields.io/badge/REST_APIs-005571?style=flat-square)
![JWT](https://img.shields.io/badge/JWT-000000?style=flat-square&logo=jsonwebtokens&logoColor=white)

### Databases, Caching & Messaging

![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![Kafka](https://img.shields.io/badge/Apache_Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white)

### DevOps & Development Tools

![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Maven](https://img.shields.io/badge/Maven-C71A36?style=flat-square&logo=apachemaven&logoColor=white)
![Flyway](https://img.shields.io/badge/Flyway-CC0200?style=flat-square&logo=flyway&logoColor=white)
![Swagger](https://img.shields.io/badge/Swagger-85EA2D?style=flat-square&logo=swagger&logoColor=black)

### Testing

![JUnit](https://img.shields.io/badge/JUnit_5-25A162?style=flat-square&logo=junit5&logoColor=white)
![Mockito](https://img.shields.io/badge/Mockito-78A641?style=flat-square)
![Testcontainers](https://img.shields.io/badge/Testcontainers-2496ED?style=flat-square)

### Core Engineering Concepts

- Object-Oriented Programming and SOLID Principles
- Design Patterns and Low-Level Design
- Data Structures and Algorithms
- Multithreading and Concurrency
- Database Transactions and ACID Properties
- Database Indexing and Query Optimization
- Caching and Idempotency
- Event-Driven Architecture Fundamentals

---

## Featured Project

### E-Commerce Order & Inventory Management System

[![Source Code](https://img.shields.io/badge/Source_Code-GitHub-181717?style=for-the-badge&logo=github)](https://github.com/pala139/ECOMMERCE)
[![Live API](https://img.shields.io/badge/Live_API-Swagger-85EA2D?style=for-the-badge&logo=swagger&logoColor=black)](https://ecommerce-backend-qbyh.onrender.com/swagger-ui/index.html)

A production-oriented Java Spring Boot backend demonstrating
secure API development, transaction management, concurrency
control, caching, and automated testing.

**Technology Stack**

Java 17, Spring Boot 3.5.8, Spring Security,
Spring Data JPA, Hibernate, MySQL, Redis, Docker,
Flyway, GitHub Actions, JUnit 5, Testcontainers

### Key Engineering Features

| Feature | Implementation |
|---|---|
| API Architecture | Controller, Service, Repository, DTO layers |
| Authentication | JWT and BCrypt password hashing |
| Authorization | Role-based access control and resource ownership |
| Inventory Consistency | Pessimistic database locking |
| Transaction Management | Transactional checkout and order processing |
| Duplicate Prevention | Idempotency keys |
| Performance | Redis cache-aside, indexing, pagination |
| Database Migrations | Flyway |
| Testing | JUnit 5, Mockito, Testcontainers |
| CI/CD | GitHub Actions |
| Deployment | Docker, Render, TiDB Cloud |
| Documentation | Swagger / OpenAPI |
| Monitoring | Spring Boot Actuator |

### Architecture

```mermaid
flowchart TD
    A[API Client] --> B[REST Controllers]
    B --> C[Spring Security / JWT]
    C --> D[Service Layer]
    D --> E[Repository Layer]
    D --> F[(Redis Cache)]
    E --> G[(MySQL / TiDB)]
```

### Project Metrics

| Metric | Result |
|---|---:|
| Throughput without Redis | 1,155 req/s |
| Throughput with Redis | 1,348 req/s |
| Throughput Improvement | 16.7% |
| Passing Automated Tests | 23 |
| HTTP Errors During Benchmark | 0 |

> Performance results are from a controlled k6 benchmark,
> not live production traffic.

The application is deployed on Render's free tier.
The initial request may take longer after inactivity.

---

## Professional Experience

### D. E. Shaw India Private Limited

**Member Technical (AQAE) | September 2023 – September 2026**

- Developed REST APIs supporting investment reporting workflows
  within an application processing **1M+ daily API requests**.
- Worked with Java, Apache Kafka, SQL, and enterprise
  application workflows.
- Engineered reusable financial document processing and
  reconciliation frameworks, saving **36+ hours per month**.
- Implemented CI/CD pipelines across six internal services,
  reducing manual deployment effort by **2 hours per day**.
- Contributed to service migrations, production troubleshooting,
  root cause analysis, and application reliability.
- Improved unit test coverage from **43% to 83%**.

### Amazon

**Intern | Software Development | January 2023 – June 2023**

- Developed automated data processing and reporting workflows using AWS QuickSight and SQL.
- Designed data extraction, transformation, and integration workflows.
- Reduced manual operational effort by **8+ hours per month** through automation.
- Improved reporting accuracy and operational efficiency using AWS cloud services.

---

## Competitive Programming

| Achievement | Statistics |
|---|---:|
| LeetCode Problems Solved | 527 |
| Problems Solved in Java | 523 |
| Contest Rating | 1661 |
| Global Contest Percentile | Top 17.54% |
| Contests Participated | 84 |
| Easy Problems | 281 |
| Medium Problems | 217 |
| Hard Problems | 29 |

[LeetCode Profile](https://leetcode.com/u/pala139/) |
[Codeforces Profile](https://codeforces.com/profile/nitish1391016) |
[CodeChef Profile](https://www.codechef.com/users/nitish_pala)

---

## Current Focus

- Java and Spring Boot internals
- Distributed systems fundamentals
- Event-driven architecture with Apache Kafka
- Database performance and concurrency
- Low-Level Design and System Design
- Advanced data structures and algorithms

---

## Education

**B.Tech – Computer Science and Engineering**

Malla Reddy Engineering College, Hyderabad

2019 – 2023 | CGPA: 7.76/10

---

## Connect With Me

- **LinkedIn:** https://linkedin.com/in/nitishpala
- **Email:** nitishpala.dev@gmail.com
- **LeetCode:** https://leetcode.com/u/pala139/
- **Live Backend:** https://ecommerce-backend-qbyh.onrender.com/swagger-ui/index.html

<p align="center">
  Open to Java Backend Developer and Software Engineering opportunities.
</p>
