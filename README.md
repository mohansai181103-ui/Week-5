Advanced E-Commerce
Project Overview
A modern multi-page e-commerce frontend built using React + Vite, demonstrating product catalog management, shopping cart functionality, order processing, tracking system, and REST API integration using Axios.
This project simulates a real-world e-commerce workflow and focuses on clean component architecture, state management, routing, and dynamic business logic handling.
Features
Product Catalog
API-based product fetching
Search functionality using ?search= query parameter
Dynamic product grid rendering
Re-fetch products when search query changes
Shopping Cart
Add items to cart
Remove items from cart
Update item quantity
Select delivery options
Real-time order summary updates
Automatic tax calculation
Orders Page
View previous orders
Display multiple products per order
Re-add items to cart
Tracking Page
Dynamic routing using order ID
Order-specific tracking status
Navigation from Orders page to Tracking page
API Integration
All REST operations implemented using Axios:
GET – Fetch products
POST – Create orders / add items
PUT – Update cart quantity
DELETE – Remove items from cart
Async/await is used for clean and readable API handling.

Technologies Used
React 18
Vite
React Router DOM
Axios
JavaScript (ES6+)
HTML
CSS
REST API Integration
Project Structure
ecommerce-project/
│── src/
│   ├── components/
│   │   ├── Header/
│   ├── pages/
│   │   ├── HomePage.jsx
│   │   ├── CheckoutPage.jsx
│   │   ├── OrdersPage.jsx
│   │   ├── TrackingPage.jsx
│   │   └── NotFoundPage.jsx
│   ├── utils/
│   │   └── money.js
│   ├── App.jsx
│   └── main.jsx
│── public/
│── package.json
│── README.md
Setup Instructions
Clone the repository
git clone: https://github.com/mohansai181103-ui/Week-5.git     
