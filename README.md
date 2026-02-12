# 🚀 AWS EC2 Nginx Static Website Deployment

## 📌 Project Overview
This project demonstrates how to deploy a static website on an Amazon EC2 instance using Nginx web server.

The application is publicly accessible using the EC2 Public IP address.

---

## 🏗 Architecture

User (Browser)
        ↓
Public IP (Port 80)
        ↓
Amazon EC2 Instance (Amazon Linux 2023)
        ↓
Nginx Web Server
        ↓
Static HTML Website

---

## 🛠 Technologies Used
- Amazon EC2
- Amazon Linux 2023
- Nginx
- HTML
- Git & GitHub
- Linux CLI

---

## ⚙️ Deployment Steps

1. Launched EC2 instance in AWS.
2. Configured Security Group:
   - Port 22 (SSH)
   - Port 80 (HTTP)
3. Connected using EC2 Instance Connect.
4. Installed Nginx using package manager.
5. Replaced default Nginx index file.
6. Restarted Nginx service.
7. Verified website via Public IP.

---

## 🌐 Live Demo
http://98.80.13.184

---

## 🎯 Learning Outcomes
- Cloud server provisioning
- Linux server management
- Nginx configuration
- Static website hosting
- Git version control & remote repository management

