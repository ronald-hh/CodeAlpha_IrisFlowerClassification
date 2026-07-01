# Iris Flower Classification

This project uses machine learning to predict the species of an Iris flower based on its measurements.

The model classifies flowers into one of three species:
- Iris-setosa
- Iris-versicolor
- Iris-virginica

It uses four features:
- Sepal Length
- Sepal Width
- Petal Length
- Petal Width

---

## Dataset

The project uses the **Iris dataset** (`Iris.csv`).

The dataset contains:
- 150 flower samples
- 3 flower species (50 samples each)
- 4 measurement columns
- 1 target column (`Species`)

The `Id` column is removed because it is not needed for prediction.

---

## What the Notebook Does

The notebook follows these steps:

1. Import the required libraries.
2. Load the Iris dataset.
3. Explore and visualize the data.
4. Prepare the data for machine learning.
5. Train different classification models.
6. Compare the models.
7. Evaluate the best-performing model.
8. Show which features are most important.
9. Predict the species of a new flower using custom measurements.

---

## Models Used

The notebook compares these machine learning models:

- Logistic Regression
- K-Nearest Neighbors (KNN)
- Decision Tree
- Support Vector Machine (SVM)
- Random Forest

---

## Requirements

Install the required libraries:

```bash
pip install numpy pandas matplotlib seaborn scikit-learn
```

---

## How to Run

1. Download or clone this project.
2. Place `Iris.csv` in the same folder as `Iris_Classification.ipynb`.
3. Open the notebook.

```bash
jupyter notebook Iris_Classification.ipynb
```

4. Run all the cells from top to bottom.

---

## Make Predictions

At the end of the notebook, you can predict a flower species by entering its measurements:

```python
predict_species(sepal_length, sepal_width, petal_length, petal_width)
```

Example:

```python
predict_species(5.1, 3.5, 1.4, 0.2)
```

---

## Results

The models achieve high accuracy on the Iris dataset, usually between **93% and 100%**.

The notebook also includes:
- Accuracy Score
- Confusion Matrix
- Classification Report
- Cross-validation

These help evaluate the performance of the models.

---

## Workflow

```text
Load Data
    ↓
Explore Data
    ↓
Prepare Data
    ↓
Train Models
    ↓
Compare Results
    ↓
Evaluate Best Model
    ↓
Predict New Flowers
```

---

## Project Goal

This project demonstrates the complete machine learning classification workflow, from data exploration to model evaluation and prediction, using the Iris dataset.
