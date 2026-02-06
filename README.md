# RESTful Posts CRUD Web Application

A REST-based web application built using **Node.js, Express.js and EJS** that allows users to create, view, edit and delete posts.  
This project demonstrates REST architecture, routing, middleware usage and server-side rendering.

---

## Features
- Create a new post
- View all posts
- View individual post
- Edit post content
- Delete post
- Unique post identification using UUID
- Method override to support PATCH & DELETE in forms

---

## Tech Stack
- Node.js
- Express.js
- EJS (Templating Engine)
- UUID
- Method-Override
- HTML & CSS

---

## REST API Routes

| Method | Route | Description |
|------|------|------|
| GET | /posts | Get all posts |
| GET | /posts/new | Form to create post |
| POST | /posts | Create post |
| GET | /posts/:id | View single post |
| GET | /posts/:id/edit | Edit form |
| PATCH | /posts/:id | Update post |
| DELETE | /posts/:id | Delete post |

---

## Installation & Run Locally

```bash
git clone https://github.com/ritesh-kr18/REST_Post-Crud-App.git
cd REST_Post-Crud-App
npm install
nodemon index.js
```

Open in browser:
http://localhost:8080/posts

---

## Concepts Practiced
- RESTful Routing
- CRUD Operations
- Express Middleware
- Server Side Rendering
- Unique Resource Identification
- MVC Pattern Basics

---

## Author
Ritesh Kumar
