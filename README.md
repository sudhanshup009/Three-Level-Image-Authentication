# 🔐 Three-Level Image Authentication System

## Overview

The Three-Level Image Authentication System is a secure web application developed to enhance user authentication by implementing multiple layers of security. Traditional login systems rely only on usernames and passwords, which can be vulnerable to various cyberattacks. To address this issue, our project introduces a three-step authentication process that significantly improves account security.

The system verifies a user through:

1. Username and Password Authentication
2. Image-Based Authentication
3. Email OTP Verification

Only after successfully completing all three levels is the user granted access to the system.

---

## Problem Statement

Most online applications still depend heavily on password-based authentication. Weak passwords, password reuse, phishing attacks, and credential leaks can compromise user accounts.

This project aims to strengthen authentication by combining graphical authentication and OTP verification with traditional password-based login, making unauthorized access much more difficult.

---

## Objectives

* Develop a secure multi-factor authentication system.
* Implement image-based authentication as an additional security layer.
* Integrate OTP verification using email services.
* Protect user credentials using password hashing techniques.
* Provide a simple and user-friendly authentication process.

---

## Features

### Level 1: Password Authentication

* User Registration
* User Login
* Password Hashing
* Credential Verification

### Level 2: Image Authentication

* Secret image selection during registration
* Image password verification during login
* Graphical authentication layer

### Level 3: OTP Verification

* Automatic OTP generation
* OTP delivery through email
* OTP expiration handling
* OTP resend functionality

### Additional Features

* Session Management
* Secure Authentication Flow
* Responsive User Interface
* SQLite Database Integration

---

## Technology Stack

### Frontend

* HTML5
* CSS3
* JavaScript

### Backend

* Python
* Flask Framework

### Database

* SQLite

### Authentication & Security

* Password Hashing
* Email OTP Verification
* Multi-Factor Authentication

### Email Service

* SMTP Email Integration

---

## System Workflow

```text
User Registration
        │
        ▼
Store User Credentials
        │
        ▼
User Login
        │
        ▼
Username & Password Verification
        │
        ▼
Image Authentication
        │
        ▼
Email OTP Verification
        │
        ▼
Access Granted
```

---

## Project Structure

```text
Three-Level-Image-Authentication-System/
│
├── app.py
├── database.db
├── requirements.txt
│
├── templates/
│   ├── login.html
│   ├── register.html
│   ├── image_auth.html
│   ├── otp_verification.html
│   └── dashboard.html
│
├── static/
│   ├── css/
│   ├── js/
│   └── images/
│
└── README.md
```

---

## Installation

### Clone the Repository

```bash
git clone https://github.com/your-username/three-level-image-authentication-system.git
cd three-level-image-authentication-system
```

### Create Virtual Environment

```bash
python -m venv venv
```

### Activate Virtual Environment

Windows:

```bash
venv\Scripts\activate
```

Linux / macOS:

```bash
source venv/bin/activate
```

### Install Required Packages

```bash
pip install -r requirements.txt
```

### Run the Application

```bash
python app.py
```

Open your browser and visit:

```text
http://127.0.0.1:5000
```

---

## Security Features

* Password Hashing
* Multi-Factor Authentication (MFA)
* OTP-Based Verification
* Session Management
* Secure Credential Storage
* Protection Against Unauthorized Access

---

## Future Enhancements

Some features that can be added in future versions:

* Mobile OTP Integration
* Face Recognition Authentication
* Biometric Verification
* JWT-Based Authentication
* Admin Dashboard
* User Activity Monitoring
* Login History Tracking
* Account Lockout After Multiple Failed Attempts

---

## Learning Outcomes

Through this project, we gained practical experience in:

* Flask Web Development
* Database Management
* Authentication Systems
* Cybersecurity Concepts
* Multi-Factor Authentication
* Email Automation
* Secure Coding Practices

---

## Authors

**Sudhanshu Pandey**
Enrollment No.: 202410101360254

**Rohit Maurya**
Enrollment No.: 202410101360246


Bachelor of Computer Applications (Data Science / Artificial Intelligence)

Shri Ramswaroop Memorial University, Barabanki, Uttar Pradesh
