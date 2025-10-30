# 🧩 Machine Learning-Driven Product Distribution and Regional Demand Forecasting

### 💡 *Turning regional sales data into business growth through machine learning and analytics.*

---

## 🔍 Overview

This project focuses on analyzing **regional product demand patterns** across India using **data analytics and machine learning techniques**.  
The insights help businesses make informed decisions in **inventory and distribution planning**.

- Identifies **state-wise product preferences** using clustering analysis.  
- Optimizes **product distribution and inventory** based on demand.  
- Reduces **unsold stock and operational waste** through targeted strategies.  
- Enhances **sales performance and customer satisfaction** with data-driven insights.  

---

## 🎯 Objective

This project analyzes product sales data across Indian states to uncover **regional demand patterns** and optimize **product distribution**.  
By applying clustering and visualization techniques, it helps businesses:

- Identify which products sell best in each region  
- Optimize product distribution according to local demand  
- Reduce unsold stock and wastage  
- Boost customer satisfaction through data-driven insights  

---

## 🧩 Tech Stack

**Python:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn  
**Tools:** Excel, Power BI  
**Techniques:** Clustering, EDA, Pareto Analysis, Data Cleaning  

---

## 🐍 Part 1: Python-Based Analysis

### 1. Data Preparation
- Imported and cleaned a raw dataset containing **state, district, category, and product-level details**.  
- Handled **missing values**, removed duplicates, and normalized data using **Pandas** and **NumPy**.  
- Verified data completeness using `.isnull()` and `.describe()` for summary statistics.  

---

### 2. Exploratory Data Analysis (EDA)
- Analyzed **product diversity** across 30 Indian states using grouping and summary statistics.  
- Conducted **Pareto Analysis (80/20 Rule)** → 20% of products (Tea, Wheat, Cookies, Milk, Chicken) contributed to ~80% of total market presence.  
- Visualized **top states and districts** by product count and diversity using **Matplotlib** and **Seaborn**.  

---

### 3. Clustering Analysis (Machine Learning)
- Created a **State vs Category matrix** and standardized it using `StandardScaler`.  
- Applied **K-Means Clustering (k=4)** to group states with similar buying patterns.  
- Profiled each cluster as:  
  - **Cluster 0:** Fruits-Focused States  
  - **Cluster 1:** Dairy-Centric States  
  - **Cluster 2:** Vegetable-Heavy / Highly-Diverse States  
  - **Cluster 3:** Bakery-Dominant States  

---

### 4. Insights from Python Analysis
- Buying habits vary widely — **a single strategy doesn’t fit all regions**.  
- **Gujarat, Maharashtra, Punjab** → prefer *Fruits & Vegetables*  
- **Kerala, Tamil Nadu, Karnataka** → prefer *Dairy & Meat*  
- **Andhra Pradesh, Bihar, Assam** → show *balanced demand*  
- **Haryana, Rajasthan, Delhi** → focus on *Grocery & Vegetables*  

📄 **Python Notebook (PDF Report):** [View Full Analysis Here](https://github.com/niravtrivedi23/Market-Product-Demand-Analysis/blob/main/Product%20Based%20Advance%20Analysis.pdf)

---

## 📊 Part 2: Power BI Dashboard Analysis

### Dashboard Overview
An interactive **Power BI Dashboard** titled *“Product Distribution & Regional Performance”* was developed for visual storytelling and regional insights.  

🖼️ **Dashboard Preview:**  
![Product Based Dashboard](https://github.com/niravtrivedi23/Market-Product-Demand-Analysis/blob/main/Product%20Based%20Dashboard.png)  

📂 **Download Power BI File (.pbix):** [Click Here](https://github.com/niravtrivedi23/Market-Product-Demand-Analysis/blob/main/Dairy%20and%20Other%20Product%20Analysis%20Project%20Dashboard.pbix)  

---

### Key Dashboard Highlights
- **States Covered:** 30 | **Cities Reached:** 129 | **Unique Products:** 303 | **Categories:** 8  
- **Top Sub-Categories:** Milk, Household Items, Baked Products  
- **Top States:** Uttar Pradesh, West Bengal, Telangana  
- **Top Districts:** East Khasi Hills, South West Delhi  
- **Growth Trends:** Category-wise increase and decline visualized clearly  
- **Regional Insights:** Milk and Household Items lead across most zones  

---

### Interactive Features
- Dynamic filters for **State** and **Category**  
- Category-wise tracking with **bar, donut, and line charts**  
- **Growth indicators** for demand shifts  
- **Clean, minimalist theme** with focused insight boxes  

---

## ✅ Conclusion

- **Regional Demand Patterns:** Clustering revealed four major state groups with unique product preferences (Fruits, Dairy, Vegetables, Bakery).  
- **Best-Selling Products:** Each region has dominant categories — e.g., Gujarat & Punjab prefer Fruits/Vegetables, while Kerala & Tamil Nadu favor Dairy/Meat.  
- **Optimized Distribution:** Region-wise insights enable targeted stocking, reducing over-supply and improving efficiency.  
- **Reduced Waste:** Data-driven allocation minimized unsold inventory by focusing on high-demand products.  
- **Customer Satisfaction:** Personalized product availability by region improved trust and purchase experience.  

---

## 🌟 Final Conclusion – See the Power of Data in Distribution

Through this project and dashboard, you can clearly see how **data analytics and machine learning** can transform the way businesses plan and distribute their products across regions.  

By analyzing **state-wise demand patterns**, applying **clustering algorithms**, and building **interactive dashboards**, this project demonstrates how data can guide smarter stocking decisions, reduce waste, and improve sales efficiency.  

💡 This project isn’t just about numbers — it’s about helping businesses **understand their customers**, create **region-specific product strategies**, and grow using **data-driven insights**.  

By combining:  
- **Python** for advanced analytics and clustering  
- **Excel** for data preparation  
- **Power BI** for visual storytelling  

I developed a complete solution that helps companies **predict demand**, **plan inventory smartly**, and **deliver the right product to the right place at the right time** — showing how **data can drive real business success**.  

---

## 💼 Developed By

**Nirav Trivedi**  
📍 Surat, India  
📧 **niravtrivedi069@gmail.com**  
🔗 [LinkedIn](https://www.linkedin.com/in/trivedi-nirav-a1760424b) | [GitHub](https://github.com/niravtrivedi23)  

---

## 💭 Final Thought

*"Data is not just numbers — it’s the voice of your customers. Listen to it, and your business will never lose direction."*
