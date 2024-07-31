# Vacation Booking Application

## Overview

The Vacation Booking Application is a Spring Framework-based project designed to modernize the backend of a travel agency's vacation booking system. This project involves developing a Java backend integrated with an existing MySQL database and an Angular front-end. It showcases skills in developing object-oriented applications, integrating them with relational databases, and implementing design patterns using the Spring Framework.

## Project Description

This application was developed as part of a software development course to create a minimally viable product (MVP) for migrating a legacy backend to the modern Spring framework. The project includes various functionalities such as managing vacation packages, handling customer data, and processing bookings.

### Key Features

1. **Spring Framework Backend**:
   - Developed using Spring Boot with dependencies such as Spring Data JPA, Rest Repositories, MySQL Driver, and Lombok.

2. **Entity Management**:
   - Includes entity classes and enums designed to match the provided UML diagram.

3. **Data Access Objects (DAO)**:
   - Repository interfaces extend JpaRepository and include cross-origin support.

4. **Service Layer**:
   - Contains services for handling business logic, including a checkout service for processing customer orders.

5. **Validation**:
   - Implements validation to enforce input requirements needed by the Angular front-end.

6. **REST Controllers**:
   - Includes REST controllers for handling HTTP requests and managing vacation packages and customer orders.

7. **Sample Data**:
   - Programmatically adds five sample customers to the application to facilitate testing.

### Technologies Used

- **Spring Framework**: For building the Java backend.
- **Spring Data JPA**: For interacting with the relational database.
- **MySQL**: As the database to store vacation booking data.
- **Angular**: For the front-end interface.
- **JUnit**: For unit testing the application.
- **Lombok**: To reduce boilerplate code in Java.

### How to Run the Application

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/mmoffett02/Vacation-Booking-Application.git
   cd Vacation-Booking-Application
