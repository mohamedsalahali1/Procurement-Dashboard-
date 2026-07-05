# 📊 Procurement Analytics Dashboard | Power BI

An end-to-end **Procurement Analytics Dashboard** built with **Power BI** to help procurement managers and business stakeholders monitor spending, supplier performance, procurement compliance, contract lifecycle, and operational efficiency through interactive dashboards and advanced analytics.

---

# 🚀 Project Overview

Procurement departments manage millions of dollars in purchasing activities every year. Without a centralized analytics solution, it becomes difficult to answer critical business questions such as:

- How much are we spending?
- Are we achieving enough procurement savings?
- Which suppliers perform the best?
- Are contracts about to expire?
- How much procurement happens outside approved contracts?
- Is the invoice validation process compliant?
- Which departments introduce the highest procurement risks?

To address these challenges, I developed an interactive **Procurement Analytics Dashboard** using **Power BI** that transforms raw procurement data into actionable business insights.

---

# 📁 Dataset

The dataset contains procurement transactions from **2022–2024** and includes information about:

- Purchase Orders
- Suppliers
- Contracts
- Departments
- Categories
- Delivery Performance
- ESG Scores
- Procurement Savings
- Invoice Matching
- Payment Status
- Multiple Currencies (USD, EUR, GBP, AUD, JPY)

---

# 🏗️ Data Modeling

<img width="1135" height="797" alt="Star Schema" src="https://github.com/user-attachments/assets/d2f94740-efa2-454e-b61e-b8584b02dbf1" />

The raw Excel dataset was initially provided as a **Flat Table**.

To improve performance and scalability, it was transformed into a **Star Schema** consisting of:

- Fact_Procurement
- Dim_Calendar
- Dim_Supplier
- Dim_Contract
- Dim_Department
- Dim_Item

Relationships were optimized to ensure fast filtering, efficient calculations, and accurate KPI reporting.

---

# 🧮 DAX Measures

More than **30+ DAX Measures** were created to calculate financial, operational, supplier, and compliance KPIs, including:

- Total Spend
- Total Savings
- Savings %
- Spend YoY
- Savings YoY
- Maverick Spend %
- Preferred Supplier Spend %
- Single Source Spend %
- Low Risk Supplier Spend %
- Weighted Average ESG Score
- On-Time Delivery %
- Average Lead Time
- Remaining Contract Days
- Contracts Expiring in 90 Days
- 3-Way Match %
- Overdue Invoice %
- Dynamic Currency Conversion
- Dynamic KPI Selection (Field Parameters)

---

# 📊 Dashboard Pages

## 1️⃣ Executive Overview


<img width="1561" height="940" alt="p1" src="https://github.com/user-attachments/assets/a6684caf-333e-46ab-ad32-232913d67eec" />



Provides a high-level overview of procurement performance.

### Key KPIs

- Total Spend
- Total Savings
- Savings Percentage
- Maverick Spend
- On-Time Delivery

### Visuals

- Spend Trend by Quarter
- Spend by Category
- Spend by Supplier Region
- Purchase Order Type Distribution

---

## 2️⃣ Supplier Performance


<img width="1555" height="935" alt="p2" src="https://github.com/user-attachments/assets/49dad935-80d6-4cf8-91cf-c3deb5262983" />



Evaluates supplier efficiency, procurement risks, and supplier quality.

### Key KPIs

- Preferred Supplier Spend
- Single Source Spend
- Low Risk Supplier Spend
- Weighted ESG Score
- Average Lead Time

### Visuals

- Supplier Lead Time Analysis
- Supplier Performance Scatter Chart
- Supplier Risk Analysis
- Supplier Distribution
- Contract Monitoring Table

---

## 3️⃣ Procurement Controls & Compliance


<img width="1556" height="933" alt="p3" src="https://github.com/user-attachments/assets/81cb0668-84a0-4e40-9fc2-dd311689b004" />



Focuses on governance, compliance, and procurement risks.

### Key KPIs

- Maverick Spend
- Contracts Expiring Soon
- 3-Way Match
- Overdue Invoice %
- Average Days Late

### Visuals

- Invoice Match Distribution
- Purchase Order Status
- Maverick Spend by Department
- Procurement Matrix
- Operational Performance Analysis

---

# 💡 Business Insights

The dashboard enables organizations to answer important procurement questions such as:

- Which categories receive the highest procurement spend?
- Which suppliers deliver the best performance?
- Which suppliers create operational risks?
- Which contracts are close to expiration?
- How much spending occurs outside approved contracts?
- Which departments generate the highest Maverick Spend?
- How healthy is the invoice validation process?
- How much value has procurement negotiations generated?

---

# ⚡ Interactive Features

The dashboard includes several interactive Power BI features:

- Dynamic Currency Slicer
- Year Filter
- Dynamic KPI Selection using Field Parameters
- Conditional Formatting
- Dynamic KPI Descriptions
- Dynamic Titles
- Bookmarks
- Drill-down Capabilities
- Interactive Tooltips
- Responsive Navigation Buttons

---

# 📈 Business Impact

This dashboard helps procurement teams:

- Monitor procurement spending
- Identify supplier risks
- Improve supplier selection
- Reduce Maverick Spending
- Track contract expiration
- Improve invoice compliance
- Monitor operational efficiency
- Support data-driven procurement decisions

---

# 🛠️ Technologies Used

- Power BI
- Power Query
- DAX
- Data Modeling
- Star Schema
- Field Parameters
- Bookmarks
- Conditional Formatting
- Interactive Visualizations



---

# 🎯 Key Skills Demonstrated

- Business Intelligence
- Procurement Analytics
- Data Modeling
- Advanced DAX
- KPI Design
- Interactive Dashboard Development
- Business Storytelling
- Performance Optimization
- Data Visualization

---

# 📬 Contact

If you have any feedback, suggestions, or opportunities, feel free to connect with me on **LinkedIn**.

linkedin.com/in/mohamed-salah-92073428b

⭐ If you found this project useful, consider giving the repository a star!
