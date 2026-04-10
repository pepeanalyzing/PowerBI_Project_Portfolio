# 📊 Power BI Project Portfolio

A collection of end‑to‑end Power BI projects demonstrating my ability to clean data, build analytical data models, write DAX measures, and design clear, decision‑focused dashboards. Each project follows a full analytics workflow — from raw data to business insights.

---

## 🛒 Project: E‑Commerce Sales Analysis

### 🔍 Overview
An end‑to‑end sales analytics project built using data from an international online retailer. The goal was to transform raw transactional data into a structured model and deliver an interactive Power BI report that supports strategic decision‑making.

A secondary dataset was added to provide broader industry context and enrich insights.

---

## 🗂️ Dataset

**Source:** Azure SQL Database (`online_sales_retailer`)

**Tables used:**

| Table | Description |
|-------|-------------|
| **Sales** | Transaction-level data: invoice number, stock code, quantity, unit price, date |
| **Invoice** | Customer and country information per invoice |
| **Product** | Product categories and descriptions |

---

## 🧩 Tasks Completed

### 🔗 Data Connection
- Connected Power BI directly to an **Azure SQL Server** database.

### 🧹 Data Cleaning (Power Query)
- Standardised country names  
- Removed duplicates  
- Handled missing values  
- Ensured correct data types  

### 🏗️ Data Modelling
- Designed a **star schema**  
- **Fact table:** Sales  
- **Dimensions:** Invoice, Product  
- Relationships via `InvoiceNo` and `StockCode`  

### 🧮 DAX Calculations
- Calculated column:  
  - `Sales = Quantity * UnitPrice`
- Core measures:  
  - `Total Sales`, `Total Quantity`, `Average Unit Price`

### 🕒 Time Intelligence
- Built a **Date table**  
- Implemented:  
  - `TOTALYTD`  
  - `TOTALYTD_LastYear`  
  - Year‑on‑Year comparison measures  

### 📊 Data Visualisation
Developed visuals covering:
- Sales trends over time  
- Top product categories  
- Best‑selling products  
- Customer distribution by region  

### 📈 90‑Day Sales Forecast
- Generated a daily forecast using trend + seasonality patterns.

### 🎬 Report Storytelling
- Organised insights using **bookmarks**, **drill‑through**, and **slicers**  
- Enabled dynamic filtering by category, country, and date  

---

## 📦 Deliverables

- **Interactive Power BI dashboard (.pbix)**  
- **Ecommerce Sales report**  
---

## 🛠️ Tools & Skills

**Power BI · Power Query · DAX · Azure SQL · Data Modelling · Time Intelligence · Forecasting · Data Storytelling**

