# 🔌 Perceptron Implementation for AND & OR Gates

This repository contains a simple and educational implementation of the **Perceptron algorithm** to model the **AND** and **OR** logic gates using a Python-based Jupyter Notebook.

---

## 📘 Notebook

📄 [`Perceptron_implementation_for_AND_and_OR_gates.ipynb`](./Perceptron_implementation_for_AND_and_OR_gates.ipynb)

This notebook includes:

- Introduction to perceptrons
- Truth tables of AND and OR gates
- Perceptron training algorithm
- Code implementation for:
  - AND Gate
  - OR Gate
- Accuracy evaluation
- Predicted results comparison

---

## 🧠 What is a Perceptron?

A **Perceptron** is a type of linear binary classifier that decides whether an input belongs to one class or another by calculating a weighted sum of the input features and passing it through a threshold function.

### Formula:
Output = 1 if (w₁·x₁ + w₂·x₂ + bias) ≥ 0
0 otherwise


---

## ⚙️ Logic Gate Truth Tables

### ✅ AND Gate

| A | B | A AND B |
|---|---|---------|
| 0 | 0 |    0    |
| 0 | 1 |    0    |
| 1 | 0 |    0    |
| 1 | 1 |    1    |

### ✅ OR Gate

| A | B | A OR B |
|---|---|--------|
| 0 | 0 |   0    |
| 0 | 1 |   1    |
| 1 | 0 |   1    |
| 1 | 1 |   1    |

---

## 🚀 How to Run

1. Clone this repository:
```bash
git clone https://github.com/sbhavya28/AND-and-OR-Gate-Implementation-Using-Perceptron.git
cd AND-and-OR-Gate-Implementation-Using-Perceptron
```

2. Install the required packages
```bash
pip install numpy matplotlib
```

3. Launch the notebook
```bash
jupyter notebook Perceptron_implementation_for_AND_and_OR_gates.ipynb
```
