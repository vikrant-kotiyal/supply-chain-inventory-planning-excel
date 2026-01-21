# supply-chain-inventory-planning-excel
Inventory planning &amp; demand analysis case study using Excel

# Supply Chain Inventory Planning – Excel Case Study

## 📌 Project Overview
This project is a **mock supply chain inventory planning case study** built using Microsoft Excel.  
The objective is to analyze sales trends, evaluate inventory positions, and recommend **optimal purchase order (PO) quantities** while considering lead time, shortages, MOQ, and working capital impact.

The case study simulates a real-world **inventory planner / supply chain analyst** scenario commonly faced in e-commerce and retail businesses.

---

## 🎯 Business Objective
- Ensure **stock availability** during vendor lead time
- Identify **inventory shortages and excess**
- Recommend **Suggested PO quantities** based on demand and constraints
- Improve **working capital efficiency**
- Support data-driven **purchase planning decisions**

---

## 📊 Data Description
The dataset includes:
- SKU / Product ID
- Vendor
- Historical sales
- Lead time (days)
- Current inventory
- MOQ (Minimum Order Quantity)
- Demand metrics

> ⚠️ Note: All data used in this project is **mock / anonymized** and created for learning and portfolio purposes only.

---

## 🧮 Key Calculations & Logic

### 1️⃣ Lead Time Demand
Calculated to estimate demand during vendor replenishment period.

**Formula:**

---

### 2️⃣ Inventory Shortage
Identifies SKUs where current stock is insufficient to meet lead time demand.

**Logic:**

(If value > 0 → shortage exists)

---

### 3️⃣ Suggested PO Quantity
Recommended purchase quantity considering:
- Lead time demand
- Existing shortage
- MOQ constraints

**Logic used:**
- PO quantity ≥ shortage
- Rounded up to the nearest MOQ multiple

This ensures both **operational feasibility** and **vendor compliance**.

---

### 4️⃣ Days of Clearance (DOC)
Measures how long current inventory will last.

**Formula:**

Helps identify:
- Overstocked SKUs
- Slow-moving inventory
- Working capital blockage

---
### 5️⃣ Forecast Accuracy (MAPE)
Used to evaluate demand forecast accuracy.

**Formula:**

Lower MAPE indicates better forecast reliability.

---

## 📈 Key Insights Generated
- Identified SKUs at **risk of stockout** during lead time
- Highlighted **excess inventory** causing higher DOC
- Optimized PO quantities to balance:
  - Service level
  - Inventory holding cost
  - Vendor MOQ constraints
- Provided actionable inputs for **purchase & replenishment planning**

---

## 🛠 Tools Used
- **Microsoft Excel**
  - Pivot Tables
  - Lookup formulas
  - Conditional logic
  - Inventory metrics & KPIs

---

## 👤 About Me
I am a **Data Analyst / Market Research Analyst** with 3 years of experience, having strong skills in:
- Advanced Excel
- Power BI
- MySQL
- Data Modeling & Analysis
- Supply Chain & Market Research Analytics

This project reflects my ability to apply **analytical thinking to real business problems**.

---

## 🔗 How This Project Can Be Used
- Portfolio demonstration for:
  - Supply Chain Executive
  - Inventory Planner
  - Operations Analyst
  - Data Analyst roles
- Interview discussion & case walkthrough
- Practical example of Excel-based analytics

---

✅ **Feel free to explore, download, and review the model.**





