# Transport Management System For Gas — Project Hub

A gas transportation management application developed for PTG Logistic to address tracking delays and inefficiencies in delivery operations. Key features include driver, vehicle, and delivery location management, task assignment to drivers, real-time order and vehicle tracking, driver compensation calculation, customer billing, and transportation performance reporting.

## 🏗 System Overview

The system is composed of two primary components working together to deliver a complete transport tracking workflow.

---

### **1. Frontend Web Application (Next.js + Tailwind CSS)**

A modern interface for delivery staff.

#### **Features**

- Manage delivery staff, vehicles, drivers, and destination locations.
- Confirm driver and vehicle readiness for work.
- Upload order information.
- Track delivery vehicles and the status of each order.
- Monitor and identify delayed orders.
- Calculate and approve trip payments for drivers.
- Calculate transportation fees for customer billing.
- Generate monthly and yearly transportation summary reports.

**Repository:**  
👉 [github.com/nk-n/tmsg-frontend](https://github.com/nk-n/TMSG-frontend.git)

---

### **2. Frontend Web Application inside Line OA (Next.js + Tailwind CSS)**

A modern interface for driver.

#### **Features**

- 
**Repository:**  
  👉 [github.com/nk-n/tmsg-driver-frontend]()

  ***

### **3. Backend Services (Java Spring Framework, Spring JDBC)**

Implements all business logic, data operations, and integrations.

#### **Capabilities**

-

**Repository:**  
👉 [github.com/nk-n/tmsg-backend](https://github.com/nk-n/TMSG-backend.git)

---

## 🔧 Architecture Diagram (Simplified)

             ┌──────────────────────────────┐
             │         Web Frontend         │
             │     (Next.js + Tailwind)     │
             └───────────────▲──────────────┘
                             │ HTTPS (REST)
                             │ WebSockets
             ┌───────────────┴──────────────────────────┐
             │               Backend API                │
             │     (Java Spring Framework, Spring JDBC) │
             └───────────────▲──────────────────────────┘
                             │
                       Database Layer
                         (MariaDB)

---

## 📡 Technologies

### **Frontend**

- Next.js
- Tailwind CSS
- TypeScript

### **Backend**

- Java
- Spring Boot framework

### **Other**

- JWT-based authentication
- RBAC (Role-Based Access Control)
- MariaDB

---

## 👨‍🔬 Authors

- Rugsit Rungrattanachai
- Narakorn Thanapornpakdee
