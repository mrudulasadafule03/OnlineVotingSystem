# 🗳️ Online Voting System

An **Online Voting System** built with PHP, MySQL, HTML, and CSS. This system allows voters to register, log in, and cast their votes securely. It also provides a result dashboard for displaying election outcomes.

---

## 🚀 Features
- 🔐 **Secure Login** – Authentication for voters.
- 📝 **Voter Registration** – Register before voting.
- 🗳️ **Voting Panel** – Cast votes for candidates.
- 📊 **Result Dashboard** – Real-time results.
- 🖼️ **Candidate Images** – Party logos and voter card uploads.
- 🛡️ **Database Integration** – Stores voter and election data in MySQL.

---

## 🛠️ Technologies Used
- **Frontend:** HTML, CSS 
- **Backend:** PHP  
- **Database:** MySQL  
- **Server:** XAMPP (Apache + MySQL)  
- **Version Control:** Git & GitHub  

---

## 📂 Project Structure

```bash
online-voting-system/
├── index.html
├── api/
│   ├── connection.php
│   ├── login.php
│   ├── register.php
│   └── vote.php
├── css/
│   └── stylesheet.css
├── db_file/
│   └── online-voting-system.sql
├── routes/
│   ├── dashboard.php
│   ├── logout.php
│   └── register.html
├── uploads/
│   ├── BJP.png
│   ├── BSP.png
│   ├── Congress.png
│   ├── Manse.png
│   ├── MenLogo.png
│   ├── NCP.png
│   ├── ShivSena.png
│   ├── WomanLogo.png
│   └── voter-card.png
```


---

## ⚡ Installation & Setup

### 1️⃣ Install XAMPP
- Download and install **[XAMPP](https://www.apachefriends.org/download.html)**.  
- Start **Apache** and **MySQL** from the XAMPP Control Panel.  

### 2️⃣ Setup Project
1. Move the project folder `online-voting-system` into: C:/xampp/htdocs/

2. Open phpMyAdmin (http://localhost/phpmyadmin)  
   - Create a new database (e.g., `voting`).  
   - Import SQL file:
     
  ```
  db_file/online-voting-system.sql
  ```

3. Configure database credentials in `api/connection.php`:
```php
$servername = "localhost";
$username   = "root";
$password   = "";
$dbname     = "voting";
```

### 3️⃣ Run the Project

- Open browser and go to:

```
http://localhost/online-voting-system
```
