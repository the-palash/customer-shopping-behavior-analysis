# Customer Shopping Behaviour Analysis

This project presents a comprehensive analysis of customer shopping behavior using transactional data from 3,900 purchases across various product categories[cite: 1]. The goal is to uncover insights into spending patterns, customer segments, product preferences, and subscription behaviors to guide strategic business decisions[cite: 1].

---

## 📌 Project Overview
- **Dataset Size:** 3,900 rows × 18 columns[cite: 1]
- **Key Focus Areas:** Demographics, Purchase Details, Discount Impact, Product Ratings, and Subscription Status[cite: 1].
- **Tech Stack Used:** Python (Pandas, Data Cleaning), SQL/MySQL/PostgreSQL, Power BI, Excel[cite: 1].

---

## 📂 Key Features & Workflow

### 1. Data Cleaning & Exploratory Data Analysis (EDA) - Python
- Imputed missing values in `review_rating` using the median rating of each product category[cite: 1].
- Standardized column names to `snake_case`[cite: 1].
- **Feature Engineering:**
  - Created `age_group` binning[cite: 1].
  - Created `purchase_frequency_days`[cite: 1].
- Dropped redundant column `promo_code_used` after verification with `discount_applied`[cite: 1].
- Integrated and exported cleaned data directly into PostgreSQL/MySQL for further querying[cite: 1].

### 2. Business Insights & SQL Analysis
Performed key SQL queries to answer critical business metrics[cite: 1]:
- **Revenue by Gender:** Analyzed total revenue contributions[cite: 1].
- **High-Spending Discount Users:** Identified customers using discounts while spending above average[cite: 1].
- **Top Rated Products:** Ranked products based on average review ratings (e.g., Gloves, Sandals, Boots)[cite: 1].
- **Shipping & Subscription Impact:** Evaluated spend differences between Express vs. Standard shipping and Subscribers vs. Non-Subscribers[cite: 1].
- **Customer Segmentation:** Classified users into **Loyal**, **Returning**, and **New** categories[cite: 1].
- **Category Rankings:** Analyzed Top 3 products within each category[cite: 1].

### 3. Interactive Power BI Dashboard
Built an end-to-end interactive **Customer Behavior Dashboard** incorporating slicers for Gender, Subscription Status, Category, and Shipping Type, alongside metrics like:
- Total Customers & Average Purchase Amount[cite: 1]
- Average Review Rating[cite: 1]
- Revenue & Sales breakdown by Category and Age Group[cite: 1]

---

## 📈 Key Recommendations
1. **Boost Subscriptions:** Promote exclusive benefits to convert non-subscribers[cite: 1].
2. **Customer Loyalty Programs:** Reward repeat buyers to transition them into the Loyal segment[cite: 1].
3. **Discount Policy Optimization:** Balance promotional sales boosts with profit margin control[cite: 1].
4. **Targeted Marketing:** Focus campaigns on high-revenue age groups and high-performing categories[cite: 1].

---

## 🔗 References & Acknowledgments
- **Project Reference:** Inspired by and based on the Data Analysis project tutorials by **Anmol Mohanty** (YouTube).
