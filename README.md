<h1 align="center">🏋️‍♂️ Intelligent Fitness Microservices Backend System 🧠</h1>

<p align="center">
  <img src="https://img.shields.io/badge/Spring_Boot-green?style=flat-square&logo=springboot" />
  <img src="https://img.shields.io/badge/MongoDB-NoSQL-green?style=flat-square&logo=mongodb" />
  <img src="https://img.shields.io/badge/PostgreSQL-Relational-blue?style=flat-square&logo=postgresql" />
  <img src="https://img.shields.io/badge/RabbitMQ-Message_Queue-orange?style=flat-square&logo=rabbitmq" />
  <img src="https://img.shields.io/badge/Keycloak-SSO-orange?style=flat-square&logo=keycloak" />
  <img src="https://img.shields.io/badge/WebFlux-Reactive-blue?style=flat-square&logo=spring" />
</p>

<p align="center"><strong>Modular, AI-powered backend system for personalized fitness recommendations</strong></p>

<hr/>

## 🚀 Overview

The **Intelligent Fitness Microservices Backend System** is a scalable and secure backend for fitness applications that:
- Leverages AI for personalized workout and diet recommendations
- Follows a microservices architecture with service discovery and gateway routing
- Implements reactive programming with Spring WebFlux
- Uses Keycloak for secure authentication and authorization

  ## 🔧 Technologies Used

| Tech Stack    | Description                                   |
|---------------|-----------------------------------------------|
| **Spring Boot** | Core framework for microservices            |
| **Spring Cloud** | Service Discovery (Eureka), Config Server   |
| **Spring WebFlux** | Reactive programming for non-blocking I/O |
| **PostgreSQL** | Relational database for user & activity data  |
| **MongoDB** | NoSQL database for unstructured AI data          |
| **RabbitMQ** | Asynchronous communication between services     |
| **Keycloak** | Authentication & Role-Based Access Control      |
| **Gemini AI** | Custom recommendation engine                   |

---

## 📦 Microservices

| Service         | Description |
|-----------------|-------------|
| `user-service`  | Manages user profiles, preferences, and roles |
| `activity-service` | Tracks workouts, calories, and progress |
| `ai-service`    | Processes and returns AI-based suggestions |
| `config-server` | Centralized configuration for all services |
| `eureka`        | Service registry/discovery                  |
| `gateway`       | Unified entry-point with routing & security |
