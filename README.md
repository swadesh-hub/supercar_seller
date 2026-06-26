🏎 SUPERCAR SELLER
Premium Automotive Marketplace

*Project Overview
The Supercar Seller Website is a premium online marketplace where users can explore, compare, and purchase luxury and high-performance vehicles. The platform combines stunning visual design with powerful search and filtering tools, delivering a world-class digital showroom experience.
Whether you're a seasoned collector or a first-time luxury buyer, the platform provides an easy, enjoyable, and informative way to discover some of the world's most iconic automobiles.

*User Experience
Attractive, high-contrast interface inspired by automotive aesthetics
Fast-loading image galleries with cinematic car photography
Side-by-side vehicle comparison tool
Saved favourites / wishlist functionality
Smooth animations and micro-interactions


 Problem Solved

Traditional car-buying platforms often lack an immersive experience for luxury vehicle enthusiasts. Supercar Seller addresses this by:

Providing a centralized platform for luxury car discovery.
Offering detailed vehicle specifications and comparisons.
Simplifying the process of exploring premium automobiles.
Creating a modern digital showroom for dealerships and buyers.
Tech Stack
Frontend
HTML5
CSS3
JavaScript
UI Frameworks
Bootstrap / Tailwind CSS (if used)
Future Integration
React.js
Node.js
Express.js
Database (Planned)
MongoDB / MySQL
Version Control
Git
GitHub
Prerequisites

Before running the project, ensure the following are installed:

Git
Node.js (v18 or later)
npm (Node Package Manager)
Modern Web Browser (Chrome, Edge, Firefox)

Check installations:

node -v
npm -v
git --version
Installation
Clone the Repository
git clone https://github.com/swadesh-hub/supercar_seller.git
Navigate to Project Directory
cd supercar_seller
Install Dependencies
npm install
Start Development Server
npm start
Build for Production
npm run build
Environment Variables

Create a .env file in the root directory:

PORT=3000
REACT_APP_API_URL=http://localhost:5000/api
Usage

Run the application:

npm start

Open your browser:

http://localhost:3000
Features
🚗 Luxury Car Listings
🔍 Advanced Search & Filtering
📊 Vehicle Comparison
❤️ Wishlist Functionality
📱 Fully Responsive Design
🎨 Modern Automotive UI
⚡ Fast Navigation Experience
📷 High-Quality Vehicle Galleries
API Reference
Get All Cars
GET /api/cars

Response:

[
  {
    "id": 1,
    "name": "Lamborghini Aventador",
    "price": 500000
  }
]
Get Car Details
GET /api/cars/:id
Add New Car
POST /api/cars

Payload:

{
  "name": "Ferrari SF90",
  "price": 600000,
  "brand": "Ferrari"
}
Tests

Run all tests:

npm test

Generate coverage report:

npm run test:coverage
Contact
Developer

Swadesh Narwariya

GitHub:
https://github.com/swadesh-hub
Acknowledgments

Special thanks to:

Open Source Community
GitHub
Automotive Design Inspiration Sources
Contributors and Supporters
Modern Web Development Community
