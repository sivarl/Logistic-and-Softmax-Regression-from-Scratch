# Logistic & Softmax Regression from Scratch (NumPy)
This project demonstrates the implementation of core machine learning algorithms from scratch using NumPy, without relying on high-level libraries like scikit-learn.

## 📌 Implementations

### 1. Logistic Regression (Binary Classification)
- Implemented sigmoid function with numerical stability
- Derived and implemented cross-entropy loss
- Computed gradients (dw, db) using vectorized operations
- Trained model using gradient descent
- Visualized decision boundary and loss convergence

### 2. Softmax Regression (Multiclass Classification)
- Implemented softmax function with numerical stability (log-sum-exp trick)
- Computed categorical cross-entropy loss
- Derived gradients for multiclass classification
- Built full training loop using gradient descent

## 🛠️ Tech Stack
- Python
- NumPy
- Matplotlib

## 📂 Project Structure
- `01_logistic_regression_basics.ipynb` → Binary Classification from scratch
- `02_softmax_regression_from_scratch.ipynb` → Multiclass classification

## 🎯 Key Learning Outcomes
- Strong understanding of model internals (not just usage)
- Hands-on implementation of optimization (gradient descent)
- Numerical stability techniques for real-world ML
