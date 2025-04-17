🎓 Student Management System (Java + MySQL)

A beginner-friendly Core Java console application to manage student records using MySQL as the backend database.

## 🛠️ Features
- ✅ Add a student (Name, Age, Department)
- 📋 View all students
- ❌ Delete a student by ID
- 🚪 Exit the program

## 📚 Technologies Used
- **Java** (Core Java)
- **MySQL** (via XAMPP phpMyAdmin)
- **JDBC** (Java Database Connectivity)
- **NetBeans IDE**
- **MySQL Connector/J** (JAR)

## 🗃️ Database Details

**Database Name:** `student_db`  
**Table Name:** `students`

```sql
CREATE TABLE students (
    id INT AUTO_INCREMENT PRIMARY KEY,
    name VARCHAR(100),
    age INT,
    department VARCHAR(100)
);

How to Run
🧰 Open XAMPP → Start Apache and MySQL

💻 Go to http://localhost/phpmyadmin → Create student_db and the students table

🧑‍💻 Open project in NetBeans

✅ Add MySQL Connector/JAR to project libraries

🟢 Run the StudentManagementSystem.java file (Shift + F6)

 Example Usage

--- Student Management System ---
1. Add Student
2. View Students
3. Delete Student
4. Exit
Enter choice:

Created By
Robayet Sabab


