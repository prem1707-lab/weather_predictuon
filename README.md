# weather_predictuon
it consists of sample projects about data analytics and data science 

---

# 🌧️ Rainfall Prediction using Machine Learning

## 📌 Project Overview

This project predicts **whether it will rain tomorrow** using historical weather data and **Machine Learning models**.

We perform:

* Data Cleaning
* Missing Value Imputation
* Feature Engineering
* Exploratory Data Analysis (EDA)
* Model Training
* Prediction
* Visualization

The goal is to build a **Rain Prediction Classifier** using weather features like temperature, humidity, pressure, wind, and clouds.

---

## 📂 Dataset Features

### 🔹 Input Features

* MinTemp, MaxTemp
* Rainfall, Sunshine, Evaporation
* WindSpeed, WindDirection, WindGust
* Humidity (9am, 3pm)
* Pressure (9am, 3pm)
* Cloud (9am, 3pm)
* Temp (9am, 3pm)
* RainToday

### 🎯 Target

* **RainTomorrow (Yes/No)**

---

## ⚙️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

---

## 🚀 Project Workflow

### 1️⃣ Data Preprocessing

* Converted Date to datetime
* Filled missing values using **Mode/Median**
* Encoded categorical columns
* Feature engineering (Day, Month, Temp difference)

### 2️⃣ Exploratory Data Analysis

* Rain distribution plots
* Correlation heatmap
* Monthly rainfall trends
* Humidity & pressure analysis

### 3️⃣ Model Training

* Train-Test Split
* Random Forest Classifier
* Accuracy evaluation

### 4️⃣ Visualization

* Confusion Matrix
* Feature Importance
* Actual vs Predicted Line Plot

---

## 📊 Sample Results

Example outputs:

* Model Accuracy
* Confusion Matrix
* Feature Importance Graph
* Rain Prediction Line Plot

---

## 🧠 Model Used

```python
RandomForestClassifier()
```

Why?

* Handles missing data well
* Works great for tabular datasets
* High accuracy
* No scaling required

---

## ▶️ How to Run

### Step 1 — Install libraries

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

### Step 2 — Run script

```bash
python main.py
```

OR run in Jupyter Notebook.

---

## 📁 Project Structure

```
Rainfall-Prediction/
│
├── data.csv
├── notebook.ipynb
├── main.py
├── README.md
```

---

## 📈 Future Improvements

* Try Logistic Regression / XGBoost
* Hyperparameter tuning
* Cross-validation
* Deploy with Streamlit/Flask
* Build dashboard in Power BI

---

## 🎯 Learning Outcomes

From this project you learn:

* Data Cleaning
* Handling Missing Values
* EDA techniques
* Feature Engineering
* Classification Models
* Visualization
* End-to-end ML pipeline

---

## 👨‍💻 Author

**Prem Prasad**
Aspiring Data Scientist | Python | Machine Learning
