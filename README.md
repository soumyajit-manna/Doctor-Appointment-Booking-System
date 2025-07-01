# 🏥 Prescripto – Doctor Appointment Booking System

## 📌 Project Description
Prescripto is a full-stack healthcare web application where patients can book doctor appointments, make secure payments using Razorpay, and manage their profiles. It features **role-based access** for Patients, Doctors, and Admins with dedicated dashboards.

---

## 🌐 Live Demo
- **User App**: [https://prescripto-frontend-two.vercel.app](https://prescripto-frontend-two.vercel.app)  
- **Admin Dashboard**: [https://prescripto-admin-theta.vercel.app](https://prescripto-admin-theta.vercel.app)  
- **GitHub Repo**: [Prescripto GitHub](https://github.com/soumyajit-manna/Doctor-Appointment-Booking-System.git)

---

## 🧰 Tech Stack

- **Frontend**: React.js, Tailwind CSS
- **Backend**: Node.js, Express.js
- **Database**: MongoDB (MongoDB Atlas)
- **Authentication**: JWT
- **Payment Integration**: Razorpay
- **Hosting**: Vercel (Frontend), Vercel (Backend)
- **Version Control**: Git, GitHub

---

## ✨ Features

### 👥 Users:
- Patient signup/login
- View doctor profiles and availability
- Book appointments by date/time/doctor
- Pay for appointments using Razorpay
- View past/future appointments

### 🩺 Doctors:
- Secure doctor login
- View appointments
- Track earnings
- Update profile and availability

### 🛠 Admin:
- Admin login panel
- Manage all users (doctors & patients)
- View, approve or cancel appointments
- System-wide control over data

---

## 🔐 Authentication & Authorization
- JWT tokens for login sessions
- Protected routes for role-based access (Doctor, Patient, Admin)
- Custom middleware to verify tokens and user roles

---

## 💳 Razorpay Integration
- Razorpay order is created on backend after form submission
- Payment is processed on frontend and verified via signature on backend
- Appointment is saved in MongoDB only if payment is verified

---

## 🧪 How to Run Locally

```bash
# Clone repo
git clone https://github.com/soumyajit-manna/Doctor-Appointment-Booking-System.git
cd Doctor-Appointment-Booking-System

# Setup backend
cd backend
npm install
# Create .env file with Razorpay keys, JWT secret, Mongo URI

# Setup frontend
cd ../frontend
npm install
