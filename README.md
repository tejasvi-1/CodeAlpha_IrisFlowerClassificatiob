# Iris Flower Classification

CodeAlpha Data Science Internship – Task 1

## 📌 Objective
Build a machine learning model that classifies an Iris flower into one of three species — *setosa*, *versicolor*, or *virginica* — based on four measurements: sepal length, sepal width, petal length, and petal width.

## 📂 Dataset
The dataset (`data/Iris.csv`) contains 150 samples, 50 for each species, with no missing values. Source: [Kaggle Iris Dataset](https://www.kaggle.com/datasets/uciml/iris).

## 🛠 Tools & Libraries
- Python
- pandas — data loading and handling
- seaborn / matplotlib — data visualization
- scikit-learn — model building and evaluation

## 🔍 Workflow
1. **Load & inspect the data** — checked structure, data types, and confirmed no missing values.
2. **Exploratory Data Analysis** — used a pairplot to visualize relationships between features. Petal length and petal width turned out to be the strongest predictors, clearly separating *setosa* from the other two species.
3. **Train/test split** — 80% training, 20% testing, stratified to keep species proportions balanced.
4. **Model training** — trained a K-Nearest Neighbors (KNN) classifier (`n_neighbors=5`).
5. **Evaluation** — measured accuracy and generated a classification report and confusion matrix.

## 📊 Results
- **Accuracy: 100%** on the held-out test set.
- Precision, recall, and F1-score were all 1.00 across all three species.

*(Iris is a well-known "easy" dataset with well-separated classes, so a perfect score here reflects the clarity of the data rather than a claim of universal model perfection.)*

## 📁 Project Structure
```
CodeAlpha_IrisFlowerClassification/
├── data/
│   └── Iris.csv
├── iris.ipynb
└── README.md
```

## ▶️ How to Run
1. Install dependencies:
   ```
   pip install pandas numpy matplotlib seaborn scikit-learn
   ```
2. Open `iris.ipynb` in Jupyter or VS Code and run the cells in order.

## ✍️ Author
Submitted as part of the CodeAlpha Data Science Internship.
