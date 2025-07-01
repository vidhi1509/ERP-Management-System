# 💼 ERP Management System

An intuitive, PHP-based **ERP Management System** for efficient handling of services, events, bookings, user management, and more. This system provides a comprehensive dashboard for managing day-to-day operations within an organization.

---

## 🛠️ Features

✅ User Registration & Authentication  
✅ Role-based Permission Management  
✅ Event & Service Management  
✅ Booking System with Approval & Cancellation  
✅ Invoice Generation  
✅ Booking & Event Reports  
✅ Password Recovery & Profile Management  
✅ Clean & Organized Dashboard  

---

## 📁 Project Structure

```plaintext
├── index.php                  # Login page
├── dashboard.php              # Main admin dashboard
├── newuser.php / newuser_form.php  # Add new users
├── manage_event.php           # Event management
├── manage_service.php         # Service management
├── booking_report.php         # Booking reports
├── approved_bookings.php      # Approved bookings
├── cancelled_bookings.php     # Cancelled bookings
├── user_permission.php        # User permissions management
├── invoice_generating.php     # Invoice generation
├── profile.php                # User profile
├── forgot_password.php        # Password recovery
├── dbconnection.php           # Database connection
└── ... other supporting files
```

---

## 🖥️ Technologies Used

- PHP - Server-side scripting
- MySQL - Database
- HTML/CSS - Frontend structure and styling
- JavaScript - Client-side interaction (if applicable)

---

## 🧑‍💻 Setup Instructions

1. Clone the Repository
```
git clone https://github.com/your-username/ERP-Management-System.git
```

2. Setup the Database
- Import the provided SQL file (if available) into your MySQL server.
- Update dbconnection.php with your database credentials.

3. Run the Application
- Place the project files in your server's root directory (e.g., htdocs for XAMPP).
- Start Apache and MySQL services.
- Access the system via:
```
http://localhost/ERP-Management-System/index.php
```
