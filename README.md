# Demo App

A simple Spring Boot demo application built with Java 17 and Gradle.

## Features

- REST API with status endpoint
- Containerized with Docker
- Built with Spring Boot 3.2.0

## Getting Started

### Prerequisites

- Java 17
- Gradle (or use the included wrapper)

### Running the Application

1. **Using Gradle wrapper:**
   ```bash
   gradle bootRun
   ```

2. **Using Docker:**
   ```bash
   # Build the application
   gradle build
   
   # Build Docker image
   docker build -t demo-app .
   
   # Run the container
   docker run -p 8080:8080 demo-app
   ```

### API Endpoints

- `GET /api/status` - Returns application status

### Development

- **Build:** `gradle build`
- **Test:** `gradle test`
- **Clean build:** `gradle clean build`

The application runs on port 8080 by default.