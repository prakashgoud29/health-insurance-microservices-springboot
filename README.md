# health-insurance-microservices-springboot
#Project
# Health Insurance Microservices Platform

A cloud-native microservices-based health insurance system built using Java, Spring Boot, Docker, Kubernetes, and CI/CD pipelines.

## Architecture
- Microservices: Auth, Customer, Policy, Claims, Payment
- API Gateway
- Service Registry (Eureka)
- Centralized Config Server

## Tech Stack
- Java 17, Spring Boot 3
- Docker, Kubernetes (EKS/AKS)
- GitHub Actions, Jenkins
- Prometheus, Grafana, ELK
- JWT Authentication

## Features
- Secure user authentication
- Policy management
- Claims processing workflow
- Premium payment simulation
- Observability & monitoring
- CI/CD automated deployments

## How to Run
```bash
docker-compose up -d
