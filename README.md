School-Management-System
# School Management System

A comprehensive collection of school management applications built with different technology stacks to streamline administrative tasks, class organization, and communication between students, teachers, and administrators.

##  Project Overview

This repository contains three different implementations of a School Management System, each built with different technologies:

### 1. **MERN School Management System** (React + Node.js)
A full-stack web application built using the MERN stack (MongoDB, Express.js, React.js, Node.js).

**Key Features:**
- User roles: Admin, Teacher, and Student
- Admin dashboard for managing students, teachers, classes, and subjects
- Attendance tracking system
- Performance assessment with marks and feedback
- Data visualization with interactive charts
- Real-time communication between users
- Redux for state management
- Material UI for responsive design

**Tech Stack:**
- Frontend: React.js, Redux, Material UI
- Backend: Node.js, Express.js
- Database: MongoDB

**Location:** `/MERN-School-Management-System/`

---

### 2. **Django School Management System** (Python/Django)
A traditional server-side rendered web application built with Django and SQLite.

**Key Features:**
- Three user portals: Admin, Teacher, and Student
- Student admission requests and approvals
- Teacher job applications and approvals
- Attendance management system
- Notice board for communications
- Profile management
- Role-based access control

**Tech Stack:**
- Backend: Django (Python)
- Database: SQLite
- Frontend: HTML, CSS, JavaScript

**Location:** `/schoolmanagement/`

---

### 3. **Milestone Project** (React)
A React-based application with additional features and improvements.

**Location:** `/Milestone/`

---

##  Getting Started

### Prerequisites
- **For MERN Stack:** Node.js, npm, MongoDB
- **For Django:** Python 3.8+, pip
- **For Milestone:** Node.js, npm

### Installation

#### MERN School Management System
```bash
cd MERN-School-Management-System

# Backend setup
cd backend
npm install
npm start

# Frontend setup (in a new terminal)
cd ../frontend
npm install
npm start


User Roles & Capabilities
Admin
Add/manage students and teachers
Create classes and subjects
View system-wide reports
Manage user accounts
Post notices and announcements
Teacher
Take attendance
Mark student performance
Provide feedback
View class records
Post notices to students
Student
View attendance records
Check marks and feedback
Visualize performance data
View notices and announcements
Communicate with teachers
