# 🌾 Crop Prediction Web App

A simple machine learning web application built with Flask that predicts the most suitable crop to grow based on user inputs like nitrogen, phosphorus, potassium levels, temperature, humidity, pH, and rainfall. The model is trained using a Random Forest Classifier.

---

## 📌 Table of Contents

- [Features](#features)
- [Tech Stack](#tech-stack)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Model Details](#model-details)
- [Screenshots](#screenshots)
- [Future Improvements](#future-improvements)

---

## ✅ Features

- User-friendly web interface using Flask  
- Predicts crops based on soil and environmental features  
- Trained with Random Forest for good accuracy  
- Lightweight and easy to run locally  

---

## 🛠 Tech Stack

- Python (3.7+)
- Flask
- scikit-learn
- pandas / numpy
- HTML / CSS (basic frontend)
- Jupyter Notebook (for training)

---

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/sisteryell/Crop-Prediction.git
cd crop-prediction
```

### 2. Run the app
```bash
python app.py
```

---

## 💡 Usage

- Enter the following input values in the web form:
  - **Nitrogen (N)** – Soil nitrogen content
  - **Phosphorus (P)** – Soil phosphorus content
  - **Potassium (K)** – Soil potassium content
  - **Temperature (°C)** – Average temperature
  - **Humidity (%)** – Relative humidity
  - **pH** – Soil pH value
  - **Rainfall (mm)** – Average rainfall

- Click the **Predict** button

- The app will return the **most suitable crop** to grow under the given conditions.

 ---
 ## 🧠 Model Details

- **Algorithm**: Random Forest Classifier  
- **Library**: scikit-learn  
- **Dataset**: [Crop Recommendation Dataset (Kaggle)](https://www.kaggle.com/datasets/atharvaingle/crop-recommendation-dataset)  
- **Accuracy**: ~93%

### 📊 Features Used:
- Nitrogen (N)
- Phosphorus (P)
- Potassium (K)
- Temperature (°C)
- Humidity (%)
- pH
- Rainfall (mm)

The model was trained using a labeled dataset of environmental conditions and corresponding crops. Random Forest was chosen for its ability to handle non-linear relationships and prevent overfitting.

---

## 📷 Screenshots

![Home Page](https://github.com/sisteryell/Crop-Prediction/blob/main/Screenshot.png)

---

## 🚧 Future Improvements
- Hyperparameter tuning to improve model accuracy
- Improve UI with Bootstrap or Tailwind
