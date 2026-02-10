# kushibookstore
<img width="200" height="200" alt="Untitled design" src="https://github.com/user-attachments/assets/260d215b-b91a-4615-8727-f201905a67de" />

Here's a detailed overview of the Online Book Store (E-commerce) project:

Project Overview
An e-commerce platform for buying and selling books online. Users can browse, search, and purchase books, while admins manage inventory and orders.

Key Features
- User Registration/Login: Secure signup/login with password hashing.
- Book Catalog: Display books with details (title, author, price, etc.).
- Search/Filter: Search books by title, author, genre, etc.
- Cart/Checkout: Add books to cart and process payments.
- Order Management: Track orders and manage inventory (admin).
- Payment Gateway: Integrate payment options (e.g., PayPal, Stripe).

Tech Stack
- Frontend: HTML5, CSS3, JavaScript (for client-side interactions).
- Backend: Java (Servlet/JSP/Spring Boot) for server-side logic.
- Database: MySQL for storing books, users, orders, etc.

Core Functionality
1. User Registration/Login:
    - Users sign up with email, password, and basic info.
    - Passwords are hashed and stored securely.
2. Book Catalog:
    - Display books with images, descriptions, and prices.
    - Users can view book details.
3. Search/Filter:
    - Users search books by title, author, genre, etc.
4. Cart/Checkout:
    - Users add books to cart and proceed to checkout.
    - Payment processing and order confirmation.
5. Order Management:
    - Admins manage book inventory and track orders.

Database Schema
- Users Table: id, email, password, name, etc.
- Books Table: id, title, author, price, etc.
- Orders Table: id, user_id, book_id, order_date, etc.

Workflow
- Client (Browser) <-> Java Backend (API) <-> MySQL Database
- User interactions trigger API calls to the Java backend.
- Backend processes requests, interacts with the database, and returns responses.

