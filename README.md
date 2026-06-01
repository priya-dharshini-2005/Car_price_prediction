# 🚗 Car_price_prediction
A Machine Learning project that predicts the selling price of used cars using features such as brand, model, mileage, fuel type, transmission type, and vehicle age. Includes data preprocessing, exploratory data analysis, model training, and evaluation using regression algorithms.
 
## 📌 Project Overview

This project predicts the selling price of used cars using Machine Learning techniques. The model learns patterns from historical car data and estimates the price based on features such as vehicle age, mileage, fuel type, engine capacity, transmission type, and more.

The goal is to help buyers and sellers make informed decisions by providing accurate car price predictions.

---

## 🎯 Objectives

* Analyze and understand the car dataset
* Perform data preprocessing and feature engineering
* Visualize important insights through Exploratory Data Analysis (EDA)
* Train and compare multiple machine learning models
* Select the best-performing model
* Predict used car selling prices accurately

---

## 📊 Dataset

The project uses the **CarDekho Dataset** containing information about used cars.

### Features Used

* Vehicle Age
* Kilometers Driven
* Fuel Type
* Transmission Type
* Engine Capacity
* Mileage
* Maximum Power
* Number of Seats
* Seller Type

### Target Variable

* Selling Price

---

## 🛠 Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn
* Pickle

---

## 🔍 Exploratory Data Analysis (EDA)

The dataset was analyzed using:

* Histograms
* Boxplots
* Heatmaps
* Scatter Plots
* Count Plots

### Key Insights

* Newer cars generally have higher selling prices.
* Engine power significantly influences price.
* Fuel type and transmission affect car valuation.
* Vehicle age negatively impacts selling price.

---

## 🤖 Machine Learning Models

The following regression models were trained and evaluated:

1. Linear Regression
2. Decision Tree Regressor
3. Support Vector Regressor (SVR)
4. Random Forest Regressor
5. Ridge Regression
6. Lasso Regression

---

## ⚙️ Hyperparameter Tuning

Hyperparameter tuning was performed using **RandomizedSearchCV** to improve model performance and identify the optimal parameters.

---

## 📈 Evaluation Metrics

The models were evaluated using:

* Mean Squared Error (MSE)
* R² Score

---

## 🏆 Best Performing Model

**Random Forest Regressor** achieved the best performance among all models due to its ability to handle complex relationships and reduce overfitting.

---

## 💾 Model Saving

The final trained model was saved using **Pickle** for future use and deployment.

---

## 🚀 Future Enhancements

* Build a web application using Flask or Streamlit
* Integrate real-time market data
* Explore advanced machine learning and deep learning models
* Deploy the model to the cloud

---

## 📌 Conclusion

This project demonstrates the application of machine learning techniques for predicting used car prices. After comparing multiple regression algorithms, Random Forest Regressor provided the best prediction performance and can be used to estimate fair market prices efficiently.

---
