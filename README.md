# Ball Classification

## 📌 Case Study 01: Ball Classification using Decision Tree

### Objective

The objective of this case study is to classify balls into different categories based on their given features using a **Decision Tree Classifier**.

### 🧠 Algorithm Used

**Decision Tree Classification**

A Decision Tree is a supervised machine learning algorithm that can be used for classification and regression problems. It makes decisions by splitting the data based on different features.

### 📊 Dataset

The dataset contains two independent features:

* **Feature 1:** Weight/Size of the ball
* **Feature 2:** Ball feature represented as `1` or `0`

The dependent variable represents the ball category:

* `1` → Category 1
* `2` → Category 2

### 💻 Implementation

The model is created using the `DecisionTreeClassifier` from the **Scikit-learn** library.

The following steps are performed:

1. Define the independent features.
2. Define the dependent/class labels.
3. Create a Decision Tree Classifier.
4. Train the model using the given dataset.
5. Provide new test data to the trained model.
6. Predict the category of the new balls.
7. Display the predicted results.

### 🔍 Test Data

The trained model is tested with:

```python
[[35,1], [95,0]]
```

The model predicts the categories for these two input values.

### 🛠️ Technologies Used

* Python
* Scikit-learn
* Decision Tree Algorithm

### 📦 Required Library

Install Scikit-learn using:

```bash
pip install scikit-learn
```

Or install all project dependencies using:

```bash
pip install -r ../requirements.txt
```

### ▶️ How to Run

Open the terminal inside the `Case_Study_01_Ball_Classification` folder and run:

```bash
python Ball_Classification.py
```

### 📌 Expected Output

The program displays:

```text
Ball Classification Case study
Predicted result of model is :  [1 2]
```

The exact prediction may depend on the trained Decision Tree and dataset.

### 📚 Conclusion

This case study demonstrates how a **Decision Tree Classifier** can learn from existing ball data and predict the category of new balls based on their features.
