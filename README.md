# Spring Boot User Authentication App

This project is a simple Spring Boot application with user authentication, including login and registration.

## Features
- User registration with encrypted passwords
- User login
- Role-based access control (default: `ROLE_USER`)

## Requirements
- Java 17 or higher
- Maven

## Run the Application
1. Clone the repository.
2. Run `mvn spring-boot:run` in the terminal.
3. Access the app at `http://localhost:8080`.

## Routes
- `/register`: Register a new user.
- `/login`: Login with existing credentials.
- `/`: Home page (authenticated users only).

## Database
Uses an in-memory H2 database (accessible at `/h2-console`).
