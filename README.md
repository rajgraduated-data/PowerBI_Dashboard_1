# 🛒 Amazon Sales Data Analysis & Dashboard

## 📌 Project Overview
This project features an interactive Power BI dashboard (`Amazon_Sales.pbix`) designed to analyze and visualize Amazon sales data. It tracks key business metrics such as Total Revenue, Profit margin, Top Performing Products, and Regional Sales distributions to help identify purchasing trends and drive business decisions.

## 📂 Files in this Repository
* **`Amazon_Sales.pbix`**: The complete Power BI interactive dashboard file.
* **`cleaned_dataset.xlsx`**: The underlying dataset used to build the visualizations.
* **`Amazon_dashboard.jpg`**: A snapshot preview of the Power BI dashboard.

## 🗄️ Dataset Description
The analysis is based on a cleaned dataset containing granular order details. 
Key columns in the dataset include:
* **Order Info:** `order_id`, `order_date`
* **Product Details:** `product_id`, `product_category`, `price`
* **Sales Metrics:** `quantity_sold`, `discount_percent`, `discounted_price`, `total_revenue`, `profit`
* **Customer Info:** `customer_region`, `payment_method`
* **Feedback:** `rating`, `review_count`

## 💡 Key Insights & Visualizations
The dashboard provides several key views and interactions:
1. **Revenue & Profit Tracking:** Overall performance metrics tracking Gross Revenue and Net Profit.
2. **Category Performance:** Breakdown of sales by `product_category` (e.g., Electronics, Fashion, Books, etc.).
3. **Regional Analysis:** Comparisons of `total_revenue` generated across different `customer_region`s (e.g., North America, Asia, Europe).
4. **Top Products:** A Top-N horizontal bar chart highlighting the most profitable/highest revenue-generating products.
5. **Trend Analysis:** Line charts mapping revenue and profit over time.

## 🛠️ Tools & Technologies Used
* **Data Visualization & Modeling:** Microsoft Power BI
* **Data Cleaning & Preparation:** Excel 
* **Data Format:** xlsx
