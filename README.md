# 📊 PowerBI Sales Dashboard — Interactive Analytics Project

An end-to-end **interactive Power BI dashboard** designed to analyze sales performance using **KPI tracking, advanced DAX calculations, and storytelling-driven insights**.
This project demonstrates strong capabilities in **data visualization, business intelligence, and analytical thinking**.

---

## 👨‍💻 Author

**Saurabh Kumar Pandey**
📌 Aspiring Data Analyst | Power BI Enthusiast

🔗 **LinkedIn:** *www.linkedin.com/in/saurabh-kumar-pandey-it-fintech*
📧 **Email:** *saurabhpandeyk01@gmail.com*

🚀 **Open to:** Internship | Full-time Opportunities in Data Analytics / BI

---

## 🎯 Project Objectives

* Analyze **sales trends over time**
* Track **profitability and business growth**
* Identify **top-performing products & categories**
* Compare **regional performance**
* Enable **interactive decision-making** with filters

---

## 📊 Dashboard Features

### 🔹 KPI Cards

* 💰 Total Sales
* 📈 Total Profit
* 📦 Total Orders
* 📊 Profit Margin %
* 🚀 YoY Growth %

---

### 🔹 Visualizations

* 📅 Monthly Sales Trend
* 🛍️ Sales by Category
* 🏆 Top 5 Products
* 🌍 Sales by Region
* 📉 Profit by Region

---

### 🔹 Interactive Elements

* 📆 Year slicer (2014–2017)
* 🌍 Region filtering
* 💡 Smart tooltips with performance insights
* 🔍 Drill-through analysis by region

---

## 🧠 Key Business Insights

* 📈 **2017 recorded the highest growth** (+20.4% YoY)
* 💹 Profit margins improved significantly (up to **15.6%**)
* 🖥️ **Technology & Furniture** are top revenue drivers
* 🌎 Regional variation reveals **optimization opportunities**

---

## 🛠️ Tools & Technologies

* Power BI Desktop
* DAX (Data Analysis Expressions)
* Data Modeling
* Data Visualization Best Practices

---

## 📌 DAX Highlights

Some of the key calculations used:

```DAX
-- Total Sales
Total Sales = SUM(Sales_Data[Sales])

-- Total Profit
Total Profit = SUM(Sales_Data[Profit])

-- Profit Margin %
Profit Margin % = DIVIDE([Total Profit], [Total Sales], 0)

-- YoY Growth %
YoY Growth % =
DIVIDE(
    [Total Sales] - CALCULATE([Total Sales], SAMEPERIODLASTYEAR(Date_Table_[Date])),
    CALCULATE([Total Sales], SAMEPERIODLASTYEAR(Date_Table[Date])),
    0
)
```

---

## 📂 Project Structure

```
📁 PowerBI-Sales-Dashboard
│── 📄 README.md
│── 📊 Dashboard.pbix
│── 📁 images
│   ├── dashboard_2017.png
│   ├── dashboard_2015.png
│   ├── tooltip_preview.png
│   ├── east_2017.png
│   └── central_2015.png
```

---

## 🖼️ Dashboard Preview

### 🔹 Main Dashboard — 2017

![Main Dashboard](images/dashboard_2017.png)

---

### 🔹 Year-over-Year Decline — 2015

![2015 Dashboard](images/dashboard_2015.png)

---

### 🔹 Custom Tooltip ⭐

![Tooltip](images/tooltip_preview.png)

---

### 🔹 Regional Drill-through — East

![East](images/east_2017.png)

---

### 🔹 Regional Drill-through — Central

![Central](images/central_2015.png)

---

## 🚀 How to Use

1. Download the `.pbix` file
2. Open in **Power BI Desktop**
3. Use slicers to explore:

   * Year-wise performance
   * Region-wise insights
4. Hover on visuals to view **interactive tooltips**

---

## 💡 What I Learned

* Creating **dynamic KPIs using DAX**
* Implementing **time intelligence (YoY growth)**
* Designing **storytelling dashboards**
* Enhancing UX using **tooltips & drill-through**
* Structuring dashboards for **business decision-making**

---

## 📬 Let's Connect

If you found this project useful or have feedback:

👉 Connect with me on LinkedIn
👉 Open to collaboration, internships, and job opportunities

---

⭐ **If you like this project, consider giving it a star!**
