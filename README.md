# 🌸 Flora — Premium Online Flower Shop

> A modern, full-stack e-commerce web application for fresh handcrafted flowers and bouquets, built with Node.js, Express, and Vanilla JavaScript.

<br>

---

## 📋 Table of Contents

- [About the Project](#about-the-project)
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Project Structure](#project-structure)
- [Prerequisites](#prerequisites)
- [Installation & Setup](#installation--setup)
- [How to Run](#how-to-run)
- [Demo Credentials](#demo-credentials)
- [Website URLs](#website-urls)
- [Pages Overview](#pages-overview)
- [API Endpoints](#api-endpoints)
- [Design & Development](#design--development)

---

## 🏠 About the Project

**Flora** is a fully functional premium flower e-commerce website with:
- A stunning **user-facing storefront** for browsing and purchasing fresh blooms
- A comprehensive **admin panel** for managing orders, products, and messages
- **Role-based access** separating user and admin functionalities
- Indian Rupee (₹) pricing and local storage persistence
- Real-time order tracking and status management
- Dynamic dashboard with sales analytics

---

## ✨ Features

### 👤 User Features
- Browse specialized floral collections (Roses, Bouquets, Wedding, etc.)
- Add handcrafted arrangements to cart with real-time total calculation
- Secure login and personalized order history
- Track order status (Pending → Processing → Shipped → Delivered)
- Interactive contact form for custom floral inquiries
- Responsive design tailored for all devices

### 🔑 Admin Features
- Comprehensive dashboard with real-time stats (Total Sales, Orders, Products)
- Product Management (Add, Edit, Delete floral items)
- Order Management (Update status, modify order details)
- Message Center (View all customer inquiries)
- Protected login session for secure administration

### 🎨 Design Features
- Premium color palette (Deep Burgundy, Gold, and Cream)
- Smooth scroll and entrance animations (AOS Library)
- High-quality imagery from Unsplash and Pinterest
- Glassmorphism UI elements and frosted glass navigation
- Micro-interactions (Hover effects, button scaling, loader animations)
- Mobile-first approach with optimized touch targets

---

## 🛠 Tech Stack

| Layer        | Technology                        |
|-------------|-----------------------------------|
| **Frontend** | HTML5, CSS3, Vanilla JavaScript   |
| **Backend**  | Node.js, Express.js               |
| **Database** | JSON-based file persistence       |
| **Animations**| AOS (Animate On Scroll)          |
| **Icons**    | Font Awesome 6.4.0                |
| **Fonts**    | Google Fonts (Playfair Display, Outfit) |

---

## 📁 Project Structure

```
online flower shop/
│
├── backend/
│   ├── server.js          # Main Express server (Dual ports: 3000 & 3001)
│   └── data/
│       ├── products.json  # Product catalog
│       ├── orders.json    # Order records
│       ├── users.json     # User & Admin credentials
│       └── messages.json  # Contact form data
│
├── frontend/              # User Portal (Port 3000)
│   ├── index.html         # Homepage & Storefront
│   ├── style.css          # Global styles & animations
│   └── script.js          # Cart, Auth, and Order logic
│
├── admin-panel/           # Admin Portal (Port 3001)
│   ├── index.html         # Admin Interface
│   ├── admin.css          # Dashboard styling
│   └── admin.js           # Admin CRUD operations
│
├── assets/                # Local images and icons
├── package.json           # Project dependencies
└── README.md              # Project documentation
```

---

## ⚙️ Prerequisites

Make sure you have the following installed:

- **Node.js** v16+ → [Download](https://nodejs.org/)
- **npm** v8+ (comes with Node.js)
- A modern browser (Chrome, Firefox, Safari)

---

## 📦 Installation & Setup

### Step 1 — Navigate to the Project Directory

```bash
cd "online flower shop"
```

### Step 2 — Install Dependencies

```bash
npm install
```

### Step 3 — Start the Server

```bash
node backend/server.js
```

---

## 🚀 How to Run

### Expected Output

```
✔ User Website running at http://localhost:3000
✔ Admin Panel running at http://localhost:3001/admin
```

### Open in Browser

| Purpose      | URL                                   |
|-------------|---------------------------------------|
| User Portal | http://localhost:3000                 |
| Admin Panel | http://localhost:3001/admin           |

---

## 🔐 Demo Credentials

### 👤 Regular User
| Field    | Value               |
|----------|---------------------|
| Email    | `urza@user.com`     |
| Password | `1234`              |
| Access   | Shop, Cart, My Orders |

### 🔑 Admin
| Field    | Value               |
|----------|---------------------|
| Email    | `urza@admin.com`    |
| Password | `1234`              |
| Access   | Full Dashboard, Orders, Products, Messages |

---

## 🌐 Website URLs

### User-Facing (Port 3000)
- **Home/Shop:** [http://localhost:3000](http://localhost:3000)

### Admin (Port 3001)
- **Admin Dashboard:** [http://localhost:3001/admin](http://localhost:3001/admin)

---

## 📄 Pages Overview

### 🏠 Home Page
- Dynamic hero section with premium typography
- Featured categories (Roses, Bouquets, Wedding, Plants)
- Top-selling product grid with "Add to Cart"
- "Our Story" brand segment
- Interactive customer testimonials
- Multi-channel contact section

### ⚙️ Admin Panel
- **Dashboard:** At-a-glance sales performance and summaries
- **Orders:** Comprehensive table with status update controls
- **Products:** Full inventory management (CRUD)
- **Messages:** Centralized inbox for customer inquiries

---

## 🎨 Design & Development

### Color Palette
| Name      | Hex        | Usage                    |
|-----------|-----------|--------------------------|
| Burgundy  | `#9B1B30` | Primary accent, luxury feel |
| Crimson   | `#D4373F` | Hover states, notifications |
| Gold      | `#C5A059` | Secondary accents, badges |
| Charcoal  | `#1A1A1A` | Headings, text           |
| Cream     | `#F8F4F0` | Elegant background       |

### Fonts
- **Playfair Display** — Seraphic, luxury headings
- **Outfit** — Clean, modern sans-serif for UI elements

---

## 👨‍💻 Developed By

<div align="center">

### Prathamesh Giri

**Full-Stack Developer**

🌐 [prathameshgiri.in](https://prathameshgiri.in/)

*Built with dedication for Uzra Devnale’s College Project*

---

**Project:** Flora — Premium Online Flower Shop
**Year:** 2026
**Stack:** Node.js · Express · Vanilla JS · HTML5 · CSS3

</div>

---

## 📝 License

This project was created as a college project and is for educational purposes.

---

<div align="center">
  <strong>Flora</strong> — Fresh Flowers Delivered With Love 🌸
</div># flowershop
