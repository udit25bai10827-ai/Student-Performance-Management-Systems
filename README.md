# **Student Performance Management System**

## **1. Project Overview**

The **Student Performance Management System** is a **console-based Java application** designed to manage student information, academic marks, attendance, and performance reports.

The system allows users to **add, view, search, update, and delete student records**. It also provides **marks management, attendance tracking, individual performance reports, and a class performance dashboard**.

The application stores student data in a **local text file**, allowing information to remain available even after restarting the program.

---

## **2. Features**

### **Student Management**

* **Add Student**
* **View All Students**
* **Search Student by Roll Number**
* **Update Student Information**
* **Delete Student**
* **Prevent Duplicate Roll Numbers**

### **Marks Management**

* **Enter Marks** for Java, Mathematics, and English
* **Calculate Total Marks**
* **Calculate Average Marks**
* **Calculate Grade**
* **Validate Marks** between 0 and 100

### **Attendance Management**

* **Record Total Classes**
* **Record Attended Classes**
* **Calculate Attendance Percentage**
* **Determine Attendance Eligibility**
* **Validate Attendance Values**

### **Reports and Dashboard**

* **Generate Individual Student Performance Report**
* **Generate Class Performance Dashboard**
* **Display Class Average**
* **Identify Highest-Performing Student**
* **Display Attendance Statistics**
* **Display Performance Categories**

### **Data Management**

* **Save Student Information** to a local file
* **Load Saved Information** when the program starts
* **Handle Invalid Input** without crashing

---

## **3. Technologies Used**

The project is developed using the following technologies and concepts:

* **Java**
* **Object-Oriented Programming (OOP)**
* **Java Collections Framework**
* **ArrayList**
* **File Handling**
* **Exception Handling**
* **Visual Studio Code**
* **Git**
* **GitHub**

---

## **4. Project Structure**

```text
StudentPerformanceManagementSystem/
│
├── Main.java
├── Student.java
├── StudentManager.java
├── MarksManager.java
├── AttendanceManager.java
├── FileManager.java
├── InputValidator.java
├── ReportManager.java
├── DashboardManager.java
├── students.txt
├── .gitignore
│
└── tests/
    └── TestCases.md
```

### **File Description**

| File                       | Description                                 |
| -------------------------- | ------------------------------------------- |
| **Main.java**              | Controls the main application and menu      |
| **Student.java**           | Represents student information              |
| **StudentManager.java**    | Handles student CRUD operations             |
| **MarksManager.java**      | Manages marks and grade calculations        |
| **AttendanceManager.java** | Handles attendance records and calculations |
| **FileManager.java**       | Handles saving and loading student data     |
| **InputValidator.java**    | Validates user input                        |
| **ReportManager.java**     | Generates individual performance reports    |
| **DashboardManager.java**  | Generates class performance statistics      |
| **students.txt**           | Stores student records                      |
| **TestCases.md**           | Contains project test cases                 |

---

## **5. Requirements**

To run this project, you need:

* **Java Development Kit (JDK)**
* **Terminal / Command Prompt**
* **Git** *(optional, for cloning the repository)*

The project uses **standard Java features** and does not require any external libraries.

---

## **6. How to Run**

### **Step 1: Open the Project Folder**

Open a **terminal or command prompt** inside the project folder.

### **Step 2: Compile the Java Files**

Run the following command:

```bash
javac Main.java Student.java StudentManager.java MarksManager.java AttendanceManager.java FileManager.java InputValidator.java ReportManager.java DashboardManager.java
```

### **Step 3: Run the Application**

Run:

```bash
java Main
```

### **Step 4: Use the Menu**

The application provides the following options:

```text
1. Add Student
2. View Students
3. Search Student
4. Update Student
5. Delete Student
6. Add Marks
7. View Performance
8. Record Attendance
9. View Attendance
10. Generate Performance Report
11. Class Performance Dashboard
12. Exit
```

---

## **7. Data Storage**

Student information is stored in the following file:

```text
students.txt
```

The file stores:

* **Student Information**
* **Marks**
* **Attendance Data**

The application automatically **loads previously saved records when it starts** and saves updated information to the file.

This provides **basic data persistence** without requiring a database.

---

## **8. Testing**

Test cases are documented in:

```text
tests/TestCases.md
```

Testing covers the following functionality:

* **Student Creation**
* **Duplicate Roll Number Validation**
* **Student Search**
* **Student Update**
* **Student Delete**
* **Marks Validation**
* **Attendance Validation**
* **Performance Calculations**
* **Report Generation**
* **Class Dashboard**
* **Data Persistence**
* **Invalid Input Handling**

---

## **9. Error Handling**

The application uses **input validation and exception handling** to prevent invalid data and application crashes.

The system handles cases such as:

* **Non-numeric values** where numbers are required
* **Marks outside the range 0–100**
* **Negative attendance values**
* **Attendance greater than total classes**
* **Empty student names**
* **Duplicate roll numbers**
* **Invalid menu choices**

---

## **10. Future Enhancements**

The following features can be added in future versions:

* **Graphical User Interface (GUI)**
* **Database Integration**
* **Login and Authentication**
* **Additional Subjects**
* **PDF Report Export**
* **Monthly Attendance Tracking**
* **Advanced Performance Analytics**
* **Student Performance Graphs**
* **Role-Based Access for Students and Faculty**

---

## **11. Author**

**Developed as an academic Java project.**

**Student Performance Management System**

---

## **12. License**

This project is developed for **educational and academic purposes**.
