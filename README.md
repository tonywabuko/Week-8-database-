# Clinic Booking System – MySQL Database

## 📌 Project Overview

This project is a relational database design and implementation for a Clinic Booking System using MySQL. It simulates a real-world clinic management scenario, allowing storage and organization of information about patients, doctors, appointments, departments, and medical records.

---

## 🧱 Database Features

- **Well-structured relational schema**
- Proper constraints: `PRIMARY KEY`, `FOREIGN KEY`, `NOT NULL`, `UNIQUE`
- Relationship types used:
  - One-to-Many (Doctor to Appointments, Patient to Appointments)
  - One-to-Many (Department to Doctors)
  - One-to-Many (Patient to Medical Records)

---

## 🗃️ Entity Descriptions

1. **Departments**
   - Stores department names (e.g., Cardiology, Pediatrics).
   - Each department can have many doctors.

2. **Doctors**
   - Contains information about each doctor.
   - Each doctor belongs to one department.

3. **Patients**
   - Holds patient details such as name, contact info, and birthdate.

4. **Appointments**
   - Links patients and doctors with appointment dates and reasons.
   - A patient can have multiple appointments with different doctors.

5. **Medical Records**
   - Stores diagnosis and treatment history for patients.
   - One patient can have multiple medical records.

---

6. ## 🛠️ Setup Instructions

1. **Clone this repository** or download the `.sql` file.
2. Open MySQL Workbench or any MySQL client.
3. Run the script file
 

