# Learnify

A modular Learning Management System (LMS) featuring secure APIs, dynamic dashboards, and role-based access — built for Admins, Instructors, and Students.

**Live Preview**: _[Coming Soon or replace with deployed link]_

---

## Overview

Learnify is a full-stack LMS platform that streamlines online education through customized dashboards, real-time data handling, and secure API integrations. With three distinct user roles — Admin, Instructor, and Student — the platform ensures scalability, modularity, and clean UI/UX for modern digital classrooms.

---

## Key Features

- **Role-Based Dashboards**  
  Separate interfaces for Admins, Instructors, and Students, each with specific access and functionality.

- **Secure REST APIs**  
  Built with JWT-based authentication and authorization, covering user registration/login, course management, assessments, and more.

- **Modular Architecture**  
  Components and routes are organized into independent modules for easy scalability and maintenance.

- **Centralized State Management**  
  Redux Toolkit is used to manage global state across all key modules efficiently.

---

## Tech Stack

### Frontend
- React.js
- Redux Toolkit
- Tailwind CSS
- React Router DOM

### Backend
- Node.js
- Express.js
- MongoDB
- Mongoose ODM
- JSON Web Tokens (JWT)

### Utilities & Tooling
- Postman (API testing)
- Dotenv (environment configuration)
- ESLint, Prettier (code formatting and linting)

---

## Folder Structure

<pre>
learnify/
├── client/                   # React frontend
│   └── src/
│       ├── components/       # Reusable UI components
│       ├── pages/            # Main pages and routes
│       ├── redux/            # Redux store and slices
│       └── App.js
├── server/                   # Node.js backend
│   ├── controllers/          # Route logic
│   ├── routes/               # Express route handlers
│   ├── middleware/           # JWT, auth, error handling
│   ├── models/               # Mongoose schemas
│   └── server.js
├── .env                      # Environment variables
└── README.md
</pre>

---

## Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/riddhiJainSDE/learnify.git
cd learnify
