# Relational Database Design

> Learning resources for **Relational Database Design** for Grade XII students.

This repository contains learning materials, examples, SQL scripts, and database design resources to help students understand how relational databases are designed and implemented.

The materials guide students from the fundamentals of databases and SQL to designing relational databases using **Entity-Relationship Diagrams (ERD)**, relationships, normalization, implementation, security, optimization, and the use of **Generative AI** as a learning and development tool.

## 📚 Learning Path

The materials are organized into chapters that progressively introduce relational database concepts.

| Chapter            | Topic                                           | What You'll Learn                                                       |
| ------------------ | ----------------------------------------------- | ----------------------------------------------------------------------- |
| [01](./chapter_01) | **Introduction to Databases and SQL**           | Database fundamentals, RDBMS, tables, SQL, and basic queries            |
| [02](./chapter_02) | **Related Tables and More SQL**                 | Working with multiple related tables and more advanced SQL concepts     |
| **03**             | **Database Design Theory**                      | Theoretical concepts related to relational database design              |
| [04](./chapter_04) | **Entities and Attributes**                     | Identifying entities and attributes and representing them in an ERD     |
| [05](./chapter_05) | **Relationships**                               | Understanding relationships between entities and cardinality            |
| [06](./chapter_06) | **Normalization and Implementation**            | Normalizing database structures and implementing the design             |
| [07](./chapter_07) | **Security and Optimization**                   | Basic database security and performance considerations                  |
| [08](./chapter_08) | **Database Design in the Age of Generative AI** | Exploring how Generative AI can support database design and development |

> **Note:** Chapter 3 focuses on theoretical concepts, so it does not contain code or practical files. Therefore, there is no Chapter 3 folder in this repository.

## 🎯 Learning Goals

After working through these resources, students should be able to:

* Explain the basic concepts of relational databases.
* Understand tables, records, attributes, and keys.
* Write basic SQL queries.
* Understand relationships between tables.
* Identify entities and their attributes from a real-world problem.
* Design an **Entity-Relationship Diagram (ERD)**.
* Determine appropriate relationships and cardinalities.
* Apply normalization to improve database design.
* Translate a database design into an actual database.
* Understand basic database security and optimization.
* Use database design tools such as **dbdiagram.io** and **MySQL Workbench**.
* Use Generative AI responsibly to support learning and database design.

## 🛠️ Tools

You may encounter or use the following tools throughout the materials:

* **SQL** — Query and manipulate relational databases.
* **SQLite** — Lightweight relational database.
* **MySQL** — Popular open-source relational database management system.
* **PostgreSQL** — Open-source object-relational database system.
* **SQL Server** — Microsoft's relational database system.
* **Oracle Database** — Enterprise relational database system.
* **dbdiagram.io** — Create ER diagrams using a simple database definition language.
* **MySQL Workbench** — Design and manage MySQL databases.
* **Generative AI** — Used as a learning and problem-solving assistant.

## 🗂️ Repository Structure

```text
.
├── chapter_01/
├── chapter_02/
├── chapter_04/
├── chapter_05/
├── chapter_06/
├── chapter_07/
└── chapter_08/
```

Chapter 3 is intentionally not included as a folder because its content is **theory-focused** and does not require code or practical files.

## 🚀 How to Use This Repository

### 1. Start with the chapters

Read the chapters in order. Each chapter contains explanations and supporting resources related to the topic.

### 2. Practice with the SQL files

Several chapters include prepared SQL scripts for different relational database systems.

Choose the script that matches the database system you are using.

### 3. Practice database modeling

For the ERD chapters, you can use the provided database definition files with tools such as:

* [dbdiagram.io](https://dbdiagram.io/)
* MySQL Workbench

Try to understand the design before simply importing the provided diagram.

### 4. Modify and experiment

Don't just copy the examples.

Try changing the database design, adding new entities, attributes, or relationships, and observe how those changes affect the database.

> **The goal is not to memorize database diagrams. The goal is to learn how to design one.**

## 🧠 Learning Approach

When working through a database design problem, try following this process:

```text
Real-world problem
        ↓
Identify entities
        ↓
Identify attributes
        ↓
Identify primary keys
        ↓
Identify relationships
        ↓
Determine cardinality
        ↓
Create ERD
        ↓
Normalize the design
        ↓
Implement the database
        ↓
Write SQL queries
        ↓
Test and improve
```

## 🤖 Using Generative AI

Generative AI can be useful when learning database design, but it should be used as a **learning assistant**, not as a replacement for understanding.

You can use AI to:

* Ask for explanations of database concepts.
* Generate practice problems.
* Discuss possible entities and relationships.
* Review an ERD design.
* Explain SQL errors.
* Generate sample data.
* Compare alternative database designs.
* Help you understand unfamiliar SQL syntax.

However, always **check, understand, and test** AI-generated answers before using them.

> **Don't ask AI to design your database for you. Ask AI to help you learn how to design it.**

## 📖 Recommended Workflow for Students

For each database design problem:

1. **Understand the problem**. Identify what the system needs to store and manage.
2. **Identify entities**. Find the important objects or concepts in the problem.
3. **Identify attributes**. Determine what information needs to be stored about each entity.
4. **Determine keys**. Identify primary keys and, where necessary, foreign keys.
5. **Determine relationships**. Ask how the entities are connected.
6. **Determine cardinality**. Decide whether relationships are one-to-one, one-to-many, or many-to-many.
7. **Create the ERD**. Represent the database structure visually.
8. **Normalize the database**. Check for unnecessary duplication and other design problems.
9. **Implement the database**. Convert the design into tables using SQL.
10. **Test the database**. Insert sample data and run queries to verify that the design works as intended.

## 👩‍💻 For Students

Don't be afraid to make mistakes.

Database design is easier to understand when you **draw it, break it, fix it, and try again**.

When you encounter a problem, ask yourself:

> **"What does the real-world system actually need?"**

A good database design starts with understanding the problem—not with writing SQL.

---

## 📌 About

This repository is created as a learning resource for **Relational Database Design** for Grade XII students.

It is intended to support classroom learning, independent study, exercises, and practical database design activities.

Made with ☕ and a lot of `SELECT * FROM curiosity;`.
