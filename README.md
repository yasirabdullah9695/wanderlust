# PROJECT-Wanderlust

# 🌍 Wanderlust - Full-Stack Rental Platform

**Wanderlust** is a full-stack rental platform that connects travelers with unique rental properties around the world. Built with a focus on user experience, security, and scalability, Wanderlust provides an intuitive interface for both travelers and hosts to browse, book, and manage rental listings with ease.



--------------------

## ✨ Key Features

- **🔐 User Authentication & Security**  
  Secure login and registration system implemented using **Passport.js**, **JWT**, **Express Sessions**, and **Cookie Parser**.

- **🏡 Property Management Dashboard**  
  Hosts can easily list properties, manage availability, and handle booking requests via an intuitive dashboard.

- **✅ Form Validations & Error Handling**  
  Robust validation for user input and centralized error handling ensure smooth user experience and data integrity.

- **📸 Image Upload & Cloud Storage**  
  Integrated **Multer** and **Cloudinary** for fast and secure image uploads and cloud storage.

- **🛠️ Admin Panel**  
  A dedicated admin panel for monitoring user activity, managing listings, and ensuring smooth platform operations.

- **📁 MVC Architecture**  
  Organized and scalable codebase following the **Model-View-Controller** pattern.

-------------------

## 🛠️ Tech Stack

### Frontend
- HTML, CSS, JavaScript
- Bootstrap
- EJS (Embedded JavaScript Templates)

### Backend
- Node.js, Express.js
- RESTful APIs
- Express Router
- Middleware & Custom Error Handlers

### Database
- MongoDB with MongoDB Atlas
- Mongo Session Store

### Authentication
- Passport.js (Local Strategy)
- Express Sessions
- Cookie Parser

### Image Upload & Storage
- Multer
- Cloudinary

### Deployment
- **Render** for full-stack deployment
- **Git & GitHub** for version control

-------------------

## 🚀 Getting Started Locally


1. **Install dependencies**  
   ```bash
   npm install
   ```

2. **Setup environment variables**  
   Create a `.env` file in the root directory and add the following:
   ```env
   CLOUDINARY_CLOUD_NAME=your_cloud_name
   CLOUDINARY_KEY=your_api_key
   CLOUDINARY_SECRET=your_api_secret
   DB_URL=your_mongodb_connection_string
   SECRET=session_secret_key
   ```

3. **Run the server**  
   ```bash
   npm start
   ```

4. Visit `http://localhost:3000` in your browser.

--------------------

## 🧠 What I Learned

- Building secure and scalable authentication systems with Passport.js and sessions.
- Structuring a backend using the MVC pattern for clean code and scalability.
- Integrating third-party services like Cloudinary for image storage.
- Handling CRUD operations and RESTful API development.
- Deploying full-stack applications using Render.

--------------------

## 🤝 Contributing

Pull requests are welcome! For major changes, please open an issue first to discuss what you’d like to change.

--------------------

## 📜 License

This project is open-source and available under the [MIT License](LICENSE).

--------------------

