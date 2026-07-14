# ✈️ Flight Fare Prediction

## 📌 Project Overview

The Flight Fare Prediction project is a Machine Learning application that predicts airline ticket prices based on various travel details such as airline, source, destination, journey date, departure time, arrival time, duration, and number of stops. The goal is to help travelers estimate flight fares before booking and assist businesses in making data-driven pricing decisions.

---

## 🎯 Problem Statement

Airline ticket prices change frequently due to multiple factors, making it difficult for customers to know the best time to book flights. This project uses historical flight data and machine learning algorithms to predict flight fares accurately.

---

## 🚀 Features

- Data Cleaning and Preprocessing
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Outlier Detection and Handling
- Model Training and Evaluation
- Flight Fare Prediction
- Model Performance Comparison
- Feature Importance Analysis

---

## 📂 Dataset

The dataset contains flight booking information such as:

- Airline
- Date of Journey
- Source
- Destination
- Route
- Departure Time
- Arrival Time
- Duration
- Total Stops
- Additional Information
- Price (Target Variable)

---

## 🛠️ Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost (Optional)

---

## 📊 Machine Learning Workflow

1. Data Collection
2. Data Cleaning
3. Exploratory Data Analysis
4. Feature Engineering
5. Data Encoding
6. Train-Test Split
7. Model Building
8. Model Evaluation
9. Hyperparameter Tuning
10. Final Prediction

---

## 🤖 Models Used

- Linear Regression
- Decision Tree Regressor
- Random Forest Regressor
- Gradient Boosting Regressor
- XGBoost Regressor (Optional)

---

## 📈 Evaluation Metrics

- R² Score
- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)

---

## 📁 Project Structure

```
Flight-Fare-Prediction/
│
├── Dataset/
│   └── flight_data.csv
│
├── notebooks/
│   └── Flight_Fare_Prediction.ipynb
│
├── models/
│   └── trained_model.pkl
│
├── images/
│   └── eda_plots.png
│
├── requirements.txt
├── README.md
└── app.py (Optional)
```

---

## 📦 Installation

Clone the repository

```bash
git clone https://github.com/your-username/Flight-Fare-Prediction.git
```

Navigate to the project

```bash
cd Flight-Fare-Prediction
```

Install dependencies

```bash
pip install -r requirements.txt
```

Run the Jupyter Notebook

```bash
jupyter notebook
```

---

## 📷 Exploratory Data Analysis

The project includes:

- Price Distribution
- Airline-wise Fare Analysis
- Source & Destination Analysis
- Correlation Heatmap
- Feature Importance
- Boxplots
- Countplots

---

## 📌 Results

The trained machine learning model successfully predicts flight ticket prices with good accuracy.

Example output:

| Airline | Source | Destination | Stops | Predicted Price |
|----------|---------|-------------|--------|-----------------|
| IndiGo | Delhi | Mumbai | Non-stop | ₹5,800 |
| Air India | Kolkata | Bangalore | 1 Stop | ₹7,900 |

---

## 🔮 Future Improvements

- Deploy using Flask or Streamlit
- Live Flight API Integration
- Deep Learning Models
- Real-time Price Prediction
- Interactive Dashboard

---

## 👨‍💻 Author

**Shubham Tayade**

- GitHub: https://github.com/your-username
- LinkedIn: https://linkedin.com/in/your-profile

---

## ⭐ If you found this project useful, don't forget to Star the repository!
