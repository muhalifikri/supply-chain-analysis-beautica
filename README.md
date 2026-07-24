# 🛍️ Supply Chain Bottleneck Detection — Beautica Store

> *"Turning supply chain data into actionable business decisions."*

This end-to-end supply chain analytics project explores a real-world inspired dataset from **Beautica Store**, a fashion and beauty retailer. The analysis focuses on identifying operational bottlenecks across key areas of the supply chain, including **supplier performance, logistics, inventory management, product quality, and cost efficiency**.

By combining exploratory data analysis with business-focused insights, this project highlights opportunities to improve operational performance and translates the findings into practical, data-driven recommendations that support more efficient and profitable decision-making.


---

## 📁 Repository Outline

| File | Description |
|---|---|
| `supply_chain_data.csv` | Raw dataset (100 rows, 24 columns) |
| `supply_chain_analysis_porto.ipynb` | Main notebook — full analysis with narrative, code, and visualizations |
| `data_clean.csv` | Cleaned dataset used throughout the analysis |
| `dashboard_supply_chain.png` | Screenshot of the interactive Tableau dashboard |

---

## 🧩 Problem Background

**Beautica Store** is a beauty and cosmetics retailer based in Surabaya, Indonesia. While the business has continued to grow, it has also started to experience several operational challenges, including inconsistent supplier performance, fluctuating inventory levels, increasing operational costs, and product quality issues that impact overall efficiency.

To gain a clearer understanding of these challenges, the management initiated a comprehensive operational review of the company's supply chain. The objective of this project is to analyze supply chain performance, identify key bottlenecks, and provide data-driven recommendations that can improve efficiency, reduce operational risks, and support sustainable business growth.


This project is the result of that audit.

---

## 🎯 Project Goals

- Identify underperforming suppliers across defect rate, lead time, and cost
- Detect delivery delay patterns across carriers, routes, and transport modes
- Flag inventory risk — products at risk of stockout or overstock
- Quantify revenue loss from defective and uninspected products
- Find cost inefficiencies and where money is being spent without return
- Deliver prioritized, data-backed recommendations to management

---

## 📊 Project Output

| Output | Description |
|---|---|
| 📓 Jupyter Notebook | Full analysis across 6 sessions with narrative and visualizations |
| 📊 Tableau Dashboard | Interactive supply chain monitoring dashboard |
| 📑 Presentation | Slide deck summarizing findings for stakeholders |

**🔗 Live Dashboard:** `https://public.tableau.com/app/profile/muhammad.ali.fikri5379/viz/supply_chain_porto_aug_2026/Dashboard1?publish=yes`

---

## 🔍 Analysis Breakdown

| Session | Topic | Key Finding |
|---|---|---|
| 1 | Overview & EDA | 76% of products have unresolved inspection status |
| 2 | Supplier Performance | Only 1 out of 5 suppliers rated Good (Supplier 1, score 94.3) |
| 3 | Delivery Delay Patterns | Carrier A + Rail = worst combo at 7.43 days |
| 4 | Inventory & Stock Risk | Skincare: highest revenue ($241K) yet 15 products at stockout risk |
| 5 | Quality & Defect Impact | Estimated revenue loss from defects: ~$12,657 |
| 6 | Cost Inefficiency | Supplier 4 costs 44% more than the most efficient supplier yet delivers the lowest revenue |

---

## 💡 Key Recommendations

1. 🔴 **Audit Supplier 4** — highest cost, lowest revenue, 67% inspection fail rate
2. 🔴 **Enforce quality gate** — block Fail-status products from entering the sales pipeline
3. 🔴 **Recalibrate Skincare stock** — raise safety stock by 30%, implement dynamic reorder points
4. 🟡 **Reduce Cosmetics overstock** — halt reordering on slow-moving SKUs
5. 🟡 **Optimize logistics mix** — eliminate Carrier A + Rail, prioritize Carrier C + Road (3.71 days)
6. 🟢 **Cut manufacturing costs** — renegotiate with Supplier 4, benchmark against Supplier 3

---

## 📂 Data

**Dataset Source:**
[Supply Chain Dataset — Kaggle](https://www.kaggle.com/datasets/harshsingh2209/supply-chain-analysis)

**Dataset Identity:**

| Detail | Info |
|---|---|
| Domain | Fashion & Beauty / Makeup Products |
| Rows | 100 |
| Columns | 24 |
| Format | CSV |

**Features covered:**
Product Type, SKU, Price, Availability, Number of Products Sold, Revenue Generated, 
Customer Demographics, Stock Levels, Lead Times, Order Quantities, Shipping Times, 
Shipping Carriers, Shipping Costs, Supplier Name, Location, Lead Time, 
Production Volumes, Manufacturing Lead Time, Manufacturing Costs, 
Inspection Results, Defect Rates, Transportation Modes, Routes, Costs.

---

## 🛠️ Stacks

**Programming Language:**

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)

**Data Visualization:**

![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=for-the-badge&logo=python&logoColor=white)
![Seaborn](https://img.shields.io/badge/Seaborn-4C72B0?style=for-the-badge&logo=python&logoColor=white)
![Tableau](https://img.shields.io/badge/Tableau-E97627?style=for-the-badge&logo=tableau&logoColor=white)

**Environment:**

![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)

---

## 📌 Reference

- Dataset: [Supply Chain Dataset by Amir Motefaker — Kaggle](https://www.kaggle.com/datasets/amirmotefaker/supply-chain-dataset)

---

## 👤 Author

**Muhammad Ali Fikri**
Data Analyst | Surabaya, Indonesia

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/malifikri/)


---

*This project is part of a personal data analytics portfolio.*
