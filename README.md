# Airline Management System (Microservices)

## Overview
A scalable backend system built using microservices architecture for managing airline operations such as authentication, flight search, booking, and notifications.

## Architecture
The system is divided into independent services communicating via REST APIs through an API Gateway.

## Services
- Auth Service: https://github.com/zyphorixx/AuthService
- Flight & Search Service: https://github.com/zyphorixx/FlightsAndSearchService
- Booking Service: https://github.com/zyphorixx/BookingService
- Reminder Service: https://github.com/zyphorixx/ReminderService
- API Gateway: https://github.com/zyphorixx/Airline-API-Gateway

## Tech Stack
Node.js, Express.js, MySQL, Sequelize ORM, REST APIs, Microservices

## Features
- User authentication and authorization (JWT-based)
- Flight search and management
- Booking system
- Notification/reminder service
- Centralized API Gateway for routing
- Database integration using MySQL with Sequelize ORM
