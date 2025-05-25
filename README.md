# Blinkit Grocery Sales Analysis (Python)

## Description  
A Python-based analysis of Blinkit's grocery sales data to uncover trends, build predictive models, and provide actionable business recommendations. Uses libraries like `pandas`, `matplotlib`, `seaborn`, and `scikit-learn`.

## Key Features  
- **Exploratory Data Analysis (EDA)**: Sales trends, item weight impact, outlet size performance, and time-of-day patterns.  
- **Machine Learning Models**:  
  - **Linear Regression**: To analyze the impact of Item MRP on sales.  
  - **Random Forest Classifier**: To identify underperforming outlets.  
  - **Random Forest Regressor**: To prioritize low-visibility, high-potential items for promotions.  
- **Actionable Insights**: Price sensitivity, visibility optimization, and outlet upgrade strategies.  

## Data Highlights  
- **Total Transactions**: 8,523  
- **Top-Selling Item Type**: Fruits and Vegetables  
- **High-MRP Items**:  
  - Canned products (MRP up to ₹266.89)  
  - Dairy and Health & Hygiene categories  
- **Sales Performance**:  
  - Medium-sized outlets contribute the most to total sales.  
  - Tier 2 locations have the highest average sales.  
- **Model Results**:  
  - **Linear Regression**: MRP has a positive impact on sales (slope: ₹15.55 increase per unit MRP).  
  - **Random Forest Classifier**: 80.06% accuracy in identifying underperforming outlets.  
  - **Random Forest Regressor**: Moderate predictive power (R²: 0.2494) for visibility-driven sales.  

## Tools & Technologies  
- **Python Libraries**:  
  - `pandas` for data manipulation  
  - `matplotlib`, `seaborn`, `plotly` for visualization  
  - `scikit-learn` for machine learning models  
  - `numpy` for numerical operations  
- **Data Sources**: Blinkit grocery sales dataset (`BlinkITGrocery.csv`)  
