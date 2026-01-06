# Hospital Appointment Booking System 🏥

## Description
The Hospital Appointment Booking System is a full-stack web application developed using **PHP, MySQL, HTML, CSS, and JavaScript**. The system allows patients to book appointments with doctors online, doctors to manage their schedules, and administrators to control users and appointments efficiently.

This project helps reduce manual appointment handling and improves hospital workflow by providing an easy-to-use, role-based system for **Admin, Doctor, and Patient** users.

---

## Roles & Features

### Admin
- Manage doctors and patients
- View all appointments
- Control system data

### Doctor
- View booked appointments
- Manage availability
- Update appointment status

### Patient
- Register and log in
- Book doctor appointments
- View appointment history

---

## Technologies Used
- Frontend: HTML, CSS, JavaScript
- Backend: PHP
- Database: MySQL
- Server: Apache (XAMPP / WAMP)

---

## Project Structure
hospital-appointment-booking-system/
│── admin/ # Admin dashboard
│── doctor/ # Doctor dashboard
│── patient/ # Patient dashboard
│── css/ # Stylesheets
│── img/ # Images
│── connection.php # Database connection
│── login.php # Login page
│── signup.php # Registration page
│── logout.php # Logout functionality
│── create-account.php # Account creation
│── index.html # Home page
│── SQL_Database_edoc.sql # Database file
│── README.md


---

## How to Run the Project

### Step 1: Install XAMPP
Download and install **XAMPP** and start **Apache** and **MySQL**.

### Step 2: Setup Database
1. Open **phpMyAdmin**
2. Create a database (e.g., `hospital_db`)
3. Import `SQL_Database_edoc.sql`

### Step 3: Configure Database
Edit `connection.php`:
```php
$conn = mysqli_connect("localhost", "root", "", "hospital_db");

**Step 4: Run the Project**

Copy project folder to:

xampp/htdocs/

Open browser and go to:

http://localhost/hospital-appointment-booking-system
