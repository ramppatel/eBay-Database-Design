# 🛒 eBay Database Management System

This project presents a robust and scalable database solution for an E-commerce platform, developed using **PostgreSQL**. It is designed to efficiently manage core operations including user information, product listings, inventory control, order tracking, and transaction management.

---

## 🎯 Project Objectives

The primary goal of this system is to simplify data operations and enhance consistency, reliability, and performance. The system architecture supports:

- **User Information Management**: Handling profiles of buyers and sellers.
- **Product Listings**: Detailed catalog of items including categories, prices, and seller details.
- **Inventory Management**: Real-time tracking of product availability and stock levels.
- **Order Tracking**: Monitoring the complete lifecycle of orders from placement to delivery.
- **Transaction Handling**: Capturing secure and traceable financial transactions with unique IDs.

---

## 🧱 Key Components

| Component | Description |
|----------|-------------|
| 📦 **Database** | PostgreSQL |
| 🧩 **ER Model** | Visual representation of the database structure and relationships |
| 🔗 **Relational Schema** | Detailed schema derived from the ER model |
| 🔍 **Functional Dependencies** | Defined attribute relationships for integrity checks |
| 📐 **Normalization** | Normalized up to **BCNF** to ensure minimal redundancy and high consistency |
| 🧾 **DDL Scripts** | SQL scripts for table creation and relationship definitions |
| ✍️ **DML Scripts** | Sample data insertion scripts for testing and demonstration |
| 🧪 **Sample Queries** | Frequently used SQL queries for reporting and analytics |

---

## 🧪 Features & Capabilities

- Normalized schema (up to BCNF) ensures data integrity and eliminates anomalies.
- Supports multiple product categories, multiple sellers, and multi-item orders.
- Provides relational integrity using foreign keys and constraints.
- Modular and extensible design for future features.

---

## 📂 What's Inside the Repository

| File Name | Description |
|-----------|-------------|
| `DDL_Script.sql` | SQL DDL commands to create tables, constraints, and relationships. |
| `Dummy_Data_Insertion_Script.sql` | Populates tables with test data (users, products, orders, etc.). |
| `Sample_SQL_Queries.sql` | Example queries for joins, aggregations, and analytics. |
| `eBay_Database_ER_Diagram.pdf` | Entity-Relationship diagram showing logical relationships. |
| `eBay_Database_Relational_Schema.pdf` | Relational schema detailing tables, keys, and attributes. |
| `eBay_Database_FDs_and_Normalization.pdf` | Functional dependencies and normalization explanation (up to BCNF). |
| `Minimal_FD_Set.pdf` | Contains the minimal cover set of functional dependencies. |
| `README.md` | Project documentation and overview (this file). |

---

## 🚀 Future Enhancements

We plan to further develop this system with:

- 🎨 **Custom data views** for different user roles (admin, seller, buyer) for secure and role-specific access.
- 🌐 **Web interface** built with a modern frontend framework (e.g., React.js or Next.js) for better interactivity.
- 📈 **Advanced analytics** using SQL views, CTEs, or BI tools to monitor sales and user behavior.
- 🔒 **Authentication layer** for secure access to database interfaces or dashboards.

---

## 📫 Connect with Me

- GitHub: [@ramppatel](https://github.com/ramppatel)
- Email: ram8881patel@gmail.com

---

> 💡 Explore the repo to dive deeper into how an E-commerce platform's backend is structured from the ground up using core database concepts.
