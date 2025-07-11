# supermarket-management-system
A simple yet functional PHP & MySQL-based supermarket management system to handle customer details, inventory, transactions, staff, suppliers, and promotions in a user-friendly interface.

📁 Project Structure
bash
Copy
Edit
supermarket-management-master/
│
├── index.php                  # Entry point (Dashboard/Login)
├── addproduct.php             # Add new product to inventory
├── addcustomer.php            # Add new customer
├── addemp.php                 # Add employee
├── addsupplier.php            # Add supplier details
├── sell.php                   # Sales/Transaction interface
├── viewlist.php               # View product list
├── css/                      # Stylesheets
├── images/                   # Static assets
├── estore.sql                # Sample database
├── supermarket_160713.sql    # Alternate database schema
├── login.php / logout.php    # Authentication
└── ...
🧰 Technologies Used
Frontend: HTML, CSS

Backend: PHP

Database: MySQL

Server: XAMPP / Apache (Localhost setup)

⚙️ How to Run This Project
1. 📥 Requirements
XAMPP or any Apache + MySQL stack

Web browser

2. 📂 Setup
Extract the folder to:
C:\xampp\htdocs\supermarket-management-master

Start Apache and MySQL from XAMPP

3. 🗃️ Database Setup
Open http://localhost/phpmyadmin

Create a new database: estore

Import either:

estore.sql (simpler)

or supermarket_160713.sql (extended)

4. 🚀 Run the System
Open browser and go to:
http://localhost/supermarket-management-master

5. 🔐 Login
If login is required, check login.php or estore.sql for default credentials (usually admin / admin or similar)
