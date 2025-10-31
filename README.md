#  House Price Prediction

##  Overview
This project predicts house prices using **machine learning** techniques based on features like location, area, rooms, and median income.  
It demonstrates the full ML workflow — **data cleaning, EDA, feature engineering, model training, evaluation**, and **prediction on new data** using a saved model.


---
---

## 🧾 Project Details

**Project Title:**  
🏠 *House Price Prediction using Machine Learning*

**Objective / Aim:**  
The main objective of this project is to build a **machine learning model** that can accurately predict the **median price of a house** based on various factors like location, number of rooms, income, and proximity to the ocean.  
This helps in understanding how different features affect housing prices and can assist buyers, sellers, or real estate companies in making data-driven decisions.

**Project Description:**  
This project focuses on predicting house prices using **regression-based machine learning models**.  
It includes all the stages of a data science pipeline — from **data collection, cleaning, and exploratory data analysis (EDA)** to **feature engineering, model training, and prediction**.  
The model is trained on the **California Housing Dataset**, and the best-performing model is saved using **Joblib** for future use.  
New, unseen data can also be passed to the trained model to predict house values instantly.

**Technologies / Tools Used:**  
- Programming Language: **Python 3.x**  
- Libraries: **Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, Joblib**  
- Dataset: **California Housing Dataset**  
- IDE: **Jupyter Notebook / VS Code**

**Methodology:**  
1. Data collection and loading  
2. Data cleaning and preprocessing  
3. Feature engineering (log transformations, ratio features, dummy encoding)  
4. Model training using **Linear Regression**  
5. Model evaluation using **R² Score** and **Mean Absolute Error (MAE)**  
6. Saving trained model using `joblib.dump()`  
7. Predicting new house prices using saved model  

**Result / Output:**  
The trained model achieved an **R² Score of 0.83** with a **Mean Absolute Error of ₹45,000** (approx).  
For new input data, the model successfully predicts the **median house value** based on the given features.

**Conclusion:**  
This project demonstrates how machine learning can be applied in the **real estate domain** to predict property prices efficiently.  
With further tuning and advanced algorithms like XGBoost or Neural Networks, the accuracy can be improved.  
It provides a foundation for creating smart, data-driven applications for property evaluation.

**Future Scope:**  
- Integration of advanced models (XGBoost, CatBoost, etc.)  
- Web application deployment using **Streamlit or Flask**  
- Real-time prediction using live housing market data  

---

## 🚀 Features
- Data preprocessing and cleaning  
- Exploratory Data Analysis (EDA) with visualizations  
- Feature engineering and encoding  
- Model training using regression algorithms  
- Saving and loading models using **Joblib**  
- Predicting new house prices with unseen data  

---

##  Dataset
Dataset used: [California Housing Dataset](https://www.kaggle.com/datasets/camnugent/california-housing-prices)  

**Example columns:**
- `longitude` — Longitude coordinate of the house block  
- `latitude` — Latitude coordinate of the house block  
- `housing_median_age` — Median age of houses in the area  
- `total_rooms` — Total number of rooms in the block  
- `median_income` — Median income of households  
- `ocean_proximity` — Location category relative to the ocean  
- `median_house_value` — Target variable (house price)
---

## ⚙️ Installation

Clone this repository:
```bash
git clone https://github.com/nitesh-kumar864/House-Price-Prediction-using-Machine-Learning.git
cd house-price-prediction
