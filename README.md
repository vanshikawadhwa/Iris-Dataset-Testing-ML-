
# 🌸 Iris Flower Classification — PyTorch Implementation

This project is a simple yet effective **machine learning pipeline using PyTorch** to classify iris flower species based on their morphological features.

It uses the classic [Iris dataset](https://archive.ics.uci.edu/ml/datasets/iris), which contains data on three iris species (*Setosa*, *Versicolor*, and *Virginica*), with four input features.

---

## 📂 Files

- `iris_evaluation.py` – Core Python script implementing:
  - Data loading and preprocessing with pandas
  - Label encoding of species
  - Conversion to PyTorch tensors
  - A simple neural network classifier
  - Training and evaluation (accuracy, confusion matrix, classification report)

---

## 📊 Dataset Overview

Each sample contains:

| Feature        | Description         |
|----------------|---------------------|
| Sepal Length   | in cm               |
| Sepal Width    | in cm               |
| Petal Length   | in cm               |
| Petal Width    | in cm               |
| Species        | Setosa / Versicolor / Virginica |

---

## 🧠 Model Architecture

- Simple **Feedforward Neural Network**
- Input size: 4 (features)
- Hidden layers: Configurable
- Output size: 3 (classes)
- Loss: `CrossEntropyLoss`
- Optimizer: `Adam`

---

## 🚀 How to Run

### 1. Install dependencies:

```bash
pip install torch pandas scikit-learn matplotlib seaborn
```

### 2. Run the script:

```bash
python iris_evaluation.py
```

You’ll see:
- Model training logs
- Accuracy score
- Confusion matrix
- Classification report

---

## 📈 Sample Output

```
Accuracy: 0.96
Confusion Matrix:
[[13  0  0]
 [ 0 10  1]
 [ 0  1 10]]
```

---

## 🔍 Future Enhancements

- Add train/validation/test split
- Improve model performance through hyperparameter tuning
- Visualize training loss over epochs
- Add interactive Streamlit interface

---

## 🧑‍💻 Author

**Vanshika Wadhwa**  
📧 wadhwav@usc.edu  
🔗 [LinkedIn](https://linkedin.com/in/vanshika-wadhwa-449ba4192/) | [GitHub](https://github.com/vanshikawadhwa)
