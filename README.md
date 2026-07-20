# Customer Care Registry

A full-stack Customer Care Registry application developed using the MERN stack architecture. This project allows users to register, log in, create support tickets, track ticket status, and enables administrators to manage customer support efficiently.

> **Note:** This version uses **JSON file storage** instead of MongoDB. All application data is stored locally in JSON files.

---

## Features

### Authentication
- User Registration
- User Login
- JWT Authentication
- Role-based Access (Admin & User)

### Customer Management
- Add Customers
- View Customer List
- Search Customers

### Ticket Management
- Create Support Tickets
- View Tickets
- Update Ticket Status
- Change Ticket Priority
- Add Interaction Notes
- Filter Tickets by Status

### Dashboard
- Total Tickets
- Open Tickets
- In Progress Tickets
- Resolved Tickets
- Closed Tickets
- Average Feedback Rating

### Feedback
- Submit Feedback
- View Feedback Analytics

---

## Tech Stack

### Frontend
- React.js
- React Router
- Axios
- CSS

### Backend
- Node.js
- Express.js
- JWT Authentication
- bcryptjs

### Database
- Local JSON File Storage

---

```
```

---

## Installation


```
```

### Backend

```bash
cd backend
npm install
npm run dev
```

Backend runs on:

```
http://localhost:5000
```

### Frontend

```bash
cd frontend
npm install
npm run dev
```

Frontend runs on:

```
http://localhost:5173
```

---

## Default Admin Login

```
Email:
admin@ccr.com

Password:
Admin@123
```

---

## User Registration

New users can register using:

- Name
- Email
- Password

After registration, users can log in using their credentials.

---

## Data Storage

Application data is stored in:

```
backend/data/users.json
backend/data/complaints.json
```

No MongoDB installation is required.

---

## Future Improvements

- Ticket Delete
- Ticket Edit
- Email Notifications
- File Upload Support
- Advanced Search
- Reports
- Export Tickets to PDF
- Role-based Ticket Visibility

---

## Developed By

MYSARAJU SRAVANI

