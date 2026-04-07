# 🚀 SQL Basics to Advanced

Welcome to my SQL learning repository!
This repo contains solutions to SQL problems from basic to advanced levels, mainly inspired by platforms like LeetCode.

---

## 📌 About

This repository is a collection of SQL problems categorized by difficulty:

* 🟢 Easy
* 🟡 Medium
* 🔴 Hard (coming soon)

Each problem includes:

* ✅ Problem Number & Title
* ✅ Clean SQL Query
* ✅ Logical Approach (for selected problems)

---

## 📂 Folder Structure

```
SQL-Basics-to-Advanced/
│
├── Easy/
│   ├── 001. 1757. Recyclable and Low Fat Products.sql
│   ├── 002. 584. Find Customer Referee.sql
│   └── ...
│
├── Medium/
│   ├── 001. 570. Managers with at Least 5 Direct Reports.sql
│   └── ...
│
└── README.md
```

---

## 🧠 Topics Covered

* SELECT Queries
* WHERE Conditions
* GROUP BY & HAVING
* JOINs (INNER, LEFT)
* Subqueries
* Aggregate Functions (COUNT, AVG, SUM)
* CASE Statements
* Date & Time Functions
* Advanced SQL Patterns

---

## 🎯 Goal

The goal of this repository is to:

* Strengthen SQL fundamentals
* Practice real interview questions
* Build consistency in problem-solving
* Prepare for technical interviews

---

## ⚡ Sample Problem

**570. Managers with at Least 5 Direct Reports**

```sql
SELECT name
FROM Employee
WHERE id IN (
    SELECT managerId
    FROM Employee
    GROUP BY managerId
    HAVING COUNT(*) >= 5
);
```

---

## 🛠️ Tech Used

* SQL (MySQL)
* LeetCode Problems

---

## 📈 Progress

* ✅ Easy Problems: In Progress
* ✅ Medium Problems: In Progress
* ⏳ Hard Problems: Coming Soon

---

## 🤝 Contribution

This is a personal learning repository, but suggestions are always welcome!

---

## ⭐ Support

If you find this repo helpful:

* ⭐ Star the repository
* 🍴 Fork it
* 📢 Share with others

---

## 👩‍💻 Author

**Nithyasri**
🚀 Java Backend Developer | SQL Enthusiast

---

## 📬 Connect with Me

* GitHub: https://github.com/nithyasrimurugesan15

---

✨ *Consistent practice is the key to mastering SQL!*
