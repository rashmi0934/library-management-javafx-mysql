# 📚 Library Management System (JavaFX + MySQL)

A desktop-based Library Management System built using JavaFX and MySQL that allows users to perform CRUD operations on book records.

---

## 🚀 Features

- Add new books to the database
- Update existing book details
- Delete books
- Search books by title
- Sort books alphabetically
- View all books in a TableView

---

## 🛠️ Tech Stack

- Java (JDK 21)
- JavaFX
- MySQL
- JDBC

---

## 🗄️ Database Schema

**Table: Books**

| Column     | Type        |
|------------|------------|
| book_id    | INT (PK)   |
| title      | VARCHAR    |
| author     | VARCHAR    |
| available  | BOOLEAN    |

---

## ⚙️ Setup Instructions

1. Clone the repository:
   ```bash
   git clone https://github.com/YOUR_USERNAME/library-management-javafx-mysql.git
   ```

2. Create MySQL database:
   ```sql
   CREATE DATABASE LibraryDB;
   USE LibraryDB;

   CREATE TABLE Books (
       book_id INT AUTO_INCREMENT PRIMARY KEY,
       title VARCHAR(255),
       author VARCHAR(255),
       available BOOLEAN
   );
   ```

3. Update database credentials in `LibraryUI.java`

4. Run the application

---

## 📸 Screenshots
<img width="1198" height="936" alt="image" src="https://github.com/user-attachments/assets/3fc375fc-11af-4c22-a429-bf362877bf43" />


---

## 📌 Future Improvements

- User authentication system
- Borrow/return book feature
- Pagination
- UI enhancements
