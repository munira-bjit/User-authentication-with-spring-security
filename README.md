# Spring Security Project with User Authentication Registration and Login

This project is a Spring Boot application that serves as a project for implementing security features using Spring Security, 
JWT (JSON Web Tokens) for authentication and various other Spring technologies. It provides a set of RESTful endpoints for 
user registration, authentication, role-based authorization and some sample endpoints for demonstration purposes.

## Project Details

- **Language**: Java
- **Framework**: Spring Boot
- **Security**: Spring Security
- **Authentication**: JWT (JSON Web Tokens)
- **Database**: MySQL
- **Authorization Roles**: "user" and "admin"

## Endpoints

- `/users/registration`: Endpoint for user registration.
- `/signin`: Endpoint for user authentication.
- `/users/hello`: A sample endpoint accessible to all authenticated users.
- `/users/hello2`: Another sample endpoint accessible to all authenticated users.
- `/users/**`: Additional user and admin-specific endpoints, protected by role-based authorization.

  
## Custom Authentication Filter

The project includes a custom authentication filter that handles user authentication and issues JWT tokens upon successful authentication.

## Exception Handling

Exception handling is implemented to provide meaningful error responses in JSON format for various scenarios including unsuccessful authentication.
