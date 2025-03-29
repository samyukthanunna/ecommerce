# eCommerce Website

This is a simple eCommerce website with an admin panel, built using PHP and MySQL.

## Features
- User registration and login
- Product listing
- Shopping cart functionality
- Admin panel to manage products
- Secure authentication system

## Project Structure
```
/ (Root Directory)
├── admin/              # Admin panel for managing products
├── css/                # Stylesheets
├── images/             # Product images and icons
├── includes/           # Database connection and utility files
├── pages/              # User-facing pages like home, cart, and checkout
├── index.php           # Main landing page
├── documentation/      # Step-by-step setup guides
```

## Setup Instructions

### 1. Database Setup
- Create a MySQL database named **ecommerce**.
- Import the provided SQL file into the database.
- Update the database credentials in `includes/db.php`.

### 2. Running the Project
- Place the project folder inside your web server directory (e.g., `htdocs` for XAMPP).
- Start your local server (Apache & MySQL via XAMPP or similar).
- Open `http://localhost/ecommerce_codewithswaroop-main/` in your browser.

### 3. Admin Access
- Admin login page: `http://localhost/ecommerce_codewithswaroop-main/admin/login.php`
- Default Admin Credentials (update in database if needed):
  - **Username:** admin
  - **Password:** admin

## Dependencies
- PHP
- MySQL
- Apache Server (XAMPP, WAMP, or LAMP)

## Notes
For further modifications, refer to the step-by-step setup guides provided in the `documentation/` folder.

