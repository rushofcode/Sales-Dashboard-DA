# 📊 Task 8 – Sales Dashboard Design (Power BI / Tableau)

This repository contains the complete solution for **Task 8: Simple Sales Dashboard Design**, built using the **Superstore Sales dataset** (`train.csv`). The dashboard visualizes key sales trends, category/region performance, and customer insights using interactive charts and filters.

---

## ✅ **Project Objective**
Create an interactive sales dashboard that reflects:
- Monthly sales trends  
- Region-wise performance  
- Category-level contribution  
- Filters to drill into specific data segments  
- Clear business insights based on the data  

This dashboard helps decision-makers quickly understand performance across time, geography, and product categories.

---

## 🗂️ **Contents of This Repository**
| File | Description |
|------|-------------|
| `Task8_Sales_Dashboard.pbix` | Power BI dashboard file |
| `train.csv` | Raw dataset used for analysis |
| `insights.txt` | 3–4 written insights extracted from the dashboard |
| `README.md` | Documentation (this file) |

---

## 🛠️ **Tools & Technologies**
- **Power BI Desktop** (primary)
- Alternatively: Tableau Public / Tableau Desktop
- Git & GitHub for version control

---

## ✅ **Steps Followed**
### **1. Data Loading & Cleaning**
- Loaded dataset into Power BI  
- Converted `Order Date` & `Ship Date` into proper Date types  
- Verified columns such as Sales, Quantity, Profit  
- Removed null/invalid rows  
- Created new columns:
  - `MonthYear` (MMM YYYY format)

### **2. DAX Measures**
Created key measures:
- **Total Sales**

### **3. Visualizations Built**
✅ Line Chart – *Sales Trend by Month*  
✅ Bar Chart – *Sales by Region*  
✅ Donut Chart – *Sales by Category*  
✅ KPIs – Total Sales, Total Profit  
✅ Slicer – Region (multi-select) , Category (milti-select) 

All visuals interact dynamically for filtering and drill-down.

---

## 📌 **Generated Insights (Based on Actual Dataset)**
(Full details provided in `insights.txt`)

1. **Top Sales Region: West**  
   - The West region contributes the highest sales volume across all regions.

2. **Top Performing Category: Office Supplies**  
   - Office Supplies is the most frequently purchased category (1,492 transactions), followed by Technology.

3. **Most Profitable Sub-Category: Phones & Chairs**  
   - These sub-categories show consistently higher sales amounts and strong margins.

4. **High-Value Products Exist (₹22,638 max sale)**  
   - A few large transactions significantly skew revenue distribution, indicating enterprise-level customers.

---

## 🚀 How to Reproduce
1. Download Power BI Desktop  
2. Clone this repository:  
   ```bash
   git clone https://github.com/<your-username>/<repo-name>.git

## Author

Name: Rushikesh Vishnu Palekar
