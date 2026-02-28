Overview

This project is a production-style microservices application built using Spring Boot and Spring Cloud. It demonstrates secure authentication, service discovery, API gateway routing, asynchronous messaging, and AI integration within a distributed architecture.

The application follows a distributed microservices architecture consisting of:

API Gateway for centralized routing

Eureka Server for service discovery

Config Server for centralized configuration

Independent domain-based microservices

Keycloak for OAuth2 authentication and JWT validation

Apache Kafka for asynchronous event-driven communication

Separate database per service approach

Each service is independently deployable and loosely coupled.

Key Features

OAuth2 authentication using Keycloak

JWT-based stateless security

Service registration and discovery via Eureka

Centralized configuration management

Synchronous REST communication

Asynchronous messaging using Kafka

AI-powered service integration

Security

Authentication and authorization are implemented using OAuth2 and JWT tokens.
Each microservice validates tokens independently, ensuring secure inter-service communication without session dependency.

Technology Stack

Java

Spring Boot

Spring Security

Keycloak

Apache Kafka

REST APIs

Docker

AWS-ready deployment structure

What This Project Demonstrates

Real-world microservices architecture design

Secure distributed systems implementation

Event-driven communication patterns

Identity and access management

Scalable backend system development

AI integration within a microservices ecosystem

Purpose

This project was built to gain hands-on experience in designing and implementing secure and scalable application using modern Java technologies.
