# 🤖 Machine Learning From Scratch

A hands-on implementation of fundamental **Machine Learning algorithms from scratch using Python and NumPy**, without relying on high-level ML libraries for the core algorithms.

The goal of this repository is to understand **what happens behind the scenes** when common machine learning algorithms are implemented and trained.

---

## 📌 About This Repository

Instead of simply calling:

```python
LinearRegression().fit(X, y)
```

this repository focuses on understanding and implementing the underlying concepts, including:

* Mathematical formulation of ML algorithms
* Loss functions
* Gradient descent
* Parameter optimization
* Predictions
* Model training
* Visualization of learning and predictions

This is part of my journey toward developing a stronger understanding of **Machine Learning, Deep Learning, and the mathematics behind them**.

---

## 📂 Implementations

### 1. Simple Linear Regression

Implemented Simple Linear Regression from scratch.

**Concepts covered:**

* Linear relationship between variables
* Cost/Loss function
* Finding optimal parameters
* Predictions
* Visualization of the regression line

**File:** `SimpleLR.ipynb`

---

### 2. Multiple Linear Regression

Implemented Multiple Linear Regression from scratch to work with multiple input features.

**Concepts covered:**

* Multiple features
* Weight vectors
* Bias/intercept
* Predictions
* Cost function
* Model fitting

**File:** `MultipleLR.ipynb`

---

### 3. Gradient Descent

Implemented Gradient Descent to understand how machine learning models optimize their parameters.

**Concepts covered:**

* Learning rate
* Loss function
* Gradients
* Partial derivatives
* Parameter updates
* Iterative optimization

**File:** `GradientDescent.ipynb`

The implementation demonstrates how a model gradually updates its parameters to minimize the loss function.

---

## 🧠 Core Concepts

The implementations in this repository focus on understanding the following ideas:

```text
Data
  ↓
Model
  ↓
Prediction
  ↓
Loss Function
  ↓
Gradient
  ↓
Parameter Update
  ↓
Repeat
  ↓
Optimized Model
```

---

## 🛠️ Technologies Used

* **Python**
* **NumPy**
* **Matplotlib**
* **Jupyter Notebook**
* **Scikit-learn** — used where appropriate for datasets, comparisons, or validation

> The core algorithm implementations are written manually to understand the underlying mechanics.

---

## 📈 Learning Goals

Through this repository, I am working toward understanding:

* How ML algorithms work internally
* How mathematical equations translate into code
* How gradient descent optimizes parameters
* How loss functions guide model training
* How predictions are generated
* How different regression approaches are related

---

## 🚀 Future Implementations

I plan to gradually expand this repository with more algorithms, including:

* [ ] Polynomial Regression
* [ ] Logistic Regression
* [ ] K-Nearest Neighbors
* [ ] K-Means Clustering
* [ ] Decision Trees
* [ ] Random Forest
* [ ] Naive Bayes
* [ ] Support Vector Machines
* [ ] Neural Networks
* [ ] Backpropagation
* [ ] Additional optimization algorithms

The aim is to eventually build a collection of **fundamental ML and Deep Learning algorithms from scratch**.

---

## 📊 Repository Structure

```text
Machine-Learning-From-Scratch/
│
├── SimpleLR.ipynb
├── MultipleLR.ipynb
├── GradientDescent.ipynb
│
└── README.md
```

---

## 🎯 Why "From Scratch"?

Using libraries such as `scikit-learn` makes machine learning extremely convenient, but implementing algorithms manually provides a better understanding of what happens underneath the API.

For example, instead of treating gradient descent as a black box, this repository explores the process of:

$$
\theta := \theta - \alpha \frac{\partial J}{\partial \theta}
$$

where:

* $\theta$ = model parameters
* $\alpha$ = learning rate
* $J$ = loss function
* $\frac{\partial J}{\partial \theta}$ = gradient of the loss

Understanding these fundamentals makes it easier to move toward more advanced topics such as **neural networks, deep learning, and optimization**.

---

## ⭐ Progress

This repository is actively being developed as I learn and implement more machine learning algorithms.

If you're also learning ML from the fundamentals, feel free to explore the notebooks and follow along!

---

## 👩‍💻 Author

**Safia Ahmad**

B.Sc. (Hons.) Computer Science
Aligarh Muslim University

---

⭐ If you find this repository useful, consider giving it a star!
