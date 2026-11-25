# Campus Complaint Management System

## 1. Project Overview

The **Campus Complaint Management System** is a Java-based application developed to make it easier for students to report and manage problems within a college campus.

In many colleges, students face issues related to classroom maintenance, network connectivity, and other campus facilities. Reporting these problems manually can take time and make it difficult to track whether they have been resolved.

This project provides a simple system where students can submit complaints, administrators can manage them, and staff members can work on resolving the reported issues.

The main aim is to reduce manual work, improve communication, and make complaint management more organized.

## 2. Objectives

- Provide an easy way for students to submit complaints.
- Allow administrators to view and manage complaints.
- Assign complaints to the appropriate staff members.
- Track the status of complaints.
- Maintain organized complaint records.
- Improve communication between students, staff, and administrators.

## 3. Technologies Used

| Technology | Purpose |
|---|---|
| Java | Main programming language |
| JDK | Compiling and executing Java programs |
| JVM | Running Java applications |
| ArrayList | Storing complaint records during execution |
| Scanner | Accepting user input |
| VS Code / IntelliJ IDEA | Writing and executing Java code |

## 4. Main Features

### Student Module
- Student registration and login.
- Submit new complaints.
- View submitted complaints.
- Check complaint status.

### Admin Module
- View all submitted complaints.
- Manage complaints.
- Assign complaints to staff members.
- Update complaint status.
- Monitor complaint resolution.

### Staff Module
- View assigned complaints.
- Work on assigned complaints.
- Update complaint progress.
- Provide resolution details.

## 5. Complaint Categories

The system supports different complaint types, including:

- Maintenance Complaints
- Network Complaints

These categories can be extended to include other campus-related issues.

## 6. Complaint Status

Each complaint follows a status-based workflow:

1. **Pending** – Complaint has been submitted.
2. **Assigned** – Complaint has been assigned to a staff member.
3. **In Progress** – Staff is working on the complaint.
4. **Resolved** – The reported problem has been solved.

## 7. Project Structure

The project contains the following Java classes:

```text
CampusComplaintManagementSystem/
│
├── Complaint.java
├── ComplaintOperations.java
├── MaintenanceComplaint.java
├── NetworkComplaint.java
│
├── User.java
├── Student.java
├── Admin.java
├── Staff.java
│
├── Management.java
├── ComplaintService.java
│
└── Main.java
```

### Description of Important Classes

| Class | Description |
|---|---|
| Complaint | Abstract class representing a complaint |
| ComplaintOperations | Handles complaint-related operations |
| MaintenanceComplaint | Represents maintenance-related complaints |
| NetworkComplaint | Represents network-related complaints |
| User | Base class for different users |
| Student | Handles student-related operations |
| Admin | Handles administrator operations |
| Staff | Represents staff members |
| Management | Manages complaint assignment and administration |
| ComplaintService | Provides complaint management services |
| Main | Entry point of the application |

## 8. How to Run the Project

Follow these steps to execute the application:

**Step 1:** Install Java JDK on your computer.

**Step 2:** Open VS Code, IntelliJ IDEA, or Eclipse.

**Step 3:** Create a Java project named:

`CampusComplaintManagementSystem`

**Step 4:** Create all the Java files mentioned in the project structure.

**Step 5:** Place all Java files in the same source folder and package.

**Step 6:** Add the respective Java code to each file.

**Step 7:** Open `Main.java`.

**Step 8:** Run the Main class to start the application.

## 9. Working Process

The application follows this basic workflow:

```text
        Start Application
               |
               v
          User Login
               |
        +------+------+
        |             |
        v             v
      Student        Admin
        |             |
        v             v
 Submit Complaint  View Complaints
        |             |
        v             v
 View Complaint   Assign to Staff
        |             |
        |             v
        |        Staff Works
        |             |
        |             v
        |       Update Status
        |             |
        +------<------+
               |
               v
       Complaint Resolved
               |
               v
          End Process
```

## 10. Storage Mechanism

The current version uses Java `ArrayList` collections to store complaint records during program execution.

No external database is required for the current prototype. Complaint records are maintained in memory and are not permanently saved after the application is closed.

## 11. Future Enhancements

The project can be improved in the future by adding:

- MySQL database integration for permanent data storage.
- A web-based user interface.
- Email or SMS notifications.
- Complaint search and filtering.
- Complaint priority management.
- Reports and analytics for administrators.
- Cloud-based deployment.

## 12. Expected Outcome

The Campus Complaint Management System aims to provide a simple and organized platform for handling campus complaints. It helps students report problems, allows administrators to assign complaints, and enables staff members to resolve them efficiently.

The system reduces manual work, improves complaint tracking, and supports better coordination within the college.

## 13. Project Team

| Roll Number | Student Name |
|---|---|
| 2520030560 | Muthana Nikhil Reddy |
| 2520030599 | Dumpala Hemasai |
| 2520030195 | Ada Rohan |

---

**Project Name:** Campus Complaint Management System

**Programming Language:** Java

**Project Type:** Console-Based Application

**Developed By:** Student Project Team
