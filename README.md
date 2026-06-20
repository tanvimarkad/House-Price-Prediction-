# 🏠 House Price Prediction using Machine Learning

## 📌 Project Overview

This project predicts house prices using Machine Learning techniques. The objective is to estimate the price of a house based on features such as area, number of bedrooms, bathrooms, stories, parking, furnishing status, and other property details.

The project includes data preprocessing, exploratory data analysis (EDA), visualization, model building, evaluation, and comparison of two regression algorithms: **Linear Regression** and **Random Forest Regressor**.

---

## 🎯 Problem Statement

Real estate buyers and sellers often rely on manual estimation or outdated comparisons to determine the value of a property. This project develops a predictive model that estimates house prices using historical housing data and identifies the features that have the greatest impact on price.

---

## 📂 Dataset

- **Dataset Name:** Housing Prices Dataset
- **Source:** Kaggle
- **File:** `Housing.csv`

Dataset contains information such as:
- Price
- Area
- Bedrooms
- Bathrooms
- Stories
- Main Road
- Guest Room
- Basement
- Hot Water Heating
- Air Conditioning
- Parking
- Preferred Area
- Furnishing Status

---

## 🛠️ Technologies Used

- Python 3.x
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## 📊 Project Workflow

1. Load the dataset
2. Explore the data
3. Handle missing values
4. Remove duplicate records
5. Encode categorical variables
6. Split data into training and testing sets
7. Train a Linear Regression model
8. Train a Random Forest Regressor
9. Evaluate both models using:
   - MAE
   - RMSE
   - R² Score
10. Compare model performance
11. Visualize the results
12. Analyze feature importance
13. Draw conclusions

---

## 📈 Visualizations

The project includes the following visualizations:

- House Price Distribution Histogram
- Correlation Heatmap
- Actual vs Predicted Price Scatter Plot

---

## 🤖 Machine Learning Models

### Linear Regression
A basic regression algorithm used to predict house prices based on a linear relationship between features and the target.

### Random Forest Regressor
An ensemble learning algorithm that combines multiple decision trees to improve prediction accuracy and reduce overfitting.

---

## 📏 Evaluation Metrics

The models are evaluated using:

- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)
- R² Score

---

## 📌 Key Insights

- House area is the most influential feature affecting price.
- Bathrooms, stories, parking, and air conditioning also significantly impact house prices.
- Random Forest Regressor provides better prediction accuracy than Linear Regression.
- Furnished houses generally have higher prices compared to unfurnished houses.

---

## 📁 Project Structure

```
HousePricePrediction/
│
├── analysis.ipynb
├── Housing.csv
├── summary.pdf
├── README.md
├── requirements.txt
└── charts/
    ├── histogram.png
    ├── heatmap.png
    └── prediction.png
```

---

## ▶️ How to Run the Project

1. Clone the repository.

```
git clone <repository-url>
```

2. Open the project folder.

3. Install the required libraries.

```
pip install -r requirements.txt
```

4. Launch Jupyter Notebook.

```
jupyter notebook
```

5. Open `analysis.ipynb` and run all cells.

---

## 📌 Future Improvements

- Add more housing datasets
- Implement XGBoost and Gradient Boosting models
- Deploy the model using Flask or Django
- Create a web application for real-time house price prediction

---

## 👩‍💻 Author

**Tanvi Vinod Markad**

Artificial Intelligence & Data Science Engineering Student

---

## 📜 License

This project is developed for educational and internship purposes.
