# 🍽️ Food Ordering Website (React)

A modern and responsive food ordering website built with **React.js**. The application provides a smooth food ordering experience with user authentication, shopping cart management, delivery area selection, and persistent user data using Local Storage and Session Storage.

## ✨ Features

* Responsive and modern UI
* User Login & Signup
* Delivery Area Selection
* Shopping Cart
* Local Storage & Session Storage
* Interactive Loading Screen
* React Router Navigation
* Reusable React Components
* Responsive Design

## 🛠️ Technologies Used

* React.js
* React Router DOM
* JavaScript (ES6+)
* HTML5
* CSS3
* Bootstrap
* Local Storage
* Session Storage

## 📁 Project Structure

```text
food-ordering-website-react/
│
├── public/
│   ├── favicon.ico
│   ├── index.html
│   └── assets/
│
├── src/
│   ├── assets/                 # Images, icons and static files
│   │
│   ├── components/
│   │   ├── Home/               # Home page reusable sections
│   │   ├── Cards/              # Food cards
│   │   ├── Layouts/            # Navbar, Footer, Loader, Popup
│   │   └── UI/                 # Reusable UI components
│   │
│   ├── pages/
│   │   ├── Home/
│   │   │   ├── Home.jsx
│   │   │   └── Auth/
│   │   ├── Cart/
│   │   └── Auth/
│   │
│   ├── App.js
│   ├── index.js
│   └── index.css
│
├── package.json
├── package-lock.json
├── .gitignore
└── README.md
```

## 📂 Folder Explanation

### **public/**

Contains static files such as `index.html`, favicon, and other publicly accessible assets.

### **src/**

Contains the complete source code of the application.

### **assets/**

Stores images, logos, icons, and other static resources.

### **components/**

Contains reusable React components used across the application, including:

* Navbar
* Footer
* Loader
* Delivery Popup
* Food Cards
* Home Sections

### **pages/**

Contains page-level components:

* Home
* Authentication (Login / Signup)
* Shopping Cart

### **App.js**

Main application component responsible for routing and global state management.

### **package.json**

Contains project information, dependencies, and npm scripts.

## 🚀 Getting Started

Clone the repository:

```bash
git clone https://github.com/your-username/food-ordering-website-react.git
```

Move into the project folder:

```bash
cd food-ordering-website-react
```

Install dependencies:

```bash
npm install
```

Start the development server:

```bash
npm start
```

## 🔮 Future Improvements

* Backend Integration
* Online Database
* Payment Gateway
* Order Tracking
* Admin Dashboard
* Favorite Items
* Search & Filtering

## 👩‍💻 Author

Developed by **Shabiha Fatima**
