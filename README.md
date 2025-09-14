# Car Data Analysis Assessment

## 📖 Overview
This project analyzes a multi-sheet car dataset to extract actionable insights and build predictive models.  
It covers price prediction, success classification, car segmentation, sales forecasting, and the relationship between advertising and sales.

## 📊 Dataset
The dataset consists of three sheets:
- **Car_Assignment1**: Car specifications with price and success indicators  
- **Car_Assignment2**: Time-series sales data across brands  
- **Car_Assignment3**: Monthly sales data with price and advertising spend  

## 🛠️ Techniques Used
- **Exploratory Data Analysis (EDA)**
- **Regression** (Linear Regression for price prediction)  
- **Classification** (Logistic Regression, Random Forest, SVM for model success)  
- **Clustering** (K-Means with Elbow method)  
- **Forecasting** (Facebook Prophet for sales prediction)  
- **Correlation & Regression** (Price vs. Ad Spend impact on sales)

## 🚀 Key Insights
- Price prediction with linear regression achieved baseline R² of 0.13  
- Random Forest outperformed Logistic Regression & SVM in success classification (Accuracy = 0.68)  
- K-Means identified 3 meaningful car clusters (economical, premium, and low-success groups)  
- Prophet forecast showed Audi leading sales, BMW moderate, Tata negligible for Jan–Mar  
- Ad spend positively influenced sales; price showed weaker impact  

## 🧑‍💻 Tools & Libraries
- Python (Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, Statsmodels)   
- Jupyter Notebook  

## 📌 Conclusion
The project demonstrates end-to-end data analysis, including cleaning, feature engineering, modeling, clustering, forecasting, and interpretation of results to support business decision-making in the automotive industry.
