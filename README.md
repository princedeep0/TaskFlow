
# TaskFlow – Full Stack Task Management System

## Overview
TaskFlow is a **full-stack task management system** built with **Spring Boot** (backend) and **React.js** (frontend). It allows users to **create, update, delete, and track tasks** with **role-based access** and **JWT authentication**.

## Features
- **User Authentication & Authorization** (JWT)
- **CRUD Operations** for tasks
- **Role-based Access** (Admin/User)
- **Responsive UI** built with React.js
- **RESTful APIs** for backend communication
- **Database**: Oracle (production) / H2 (development)
- **Swagger API Documentation**
- **CI/CD** with GitHub Actions

## Tech Stack
- **Backend:** Java 11, Spring Boot, Hibernate, Maven
- **Frontend:** React.js, Axios
- **Database:** Oracle (prod), H2 (dev)
- **Version Control:** GitHub
- **Deployment:** Docker-ready

## Getting Started
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/TaskFlow.git
   ```
2. **Backend**:
   ```bash
   cd backend
   mvn spring-boot:run
   ```
3. **Frontend**:
   ```bash
   cd frontend
   npm install
   npm start
   ```
4. Access app at `http://localhost:3000`
