# CIFAR-10 Dense Neural Network

A simple fully connected neural network trained on the CIFAR-10 dataset using TensorFlow and Keras.  
Includes accuracy and loss visualization over training epochs.

---

## 🛠 Features
- Dense neural network with two hidden layers
- Multi-class classification on CIFAR-10 (10 classes)
- Accuracy and loss plots for train/validation sets
- Easy to run and modify
- Suitable for educational purposes and demo

---

## 📂 Project Structure

```
cifar10-dense-nn/
 ├── cifar10_dense_nn.py   # Main Python script with full workflow
 ├── README.md             # This file
 ├── requirements.txt      # Dependencies
 └── data/                 # CIFAR-10 dataset (downloaded automatically)
```

---

## ⚡ How to Run

1. Create a virtual environment:

```bash
python -m venv venv
# Activate environment:
# Windows:
venv\Scripts\activate
# macOS/Linux:
source venv/bin/activate
```

2. Install dependencies:

```bash
pip install -r requirements.txt
```

3. Run the project:

```bash
python cifar10_dense_nn.py
```

> The script downloads CIFAR-10 automatically, trains a dense network, and plots accuracy and loss curves.

---

## 🧰 Requirements

- Python 3.8+  
- numpy  
- matplotlib  
- tensorflow  
- scikit-learn  

---

## 📄 License

MIT License
