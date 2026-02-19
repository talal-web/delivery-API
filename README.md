# FastExpress Backend API

This is the **backend API** for the FastExpress delivery and shopping system.  
It is built with **Node.js**, **Express.js**, and **MongoDB**, and provides endpoints for managing:

- **Shopping Orders**: Users can place orders for groceries, vegetables, or other items for delivery.  
- **Parcel Orders**: Users can send parcels from one location to another.

The API is designed to be **modular, scalable, and easy to integrate** with a Next.js frontend.

---

## Features

- Create and retrieve shopping orders
- Create and retrieve parcel orders
- MongoDB database integration
- Express.js routing and controllers
- Centralized error handling
- Ready for admin dashboard integration

---

## Tech Stack

- **Node.js & Express.js** – Backend server  
- **MongoDB & Mongoose** – Database and ORM  
- **CORS & Morgan** – Middleware for API requests and logging  
- **dotenv** – Environment variables management

---

## API Endpoints

### Shopping Orders

| Method | Endpoint         | Description                  |
|--------|----------------|------------------------------|
| POST   | /api/shopping  | Create a new shopping order  |
| GET    | /api/shopping  | Retrieve all shopping orders |

### Parcel Orders

| Method | Endpoint         | Description                  |
|--------|----------------|------------------------------|
| POST   | /api/parcel    | Create a new parcel order    |
| GET    | /api/parcel    | Retrieve all parcel orders   |

---

## Getting Started

1. Clone the repository:

```bash
git clone https://github.com/yourusername/fastexpress-backend.git
