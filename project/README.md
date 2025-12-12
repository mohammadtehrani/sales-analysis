
# 📊 Sales Analysis Project

This project provides a comprehensive analysis of sales data, customer behavior, product performance, and geographic distribution.  
The main goal is to support **data-driven business decisions** and optimize revenue.

---

## 🗂️ Project Structure
project/
├─ cleaned/
│ └─sales_clean.csv
├─ data/
│ └─ sales_data_sample.csv
├─ notebook/
│ └─ sales-analysis.ipynb
│ └─sales_data_sample.csv
├─ reports/
│ ├─ overview.md
│ └─ images/
│ ├─ monthly_sales.png
│ ├─ top_customers.png
│ ├─ top_products.png
│ ├─ top_countries.png
│ └─ price_distribution.png
└─ README.md

---

## 🛠️ Technologies & Tools
- Python 3.x
- Pandas
- Matplotlib & Seaborn
- Markdown

---

## 📈 Key Insights

### 🔹 Time Analysis
- **Peak sales:** 11-2004  
- **Highest monthly revenue:** $1,089,048.01  
- **Seasonal pattern:** Q4 usually has higher sales  

![Monthly Sales per Year](reports/images/monthly_sales.png)

### 🔹 Customer Analysis
- Top 3 loyal customers contributed ~17.62% of total revenue  
- Number of new customers per year: {2003: 69, 2004: 84, 2005: 40}  
- Top 5% of customers account for ~19.59% of total sales  

![Top Customers](reports/images/top_customers.png)

### 🔹 Product Analysis
- Most profitable product: S18_3232  
- Highest quantity sold: S18_3232  

![Top Products](reports/images/top_products.png)

### 🔹 Geographic Analysis
- Top country by sales: USA (~36.16% of total revenue)  
- Top 5 countries contribute ~70.41% of total sales  

![Top Countries](reports/images/top_countries.png)  
![Sales Share Pie](reports/images/country_pie.png)

### 🔹 Price Analysis
- Price distribution: mean $83.66, std $20.17, min $26.88, max $100.0  
- High-value orders (> $5,000): 0  

![Price Distribution](reports/images/price_distribution.png)

---

## 💡 Recommendations
- Focus marketing efforts on low-season months  
- Increase inventory for top-selling products  
- Launch loyalty programs for the top 5% of customers  
- Explore potential growth opportunities in new countries

---

## 📋 How to Run

1. Clone the repository:  
```bash
git clone https://github.com/mohammadtehrani/sales-analysis.git

2.Install dependencies:
pip install pandas matplotlib seaborn

3.Run the chart generation script:
python scripts/generate_charts.py

4.View the final report:
- Markdown overview: reports/overview.md
- Charts: reports/images/

🎯 Conclusion

This project provides a complete overview of sales, customers, products, and geographic distribution.
The analysis helps make informed business decisions and improve revenue optimization.
