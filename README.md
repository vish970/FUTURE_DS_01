 Task 1
#  Sales Data Analysis 

##  Objective

This project analyzes business sales data to uncover key insights related to:

* Revenue trends over time
* Top-performing products
* Category-wise profitability
* Regional sales performance

The goal is to support **data-driven business decision-making**.

---

##  Tools & Technologies Used

* Python
* Pandas
* Matplotlib & Seaborn

---

##  Dataset

The Superstore dataset includes:

* Sales & Profit data
* Product categories and sub-categories
* Customer regions
* Order dates

Dataset is included in this repository for reproducibility.

---

##  Key Performance Indicators (KPIs)

* **Total Sales:** Calculated from dataset
* **Total Profit:** Calculated from dataset
* **Profit Margin:** Profit / Sales

---

##  Analysis & Visualizations

### 🔹 1. Monthly Sales Trend

![Monthly Sales](images/monthly_sales.png)

**Insight:**
Sales show clear fluctuations across months, indicating seasonal demand patterns. Businesses can optimize inventory and marketing strategies during high-demand periods.

---

### 🔹 2. Top 10 Products by Sales

![Top Products](images/top_products.png)

**Insight:**
A small group of products contributes significantly to total revenue, suggesting a strong reliance on key products. These should be prioritized for promotions and stock availability.

---

### 🔹 3. Category Performance

![Category Performance](images/category_performance.png)

**Insight:**
While some categories generate high sales, their profit contribution is not proportional, indicating **low profit margins**. This suggests potential issues in pricing or cost management.

---

### 🔹 4. Regional Sales Analysis

![Regional Sales](images/region_sales.png)

**Insight:**
“The West region is the top-performing region in terms of sales, whereas the South region shows the lowest performance, indicating a need for targeted strategies to improve revenue in that area.”
---

##  Additional Insights

* A number of transactions result in **negative profit**, indicating discounting or high operational costs
* High sales do not always translate to high profitability
* Certain categories are more prone to losses than others

---

##  Business Recommendations

* Focus on **high-margin products and categories** to improve profitability
* Reduce excessive discounts on **loss-making products**
* Strengthen marketing strategies in **low-performing regions**
* Optimize pricing strategies to balance **sales volume and profit**

---

##  How to Run the Project

1. Clone the repository
2. Ensure dataset is inside the `data/` folder
3. Run the script:

```bash
python analysis.py
```

4. Visual outputs will be saved in the `images/` folder

---

##  Conclusion

This analysis highlights how data can be used to identify trends, optimize performance, and drive strategic decisions. By focusing on profitability and regional performance, businesses can significantly improve overall outcomes.

---
