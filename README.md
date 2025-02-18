# Databases Project

## 📌 Project Overview

This repository contains **database projects**, including both **SQL and NoSQL-based (MongoDB and Cassandra) solutions**  focusing on **data architecture, relational modeling, and SQL-based operations**. Each project includes documentation, relational models, and SQL scripts for database creation and data manipulation.

## 🚀 Getting Started

### 📋 Prerequisites

Ensure you have the following installed:

- SQL database system (MySQL, PostgreSQL, or similar)
- MongoDB and Cassandra
- A text editor (VS Code, Sublime, etc.)
- [Draw.io](https://app.diagrams.net/) (optional, for relational models)

### 🔧 Installation

Clone the repository:

```sh
git clone https://github.com/your_username/Databases-main.git
cd Databases-main
```

## 🏗 Project Structure

```
Databases-main/
│── Proyecto 1 Arquitectura de Datos/
│   ├── P1.pdf                      # Project 1 documentation
│── Proyecto 1 FyBBDD/
│   ├── FSDB_Memoria1.docx          # Project memory
│   ├── Grafo Relacional.drawio     # Relational model
│   ├── NEWcreation.sql.docx        # Database creation script
│   ├── NEWload.sql.docx            # Data loading script
│── Proyecto 2 Arquitectura de Datos/
│   ├── Documentación.docx          # Project 2 report
│   ├── P2.drawio                   # Relational model diagram
│   ├── README.txt                   # Instructions
│── Proyecto 2 FyBBDD/
│   ├── 100432028_100432200_100432070_LW2.docx # Authors and project notes
│── Proyecto 3 FyBBDD/
│   ├── 2022-23-Enunciado práctica 3.pdf  # Project 3 description
│   ├── Memoria_práctica3.docx            # Project memory
│   ├── createBD_2023.sql                 # Database creation script
│   ├── insert2023 - errors_fixed.sql     # Fixed data insertion script
│   ├── script_statistics_2023.sql        # SQL script for statistics
```

## 🎯 Usage

### Running SQL Scripts

To execute the database creation script:

```sh
mysql -u root -p < Proyecto3_FyBBDD/createBD_2023.sql
```

To insert data:

```sh
mysql -u root -p < Proyecto3_FyBBDD/insert2023 - errors_fixed.sql
```

To generate statistics:

```sh
mysql -u root -p < Proyecto3_FyBBDD/script_statistics_2023.sql
```

## ✅ Testing

You can validate the database structure by executing:

```sh
SHOW TABLES;
```

Or by running test queries on sample data provided in the project.

## 🛠 Built With

- **MySQL/PostgreSQL** - Relational database system
- **SQL** - Data querying and management
- **Draw\.io** - Used for entity-relationship modeling

## 🤝 Contributing

If you wish to contribute, feel free to fork the repository, make improvements, and submit a pull request.

---
