🏨 BookMyStay – Resort Booking System

BookMyStay is a **Spring Boot REST API application** for managing resort bookings, users, resorts, and reviews. The project is built using **Java, Spring Boot, MySQL, Spring Data JPA, Spring Security, and JWT**.

🚀 Features

* User registration and login
* JWT-based authentication
* BCrypt password encryption
* Resort management and CRUD operations
* Resort booking and cancellation
* Booking status management
* Resort reviews and ratings
* User profile management
* Cloudinary image upload
* Email notifications using Gmail SMTP
* Global exception handling
* Swagger/OpenAPI API documentation

 🛠️ Technologies Used

* **Java 17**
* **Spring Boot 3.5.6**
* **Spring Web / REST APIs**
* **Spring Data JPA & Hibernate**
* **Spring Security & JWT**
* **MySQL**
* **Cloudinary**
* **Spring Mail**
* **Maven**
* **Swagger/OpenAPI**
* **Postman**
 🏗️ Architecture

The application follows a layered architecture:


Controller
    ↓
Service
    ↓
Repository
    ↓
MySQL Database


DTOs, request/response classes, exception handling, security configuration, and utility components are used to keep the application structured and maintainable.

 📁 Project Structure

src/main/java/
├── controller/
├── service/
├── repo/
├── entity/
├── dto/
├── request/
├── response/
├── exception/
├── config/
└── utills/


⚙️ Database Configuration

The application uses MySQL with JPA/Hibernate.

Prerequisites

* Java 17
* Maven
* MySQL
* STS/Eclipse or IntelliJ IDEA


The application runs on:


APIs can be tested using **Postman** or **Swagger/OpenAPI**.

> **Security:** Do not commit database passwords, Gmail credentials, Cloudinary secrets, or other sensitive configuration to GitHub.

🎯 Learning Outcomes

This project provided practical experience in **Spring Boot REST API development, JWT authentication, JPA/Hibernate, MySQL integration, layered architecture, exception handling, cloud image storage, and email integration**.

👩‍💻 Author

Nikhitha A.
