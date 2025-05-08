# 🌳 Decision Tree Classifier on Iris Dataset

This project demonstrates how a Decision Tree Classifier can be used for **multiclass classification** using the well-known **Iris dataset**.

## 📌 Objective
Predict the species of an iris flower (Setosa, Versicolor, Virginica) based on its:
- Sepal length
- Sepal width
- Petal length
- Petal width

## 🧠 Methodology
- Load and split the dataset using `train_test_split`
- Train a `DecisionTreeClassifier` from scikit-learn
- Evaluate model performance using a classification report
- Visualize the trained decision tree

## 🛠 Tech Stack
- Python
- scikit-learn
- Matplotlib

## 📈 Results
- High accuracy on test data
- Fully interpretable decision paths
- Clear visualization of feature splits

## Insights:

1. Setosa is perfectly predicted.

2. Versicolor has slightly lower recall (0.92), meaning a couple of actual versicolor samples may have been misclassified.

3. Virginica has slightly lower precision (0.89), which means a few non-virginica were incorrectly predicted as virginica, but recall is 1.00, so it found all the actual virginica samples.

4. Accuracy is 0.97, means the model predited 97% of the data  correctly.

## 🌍 Applications
- Credit scoring
- Medical diagnosis
- Rule-based automation
- Fraud detection

## 📷 Visualization
![image](https://github.com/user-attachments/assets/d8747e3e-4c1b-4daa-934f-8ae5e282a638)


---

## Conclusion:

The Decision Tree Classifier is perfect for understanding how machine learning makes decisions based on feature thresholds.It's also easily visualizable making it ideal for teaching,model interpretability or quick prototyping.
