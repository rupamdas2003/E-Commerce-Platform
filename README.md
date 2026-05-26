# E-Commerce-Platform
An advanced and user-friendly web application that enables customers to buy products online with secure authentication, product management, online payments, and real-time order tracking.

## Description
The E-Commerce Platform is a full-stack web application developed using the MERN Stack — MongoDB, Express.js, React.js, and Node.js.
It provides a seamless online shopping experience where users can browse products, manage carts, place orders securely, and track their purchases.

The platform also includes an Admin Dashboard for managing products, users, and orders efficiently.
Cloudinary integration is used for optimized image storage and management, while JWT authentication ensures secure user access.

The application features a modern, responsive UI that works smoothly across desktop, tablet, and mobile devices.



## Features

👤 User Features
1. User Registration and Login Authentication
2. Secure JWT-based Authorization
3. Browse Products with Search & Filters
4. Add/Remove Products from Cart
5. Wishlist and Product Reviews
6. Secure Checkout and Online Payments
7. Order History and Order Tracking
8. Responsive UI for Mobile and Desktop

🛠️ Admin Features
1. Admin Dashboard
2. Manage Products (Create, Update, Delete)
3. Manage Users and Orders
4. Upload Multiple Product Images
5. Monitor Sales and Order Status

🔒 Security Features
1. Password Encryption
2. Protected Routes and APIs
3. Secure Payment Integration
4. Authentication using JWT Tokens




## Technologies Used

Frontend:
i)React.js
ii)Redux Toolkit
iii)React Router DOM
iv)Axios
v)Bootstrap / CSS

Backend:
i)Node.js
ii)Express.js
iii)JWT Authentication
iv)REST APIs

Database:
i)MongoDB
ii)Mongoose

Third-Party Services:
i)Cloudinary (Image Storage)
ii)Stripe / Razorpay (Payment Gateway)


## Installation and Setup


1. **Clone the repository**:
    ``` bash
    git clone https://github.com/vishalyadav0987/E-Commerce.git
    cd E-COMMERCE
    ```

2. **Install backend dependencies**:
    ``` bash
    cd backend
    npm install
    ```

3. **Install frontend dependencies**:
    ```bash
    cd ../frontend
    npm install
    ```

4. **Start the development servers**:
    - Backend server:
      ```bash
      cd ../backend
      npm start
      ```
      - Frontend server:
      ```bash
      cd ../frontend
      npm run dev
      ```
## Configure Environment Variables

1. Create a **.env** file in the backend directory and add the following.
2. Essential Variables
3. PORT=4000
4. MONGO_URI 
5. STRIPE_API_KEY
6. STRIPE_SECERET_KEY
7. JWT_SECERET
8. JWT_LIFETIME
9. JWT_COOKIE_EXPIRE
10. SMPT_SERVICE
11. SMPT_MAIL
12. SMPT_PASSWORD
13. SMPT_HOST
14. SMPT_PORT
15. CLOUDINARY_NAME
16. CLOUDINARY_API_KEY
17. CLOUDINARY_API_SECRET
Fill each filed with your info respectively.


## Usage

1. Open your browser and navigate to **http://localhost:5173** to access the frontend.
2. Use Postman or any API client to interact with the backend via **http://localhost:4000**.

## Core Functionalities

1. Product Listing & Details
2. Cart Management
3. User Authentication
4. Secure Payment Processing
5. Order Placement & Tracking
6. Product Reviews & Ratings
7. Admin Product Management


## Future Enhancements

1. AI-based Product Recommendations
2. Live Chat Support
3. Multi-Vendor Marketplace
4. Dark Mode UI
5. Advanced Analytics Dashboard
6. Social Media Login Integration
7. PWA (Progressive Web App) Support
