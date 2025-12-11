# MERN CRUD API (Express + MongoDB)
This repository contains a simple RESTful API for `Product` resources built with Express.js and MongoDB (Mongoose).
## Features
- CRUD endpoints: POST / GET / PUT / DELETE
- Input validation using `express-validator`
- Centralized error handling middleware
## Project Structure
```
project-root/
├── server.js
├── .env
├── models/
│   └── Product.js
├── controllers/
│   └── productController.js
├── routes/
│   └── productRoutes.js
└── middleware/
    └── validateProduct.js
```
## Setup (locally)
1. Clone the repo (or download the zip).
2. Copy `.env.example` to `.env` and set `MONGODB_URI`.
3. Install dependencies:
```
npm install
```
4. Start MongoDB (e.g. `mongod`).
5. Run:
```
npm run dev
```
6. Test endpoints with Postman or Thunder Client:
- POST `/api/products` with JSON `{ "name": "Laptop", "price": 999.99 }`
- GET `/api/products`
- PUT `/api/products/:id`
- DELETE `/api/products/:id`
## How to push to GitHub
1. Initialize a git repo:
```
git init
git add .
git commit -m "Initial commit - MERN CRUD API"
```
2. Create repository on GitHub (via website) and follow their instructions:
```
git remote add origin https://github.com/<your-username>/<your-repo>.git
git branch -M main
git push -u origin main
```
## Notes
This project was prepared from the task description you uploaded. See the original task file for details. 
