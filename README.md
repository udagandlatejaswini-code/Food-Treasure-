# Food Treasure – Online Food Ordering Web Application

## Project Description

Food Treasure is a full-stack online food ordering web application developed using Java technologies.  
The application allows customers to browse restaurants, add food items to cart, place orders, and track deliveries in real time.

The system also provides dedicated dashboards for restaurant administrators and delivery personnel.

---

## Purpose of the Project

The purpose of this project is to simplify online food ordering and restaurant management through an automated web-based platform.

It helps:
- Customers order food easily
- Restaurants manage orders efficiently
- Delivery personnel track deliveries
- Administrators maintain system operations

---

## Technologies Used

- Java
- Servlets
- JSP
- JDBC
- MySQL
- HTML
- CSS
- JavaScript
- MVC Architecture
- Apache Tomcat

---

## Features

### Customer Module
- User Registration & Login
- Browse Restaurants
- Add to Cart
- Place Orders
- Online Payment
- Order Tracking

### Restaurant Admin Module
- Add Food Items
- Update Menu
- Manage Orders
- View Customer Requests

### Delivery Module
- View Assigned Orders
- Update Delivery Status
- Track Deliveries

### Security Features
- Authentication & Authorization
- Session Management
- Role-Based Access Control

---

## Project Structure

```text
FoodTreasure/
│
├── src/
│   ├── controller/
│   ├── model/
│   ├── dao/
│   └── util/
│
├── WebContent/
│   ├── css/
│   ├── js/
│   ├── images/
│   ├── jsp/
│   └── WEB-INF/
│
├── database/
│   └── foodtreasure.sql
│
├── README.md
└── pom.xml
```

---

## System Architecture

The Food Treasure application follows MVC Architecture.

### 1. Client Layer
- Browser interface for users
- Sends HTTP requests to server

### 2. Application Layer
- Servlets handle requests
- JSP manages UI
- Business logic implementation

### 3. Database Layer
- MySQL database stores data
- JDBC used for database connectivity

---

## Database Design

The database includes tables such as:
- Users
- Restaurants
- Food_Items
- Orders
- Order_Details
- Payments
- Delivery_Status

Foreign key constraints are used to maintain data consistency.

---

## Installation Steps

1. Install Java JDK
2. Install Apache Tomcat
3. Install MySQL
4. Import project into Eclipse
5. Configure database connection
6. Run SQL script
7. Deploy project on Tomcat server

---

## Future Enhancements

- Mobile Application Support
- AI-based Food Recommendations
- Live GPS Tracking
- Email & SMS Notifications
- Cloud Deployment

---

## Author

Teja Swini
