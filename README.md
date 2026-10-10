
# Wine Quality Prediction Using Machine Learning

## 📌 Overview
This project predicts red wine quality categories using machine learning and physicochemical measurements. The dataset is obtained from Kaggle and analyzed using Python and Scikit-learn.

## 🎯 Objectives
- Explore and preprocess the dataset.
- Analyze feature distributions and correlations.
- Classify wine into Poor, Average, and Good categories.
- Train and compare multiple machine learning models.
- Evaluate model performance.
- Identify important features.
- Predict the quality category of sample wine data.

## 📂 Dataset
Dataset: [Red Wine Quality - Kaggle](https://www.kaggle.com/datasets/uciml/red-wine-quality-cortez-et-al-2009)

The dataset includes acidity, residual sugar, chlorides, density, sulphates, alcohol, and the original quality score.

## 🛠️ Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- KaggleHub
- Joblib

## ⚙️ Workflow
1. Download and load the dataset from Kaggle.
2. Inspect missing values, duplicates, and data types.
3. Perform exploratory data analysis (EDA).
4. Visualize feature distributions and correlations.
5. Create three quality categories:
   - **Poor:** Quality score <= 4
   - **Average:** Quality score 5 or 6
   - **Good:** Quality score >= 7
6. Split the data into training and testing sets.
7. Train multiple classification models.
8. Compare model performance.
9. Evaluate the best model using a classification report and confusion matrix.
10. Analyze feature importance where supported.
11. Generate predictions and save the trained model.

## 🤖 Machine Learning Models
- Logistic Regression
- Decision Tree
- Random Forest
- Gradient Boosting

## 📈 Evaluation Metrics
- Accuracy
- Macro Precision
- Macro Recall
- Macro F1-score
- Confusion Matrix
- Classification Report

## 📊 Output Files
- `wine_model_comparison.csv`
- `wine_model_comparison.png`
- `wine_confusion_matrix.png`
- `wine_test_predictions.csv`
- `best_wine_quality_model.pkl`
- EDA charts and feature importance results

## ▶️ How to Run
1. Open the notebook in [Google Colab](https://colab.research.google.com/) or Jupyter Notebook.
2. Install the required libraries.
3. Run the cells in order.
4. Review the model comparison and evaluation results.
5. Use the saved model for further predictions.

## 📚 Learning Outcomes
- Exploratory data analysis.
- Machine learning classification.
- Model comparison and evaluation.
- Feature importance analysis.
- Saving and using trained models.

## ⚠️ Limitations
The predictions depend on the dataset and selected quality categories. The model does not replace professional wine assessment or determine whether wine is safe to consume.
## 🏷️ Tags
`Python` `MachineLearning` `ScikitLearn` `WineQualityPrediction` `DataScience` `Kaggle`
