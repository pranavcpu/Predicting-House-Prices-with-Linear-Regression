House Price Prediction Using Machine Learning

1) Project Overview

This project predicts residential house prices using Machine Learning techniques based on various property characteristics such as area, number of bedrooms, bathrooms, stories, parking availability, air conditioning, and preferred location.
The project demonstrates the complete Machine Learning workflow including data preprocessing, exploratory data analysis, feature engineering, feature selection, model building, and performance evaluation.

2) Objective

To build a predictive model capable of estimating house prices accurately using historical housing data and identifying the most influential factors affecting property prices.

3) Dataset Information

The dataset contains information about residential properties and their selling prices.

Features Used
Area
Bedrooms
Bathrooms
Stories
Main Road Access
Guest Room
Basement
Hot Water Heating
Air Conditioning
Parking
Preferred Area
Furnishing Status
Target Variable
Price

🛠️ Technologies Used
Python
Pandas
NumPy
Matplotlib
Seaborn
Scikit-Learn
Statsmodels
Jupyter Notebook

🔄 Project Workflow
1. Data Understanding
Loaded and explored housing dataset
Checked dataset dimensions and feature information
Generated descriptive statistics
2. Data Cleaning
Verified missing values
Confirmed dataset quality
3. Outlier Detection & Treatment
Outliers were identified using boxplots and treated using the Interquartile Range (IQR) method for:
 Price
 Area
4. Exploratory Data Analysis (EDA)
Performed:

Pair Plot Analysis
Correlation Analysis
Feature Distribution Visualization
Categorical Feature vs Price Analysis

5. Feature Engineering

 Converted categorical variables into numerical values:
  Feature	Encoding
   Yes	1
   No	0
 Created dummy variables for:
  Furnishing Status

6. Feature Selection

Applied Recursive Feature Elimination (RFE) to identify the most important predictors.

Selected Features
Area
Bathrooms
Stories
Air Conditioning
Parking
Preferred Area

7. Model Building
Implemented:
Linear Regression
Model training performed using Scikit-Learn and Statsmodels.

8. Model Evaluation
Performance evaluated using:
  R² Score

📈 Results
Final Model Performance
Metric	Value
R² Score	0.579

Key Findings
Property area has a strong impact on house prices.
Houses with air conditioning tend to have higher values.
Parking availability contributes positively to pricing.
Preferred locations command premium prices.
Number of bathrooms and stories significantly influence house value.

📷 Visualizations
Exploratory Analysis
Boxplots for Outlier Detection
Pairplots
Feature-wise Price Comparisons
Distribution Plots
Model Analysis
Residual Distribution Plot
Actual vs Predicted Analysis


🚀 Installation
Clone the repository:

git clone https://github.com/pranavcpu/House-Price-Prediction.git

Install required libraries:

pip install -r requirements.txt

Run Jupyter Notebook:

jupyter notebook

Open:

Housing.ipynb
📂 Repository Structure
House-Price-Prediction/
│
├── Housing.ipynb
├── README.md
├── requirements.txt
├── screenshots/
├── dataset/
└── model/
💼 Business Applications
Real Estate Valuation
Property Investment Analysis
Housing Market Research
Automated Price Estimation Systems
Real Estate Decision Support

🔮 Future Improvements
Random Forest Regression
XGBoost Regression
Hyperparameter Tuning
Streamlit Web Application Deployment
Real-Time Property Price Prediction

👨‍💻 Author
Pranav
Electronics & Telecommunication Engineering Student
Savitribai Phule Pune University (SPPU)

Skills Demonstrated
Data Analysis
Data Cleaning
Exploratory Data Analysis
Feature Engineering
Machine Learning
Regression Modeling
Statistical Analysis
Data Visualization

⭐ If you found this project useful, please consider starring the repository.
