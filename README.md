# 🧠 Neural Network from Scratch — MNIST Digit Classification

> Built with only NumPy. No PyTorch. No TensorFlow. Just math.

![Python](https://img.shields.io/badge/Python-3.10-blue)
![NumPy](https://img.shields.io/badge/NumPy-only-orange)
![Accuracy](https://img.shields.io/badge/Test%20Accuracy-97%25-brightgreen)
![Status](https://img.shields.io/badge/Status-Complete-success)

---

## 📌 Project Overview

This project implements a **fully connected neural network from scratch** using only NumPy to classify handwritten digits from the MNIST dataset.

No deep learning libraries were used. Every component — forward propagation, backpropagation, activation functions, and gradient descent — was implemented manually to build a ground-up understanding of how neural networks actually work.

---

## 🏗️ Architecture
Input Layer  →  Hidden Layer 1  →  Hidden Layer 2  →  Output Layer
784 neurons      128 neurons          64 neurons         10 neurons
(28×28 pixels)    (ReLU)               (ReLU)            (Softmax)
---

## ⚙️ What Was Built From Scratch

| Component | Description |
|---|---|
| Forward Propagation | Matrix multiplication + bias through all layers |
| ReLU Activation | Adds non-linearity to hidden layers |
| Softmax Activation | Converts scores to probabilities at output |
| Cross-Entropy Loss | Measures prediction error |
| Backpropagation | Chain rule to compute gradients for all weights |
| Mini-Batch Gradient Descent | Weight updates using batches of 256 |

---

## 📊 Results

| Metric | Value |
|---|---|
| Dataset | MNIST (70,000 handwritten digits) |
| Training samples | 60,000 |
| Test samples | 10,000 |
| Final Test Accuracy | **~97%** |
| Epochs | 30 |
| Batch size | 256 |
| Learning rate | 0.1 |

---

## 🚀 How to Run

**Option 1 — Google Colab (recommended)**

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](YOUR_COLAB_LINK_HERE)

**Option 2 — Local**

```bash
git clone https://github.com/YOUR_USERNAME/neural-network-from-scratch
pip install numpy matplotlib scikit-learn
jupyter notebook neural_network_mnist.ipynb
```

---

## 💡 Key Concepts Learned

- How weights and biases represent neuron connections
- Why ReLU activation enables non-linear learning
- How cross-entropy loss penalizes wrong confident predictions
- How backpropagation uses the chain rule to assign blame to each weight
- Why mini-batches balance speed and stability during training

---

