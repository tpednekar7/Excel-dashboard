# 📊 Sales Performance Dashboard — Excel Project

An interactive sales dashboard built in Microsoft Excel using Pivot Tables and Pivot Charts. The dashboard visualizes key business metrics across products, categories, cities, sales reps, and months — all connected through a dynamic slicer for real-time filtering.

---

## 📁 File Structure

The workbook contains two sheets:

| Sheet | Contents |
|-------|----------|
| `Data` | Raw sales data — one row per transaction |
| `Dashboard` | Interactive charts and slicer built from pivot tables |

---

## 🧾 Dataset Overview

| Column | Description |
|--------|-------------|
| `Date` | Date of the transaction |
| `Product` | Product name |
| `Category` | Product category |
| `Sales Rep` | Name of the sales representative |
| `City` | City where the sale occurred |
| `No. of Units` | Number of units sold |
| `Price` | Price per unit |
| `Amount` | Total sale amount (Units × Price) |
| `Month` | Month of the transaction |

---

## 📊 Dashboard Components

### Charts

| Chart | Type | Metric Shown |
|-------|------|--------------|
| City Wise Sales | Line Chart | Total sales amount per city |
| Sales by Sales Rep | Bar Chart | Revenue contribution per sales representative |
| Category Wise Sales | Pie Chart | Sales distribution across product categories |
| Product Wise Sales | Column Chart | Units or revenue broken down by product |
| Sales by Month | Column Chart | Monthly sales trend across the year |

### 🎛️ Interactive Slicer
- A **Month Slicer** is connected to all 5 charts via **Report Connections**
- Selecting any month instantly filters every chart on the dashboard simultaneously
- Allows quick comparison of performance across different time periods

---

## 🛠️ Tools & Features Used

- **Microsoft Excel**
- Pivot Tables
- Pivot Charts (Line, Bar, Pie, Column)
- Slicers with Report Connections
- Dashboard layout and design

---

## 💡 Key Skills Demonstrated

- Transforming raw transactional data into meaningful summaries using Pivot Tables
- Building a multi-chart interactive dashboard in Excel
- Connecting a single slicer to multiple charts using Report Connections for synchronized filtering
- Choosing the right chart type for each metric (trends, comparisons, distributions)
- Clean dashboard layout for business reporting

---

## 📂 Repository Structure

```
excel-sales-dashboard/
│
├── Sales_Dashboard.xlsx     # Excel workbook with Data sheet and Dashboard sheet
├── README.md                # Project documentation
```

---

## 🙋 About

This project was built to demonstrate proficiency in Excel-based data visualization and dashboard design — a core skill in data analyst and business analyst roles. The dashboard mimics the kind of sales reporting commonly used in real business environments.
