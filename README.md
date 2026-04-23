---

# 📊 Heart Disease Prediction using Logistic Regression

## 📌 Project Overview

This project is a hands-on machine learning practice where I built a **Logistic Regression model** to predict the likelihood of heart disease using a dataset sourced from Kaggle.

The goal is to understand the end-to-end ML workflow — from data loading and preprocessing to model training, evaluation, and prediction.

---

## 📂 Dataset

* **Source:** Kaggle Heart Disease Dataset

* The dataset contains medical attributes such as:

  * Age
  * Sex
  * Chest pain type
  * Resting blood pressure
  * Cholesterol level
  * Maximum heart rate achieved
  * And more…

* **Target Variable:**

  * `0` → No heart disease
  * `1` → Presence of heart disease

---

## ⚙️ Technologies Used

* Python 🐍
* Pandas
* NumPy
* Scikit-learn

---

## 🔍 Project Workflow

### 1. Data Loading & Exploration

* Loaded dataset using Pandas
* Checked:

  * Data structure (`info()`)
  * Statistical summary (`describe()`)
  * Missing values (`isnull().sum()`)

---

### 2. Data Preprocessing

* Split dataset into:

  * **Features (X)**
  * **Target (y)**

---

### 3. Train-Test Split

* Used `train_test_split`:

  * 80% Training data
  * 20% Testing data

---

### 4. Model Building

* Algorithm used: **Logistic Regression**

```python
model = LogisticRegression()
model.fit(X_train, y_train)
```

---

### 5. Model Evaluation

* Evaluated using **Accuracy Score**

* Training Accuracy

* Testing Accuracy

This helps check if the model is:

* Learning well
* Not overfitting

---

### 6. Prediction System

Built a simple predictive system where new patient data can be passed into the model:

```python
input_data = (34,0,1,118,210,0,1,192,0,0.7,2,0,2)
prediction = model.predict(input_data_reshape)
```

* Output:

  * `0` → No heart disease
  * `1` → Heart disease detected

---

## 📈 Results

* The model achieved good accuracy on both training and testing data.
* Demonstrates that Logistic Regression can be effective for binary classification problems like this.

---

## 🚀 Key Learnings

* Understanding dataset structure and features
* Importance of data preprocessing
* How Logistic Regression works for classification
* Model evaluation using accuracy score
* Building a simple prediction system

---

## 📁 Project Structure

```
├── heart_disease.ipynb   # Jupyter Notebook with full workflow
├── heart.csv             # Dataset
├── README.md             # Project documentation
```

---

## 🤝 Connect With Me

I’m currently learning and building projects in **Data Science & Machine Learning**.
Feel free to connect or give feedback!

**linkedln:** http://linkedin.com/in/okposo-michael-b0b99224a 
