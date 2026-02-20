# 📘 Linear Regression vs Logistic Regression

## 📌 Project Objective

This repository demonstrates the fundamental differences between 
Linear Regression and Logistic Regression from both a mathematical 
and practical perspective.

The goal is not model evaluation, but conceptual clarity:
- How each model works
- What type of problems they solve
- How their outputs differ
- Why logistic regression uses the sigmoid function

---

## 📈 Linear Regression

### 🔹 Purpose
Used for predicting continuous numerical values.

### 🔹 Mathematical Equation

y = β0 + β1x1 + β2x2 + ... + βnxn

### 🔹 Output
- Continuous value
- Can range from -∞ to +∞

### 🔹 Dataset Used
California Housing Dataset (Regression Problem)

## 📊 Logistic Regression

### 🔹 Purpose
Used for binary classification problems.

### 🔹 Core Idea
Applies a linear model and then transforms the output using 
the Sigmoid Function.

### 🔹 Sigmoid Function

σ(z) = 1 / (1 + e^(-z))

### 🔹 Output
- Probability between 0 and 1
- Converted into class labels (0 or 1)

### 🔹 Dataset Used
Breast Cancer Wisconsin Dataset (Binary Classification)

## 🔄 Direct Comparison

| Linear Regression | Logistic Regression |
|-------------------|--------------------|
| Used for Regression | Used for Classification |
| Predicts Continuous Values | Predicts Probabilities |
| Output Range: (-∞, +∞) | Output Range: (0, 1) |
| No Activation Function | Uses Sigmoid Function |

## 🛠️ Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Scikit-learn
  
---

## 🎯 Key Takeaways

- Linear Regression predicts continuous outputs.
- Logistic Regression predicts probabilities using the sigmoid function.
- Logistic Regression is fundamentally a classification algorithm.
- Understanding output behavior is critical before applying ML models.

---

## 👨‍💻 Author

Piyush Verma  
Computer Science Student | Aspiring ML Engineer
