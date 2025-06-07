# 🛍️ Purchase Dashboard: Store Survey Analysis - Power BI/ SQL/ Python

This dashboard analyzes store survey data across multiple cities and store settings (Urban, Suburb, Rural) to track customer purchasing behavior, item preferences, exchange types, and store-wise sales performance.

![Sample_7_page-0001](https://github.com/user-attachments/assets/a44a1338-fb12-4746-8d15-7ff167e48c7f)

---

## 🔍 Purpose

This dashboard was developed to:
- Track total **purchase amount, quantity sold, and average spend** by location, product, and customer demographics
- Understand **purchase behavior across store settings** (Urban/Suburb/Rural)
- Identify **top-performing cities and product types**
- Evaluate **monthly purchase trends (MTD/YTD)** to aid in seasonal sales planning

---

## 🎯 Business Impact

- Delivered a **360° view of purchasing behavior** segmented by city, age group, and store setting
- Enabled decision-makers to identify **suburb stores** as the **highest contributors** to total revenue
- Uncovered valuable insights such as:
  - **Gadgets, Academic Books**, and **Outdoor Sports Kits** were top-selling categories
  - **Exchange transactions** drove a major chunk of revenue in cities like New York and Los Angeles
- Helped align **inventory strategy and promotion campaigns** by understanding month-wise demand trends

---

## 🛠️ How It Was Built

### 📊 Power BI
- Imported survey and purchase datasets using Excel/CSV connectors
- Designed drill-down visuals for:
  - Purchase trends by **city**, **store setting**, and **product type**
  - Amount split by **exchange type** (Cash vs Card vs Exchange)
  - MTD/YTD purchase performance
- Used DAX for calculating:
  - **Average purchase amount**
  - **Monthly purchase comparison**
  - **Quantity sold metrics**

### 🐍 Python (Used for Data Prep)
Python was used alongside Power BI for initial **data processing and enrichment**:
- Cleaned missing values, unified exchange codes, grouped age buckets
- Aggregated monthly data for MTD/YTD visualizations
- Enhanced categorical mapping for store settings and purchase types

## 📌 Key Insights
- Total Purchase Amount across 4 cities: $642K+, with Suburb stores contributing the most
- Highest Purchase Cities: New York ($167K), Los Angeles ($167K), Seattle (~$160K)
- Average Customer Age: 14.38 years
- Exchange-based purchases outpaced direct cash/card payments in several cities
- June and May recorded highest MTD purchase spikes – ideal for campaign planning
- Outdoor Sport Kits had highest sales in Rural/Suburb areas among 15–19 age group

## 🧰 Tools Used
- Power BI:	Visual dashboarding, interactivity, KPI cards
- Excel/CSV:	Raw data source format
- PostgreSQL: Data validation & extraction
- Python (pandas, matplotlib)	Preprocessing, age bucketing, grouping, monthly rollups

