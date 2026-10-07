# Emergency-Management-
# Accidental Emergency Information System (AEIS)

An AWS cloud-based emergency response platform engineered to store, manage, and rapidly retrieve critical patient health and contact details during vehicular or medical incidents.

---

## 📌 Project Overview
In critical emergencies, first responders often encounter unidentified patients without medical history or next-of-kin contacts. **AEIS** enables rapid retrieval of vital data (blood group, emergency contact numbers, family physician info) at the incident scene via QR code scanning, while alerting nearby hospitals to optimize turnaround time.

---

## 🏗️ Architecture & Tech Stack

| Layer | Technologies |
| :--- | :--- |
| **Frontend** | Angular, HTML5, CSS3, JavaScript |
| **Backend & Compute** | AWS Lambda (Serverless REST handlers) |
| **Database** | Amazon DynamoDB (NoSQL fast key-value storage) |
| **Storage & Hosting** | Amazon S3 (Static assets & QR generation storage) |

---

## ⚙️ Core Modules & Workflows

1. **User Profile & Health Locker:**
   - Captures primary demographic and medical information: Blood group, Aadhaar verification, emergency contact, and primary care doctor.
   - Generates a unique, authenticated QR identifier.
2. **Hospital Reception Portal:**
   - Scans and loads incoming trauma profiles.
   - Sends incident alerts and updates resource readiness.
3. **Admin Dashboard:**
   - Manages role authorization (Admin, User, Hospital) and audit logs.

---

## 📊 System Design Diagrams
- **DFD Level-0 & Level-1:** Outlines emergency reporting and user-record interactions across roles.
- **UML & ER Diagrams:** Demonstrates NoSQL entities (`User`, `Admin`, `Form`) and action sequences (`FillForm()`, `ScanQR()`, `SubmitForm()`).

*(Screenshots and architecture diagrams can be placed under the `/docs` or `/assets` folder)*

---

## 👥 Contributors
- **Khushi Gupta** 
- **Om Gautam** 
- **Vaishnavi Patil** 
- *Guided by:* **Ms. Hetal Thaker** (DY Patil International University, Pune)
