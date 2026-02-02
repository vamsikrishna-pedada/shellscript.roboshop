# 🛒 Roboshop Automation using Shell Scripting

This repository contains **Shell scripts to automate the deployment of the Roboshop e-commerce application**, which follows a **microservices architecture with 12+ services**, deployed on **AWS EC2 instances**.

---

## 📌 Project Overview

The objective of this project is to learn and implement **Shell Scripting** by automating a real-world microservices application.  
Each Roboshop service is deployed using an individual shell script with reusable logic to ensure clean, maintainable, and scalable automation.

---

## 🚀 Features

- Automated deployment of 12+ microservices
- Modular and reusable shell scripts
- Centralized common functions
- Systemd service configuration
- Database and message broker setup
- AWS EC2 ready deployment

---

## 🧰 Technologies Used

- Shell Scripting (Bash)
- Linux (Amazon Linux / RHEL)
- AWS EC2
- Nginx
- MongoDB
- MySQL
- Redis
- RabbitMQ
- Systemd
- Microservices Architecture

---

## 📂 Repository Structure

```bash
.
├── roboshop.sh
├── common.sh
├── frontend.sh
├── cart.sh
├── catalogue.sh
├── user.sh
├── payment.sh
├── shipping.sh
├── mongodb.sh
├── mysql.sh
├── redis.sh
├── rabbitmq.sh
├── mongo.repo
├── rabbitmq.repo
├── nginx.conf
├── cart.service
├── catalogue.service
├── user.service
├── payment.service
├── shipping.service
└── README.md
