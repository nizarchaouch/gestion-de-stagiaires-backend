# Gestion de Stagiaires Backend

![Node.js](https://img.shields.io/badge/Node.js-Backend-339933)
![Express.js](https://img.shields.io/badge/Express.js-API-black)
![MongoDB](https://img.shields.io/badge/MongoDB-Database-47A248)
![JWT](https://img.shields.io/badge/JWT-Authentication-orange)
![Status](https://img.shields.io/badge/Status-Academic%20Project-blue)

This repository contains the backend of **Gestion de Stagiaires**, a full-stack web platform for internship request processing and intern administration.

The backend provides REST APIs for authentication, administrators, interns, supervisors, internship offers, requests, assignment management, forms, file upload, and database operations.

## Backend Responsibilities

- User authentication and login
- Administrators management
- Interns management
- Supervisors management
- Internship offers management
- Internship requests management
- Supervisor assignment handling
- Internship form management
- File upload handling
- Database communication through MongoDB
- REST API endpoints

## Tech Stack

- Node.js
- Express.js
- MongoDB
- Mongoose
- JWT
- bcryptjs
- Nodemailer
- Multer
- REST API
- JSON

## Getting Started

### Prerequisites

Make sure you have installed:

- Node.js
- npm
- MongoDB

### Clone the repository

```bash
git clone https://github.com/nizarchaouch/gestion-de-stagiaires-backend.git
cd gestion-de-stagiaires-backend
```

### Install dependencies

```bash
npm install
```

### Run the server in development mode

```bash
npm run dev
```

### Run in production

```bash
npm start
```

## API Modules

- Authentication
- Administrators
- Interns
- Supervisors
- Offers
- Requests
- Assignment
- Forms
- Upload

## Example Routes

```bash
/admin/login
/admin/AddAdmin
/admin/showAdmin
/stagiaire/addStagi
/stagiaire/showStagi
/encadreur/addEncad
/encadreur/showEncad
/offer/addOffer
/offer/showOffer
/demande/addDemande
/demande/showDemande
/form/showForm
/assigner/AddAssg
/upload
```

## Project Structure

```bash
internship-management-backend/
├── Admin/
├── Assigner/
├── Deamande/
├── Encadreur/
├── Form/
├── Offer/
├── Stagiaire/
├── public/
├── app.js
├── package.json
└── README.md
```

## Related Repository

Frontend repository: https://github.com/nizarchaouch/gestion-de-stagiaires-frontend.git
## Database

This project uses **MongoDB** as the main database system to store administrators, interns, supervisors, internship offers, requests, assignments, and related platform data.

## Notes

- The backend runs locally on port `8081`.
- CORS is configured for the frontend running on `http://localhost:8080`.
- File uploads are handled with **Multer** and stored in the `public/` directory.
- Database connection is configured in `app.js`.

## Author

**Nizar Chaouch**
