
# Employee Management System

The **Employee Management System** is a desktop-based application built using **Java Swing** and **MySQL**.  
It helps organizations manage employee records efficiently, including adding, updating, viewing, and deleting employee details.

---

## 🚀 Features
- 🔑 Login & Authentication  
- ➕ Add New Employee Records  
- 📋 View Employee Details  
- ✏️ Update Employee Information  
- ❌ Remove Employee Records  
- 🏠 User-friendly GUI built with **Java Swing**  

---

## 🛠️ Tech Stack
- **Programming Language:** Java (JDK 8 or later)  
- **GUI Framework:** Java Swing  
- **Database:** MySQL  
- **IDE Used:** NetBeans / Eclipse  

---

## 📂 Project Structure
```

Employee-Management-System/
│── src/employee/management/system/
│   ├── Login.java
│   ├── Home.java
│   ├── AddEmployee.java
│   ├── ViewEmployee.java
│   ├── UpdateEmployee.java
│   ├── RemoveEmployee.java
│   ├── Splash.java
│   └── Conn.java
│── src/icons/   (All image resources)
│── build.xml
│── manifest.mf
│── nbproject/   (NetBeans project files)

````

---

## ⚙️ Installation & Setup
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/Employee-Management-System.git
````

2. Import the project into **NetBeans** or **Eclipse**.

3. Setup the **MySQL Database**:

   * Create a database (e.g., `employeemanagement`).
   * Import the SQL script if provided, or manually create employee table:

     ```sql
     CREATE TABLE employee (
         id INT PRIMARY KEY AUTO_INCREMENT,
         name VARCHAR(100),
         age INT,
         department VARCHAR(50),
         salary DECIMAL(10,2)
     );
     ```

4. Update the database credentials in `Conn.java`:

   ```java
   Connection c = DriverManager.getConnection("jdbc:mysql://localhost:3306/employeemanagement", "root", "yourpassword");
   ```

5. Run the project from `Login.java` or `Splash.java`.

---

## 🎯 Usage

* Login with admin credentials.
* Add new employees with their details.
* View, update, or delete employee records.
* Manage employee data with an easy-to-use interface.

---

## 📸 Screenshots

*(Add screenshots of Login, Home, Add Employee, etc. here)*

---

## 🤝 Contribution

Contributions are welcome!
If you’d like to improve this project, feel free to fork the repo and submit a pull request.

---

## 📜 License

This project is licensed under the **MIT License** - you are free to use, modify, and distribute it.

---

## 👨‍💻 Author

Developed by **Srihari**

```

---

Would you like me to also create **README.md files** for the other projects you uploaded earlier (ATM, Hotel Management, Chatting Application) so that all of them are GitHub-ready in one go?
```
