# Amazon E-commerce 1M Analytics
A data science project for exploratory analysis and visualization of a 1M-row e-commerce transactions dataset.

## Overview
This project analyzes customer orders, pricing, discounts, ratings, returns, and delivery outcomes to uncover business and operational insights.

## Objectives
- Profile dataset quality and structure
- Analyze pricing, discount, and order-value behavior
- Understand return-rate drivers
- Compare performance across categories, locations, devices, and payment methods
- Build notebook-friendly visual analytics

## Dataset
- File: `amazon_ecommerce_1M.csv`
- Rows: 1,000,000
- Columns: 20
- Key fields include:
  - User/Product: `user_id`, `product_id`
  - Product info: `category`, `subcategory`, `brand`
  - Commerce metrics: `price`, `discount`, `final_price`
  - Quality and sentiment: `rating`, `review_count`
  - Fulfillment: `shipping_time_days`, `delivery_status`
  - Channel and geography: `device`, `payment_method`, `location`
  - Target outcome: `is_returned`

## Tech Stack
- Python 3.10+
- Pandas, NumPy
- Matplotlib, Seaborn, Plotly
- Jupyter Notebook

## Quick Start
1. Clone the repository:
   - `git clone <your-repo-url>`
2. Create and activate a virtual environment
3. Install dependencies:
   - `pip install pandas numpy matplotlib seaborn plotly scipy statsmodels jupyter`
4. Place dataset in your project (recommended path: `data/amazon_ecommerce_1M.csv`)
5. Open notebooks:
   - `jupyter notebook`

## Suggested Project Structure
```text
.
├── data/
│   └── amazon_ecommerce_1M.csv
├── notebooks/
│   └── ecommerce_analysis.ipynb
├── src/
│   └── utils.py
├── outputs/
│   ├── figures/
│   └── reports/
└── README.md
```

## Analysis Scope
- Data quality checks (missing values, duplicates, type validation)
- Descriptive statistics and distribution analysis
- Category/subcategory revenue and return analysis
- Location/device/payment segmentation
- Time-series trends by month
- Correlation and relationship exploration
- Interactive visuals for stakeholder reporting

## Sample Insights (from baseline analysis)
- Electronics contributes the largest share of revenue
- Overall return rate is ~11.6%
- Shipping time shows a measurable relationship with returns
- Return behavior varies by location more than by device/payment method

## Dataset Link: https://www.kaggle.com/datasets/sharmajicoder/amazon-e-commerce/data
