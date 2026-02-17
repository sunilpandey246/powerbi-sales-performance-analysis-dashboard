# 📊 Power BI Data Model – Sales & Returns Analysis  

This project contains a well-structured **Power BI Data Model** designed to analyze Sales and Returns data using a **Star Schema approach**.

---

## 🔹 Data Model Overview  

The model consists of two fact tables and multiple dimension (lookup) tables connected through primary and foreign key relationships.

---

## 🔸 Fact Tables  

### 1️⃣ Sales Data  

| Column Name     | Description |
|----------------|------------|
| CustomerKey    | Unique customer identifier |
| OrderDate      | Date of order |
| OrderNumber    | Unique order number |
| OrderQuantity  | Quantity ordered |
| ProductKey     | Unique product identifier |
| TerritoryKey   | Region identifier |
| StockDate      | Stock availability date |

### 2️⃣ Returns Data  

| Column Name     | Description |
|----------------|------------|
| ProductKey     | Unique product identifier |
| ReturnDate     | Date of return |
| ReturnQuantity | Quantity returned |
| TerritoryKey   | Region identifier |

These tables store transactional data used for sales and return analysis.

---

## 🔸 Dimension (Lookup) Tables  

- **Customer Lookup** – Customer details (Income, Education, etc.)  
- **Product Lookup** – Product information (Name, Color, Cost, Price, etc.)  
- **Product Subcategories Lookup**  
- **Product Categories Lookup**  
- **Calendar Lookup** – Date, Month, Month Name  
- **Territory Lookup** – Country, Region, Continent  

---

## 🔹 Relationships & Schema  

- Implemented **One-to-Many (1:*) relationships** between dimension tables and fact tables.  
- Followed a **Star Schema design** for better performance and scalability.  
- Proper key mapping ensures accurate filtering and aggregation across reports.  

---

## 🔹 Key Analysis Capabilities  

Using this data model, we can analyze:

- 📌 Sales by Region  
- 📌 Sales by Product Category & Subcategory  
- 📌 Customer Segmentation  
- 📌 Monthly & Yearly Sales Trends  
- 📌 Return Quantity Analysis  
- 📌 Product Performance  

---

## 🎯 Objective  

The goal of this project is to build a clean and optimized data model that supports efficient reporting and interactive dashboard creation in Power BI.

---

## 🛠 Tools Used  

- Power BI Desktop  
- Data Modeling (Star Schema)  
- Relationship Management  
- DAX (for calculations and measures)  




