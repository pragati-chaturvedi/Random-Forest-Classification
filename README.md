# Iris Dataset Classification with Random Forest
This Jupyter Notebook performs classification on the Iris dataset using the Random Forest model. It includes steps for data loading, preprocessing, model training, and evaluation with a focus on interpreting results using confusion matrices and accuracy scores.

## Requirements
- Python 3.x
- Jupyter Notebook
- Required Libraries:
    * pandas
    * numpy
    * scikit-learn
    * matplotlib
    * seaborn

## Dataset
The Iris dataset is loaded from sklearn.datasets. It contains 150 samples from three iris species, with measurements for four features: sepal length, sepal width, petal length, and petal width.

## Model Used
* Random Forest Classifier
  - Various parameter settings, such as the number of trees (n_estimators), are tested to evaluate performance on the dataset.

## Structure
1. Data Loading - Loads the Iris dataset using sklearn.datasets.load_iris.
2. Exploratory Data Analysis - Briefly visualizes and describes the dataset.
3. Model Training - Trains a Random Forest classifier with selected hyperparameters.
4. Evaluation - Measures model performance through accuracy scores and confusion matrix heatmaps.

## Usage
1. Open the Jupyter Notebook and run each cell sequentially.
2. Adjust parameters, such as n_estimators, to experiment with different Random Forest configurations.

## Results
Model performance is evaluated based on accuracy scores and visualized using a confusion matrix heatmap, providing insight into classification accuracy across different species.
