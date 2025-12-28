# Flight Fare Prediction using Machine Learning

This project is a **machine learning-based flight fare prediction system** that estimates airline ticket prices using historical flight data. The model predicts fares based on factors such as airline, source, destination, journey date, duration, and number of stops.

---

## Problem Statement
Flight ticket prices fluctuate frequently due to various factors like airline policies, demand, timing, and route details. Predicting flight fares in advance can help users make better travel and booking decisions.

---

## Objective
To build an accurate and reliable **machine learning model** that predicts flight ticket prices using supervised learning techniques.

---

## Technologies Used
- Python  
- Pandas & NumPy  
- Matplotlib & Seaborn  
- Scikit-learn  
- Pickle / Joblib  

---

## Machine Learning Approach
- Data cleaning and preprocessing  
- Feature engineering (date, time, duration extraction)  
- Encoding categorical variables  
- Model training using **Random Forest Regression**  
- Model evaluation and performance analysis  
- Saving and loading the trained model for future predictions  

---

## Features Used
- Airline  
- Source  
- Destination  
- Journey Date  
- Departure Time  
- Arrival Time  
- Duration  
- Total Stops  

---

## Model Persistence
The trained model is saved using `pickle`, allowing reuse without retraining. This makes the project deployment-ready and efficient.

---

## How to Run the Project
1. Clone the repository  
   ```bash
   git clone https://github.com/your-username/Flight_Fare_Prediction.git

