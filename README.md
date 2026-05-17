# customer_shopping_behavior_analysis

<img width="1045" height="569" alt="image" src="https://github.com/user-attachments/assets/001d727f-29dc-42b2-a816-ab9ea188c0a8" />
customer-shopping-behavior-analysis/
│
├── data/
│   └── shopping_behavior.csv          # Raw dataset (3,900 rows, 18 features)
│
├── python/
│   └── eda_cleaning.py                # Data cleaning, feature engineering & DB load
│
├── sql/
│   ├── 01_revenue_by_gender.sql
│   ├── 02_high_spending_discount_users.sql
│   ├── 03_top5_products_by_rating.sql
│   ├── 04_shipping_type_comparison.sql
│   ├── 05_subscribers_vs_nonsubscribers.sql
│   ├── 06_discount_dependent_products.sql
│   ├── 07_customer_segmentation.sql
│   ├── 08_top3_products_per_category.sql
│   ├── 09_repeat_buyers_and_subscriptions.sql
│   └── 10_revenue_by_age_group.sql
│
├── dashboard/
│   └── customer_behavior_dashboard.pbix   # Power BI dashboard file
│
├── presentation/
│   └── Customer_Shopping_Behavior_Analysis.pptx
│
└── README.md
