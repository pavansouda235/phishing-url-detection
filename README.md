# Phishing URL Detection

A machine learning and deep learning project that classifies URLs as legitimate or phishing.

## Project overview

This notebook explores URL features and compares two approaches:

- A hybrid Support Vector Machine (SVM) using character-level TF-IDF and handcrafted URL features
- A character-level Convolutional Neural Network (CNN)

It evaluates the models with metrics such as accuracy, precision, recall, F1 score, and ROC-AUC.

## Run the notebook

1. Clone or download this repository.
2. Install Python and the notebook dependencies used in the project, including pandas, scikit-learn, scipy, matplotlib, and TensorFlow.
3. Place `phishing_url_dataset_unique.csv` in the same folder as the notebook.
4. Open `phishing_url_project.ipynb` in Jupyter or VS Code and run the cells.

## Dataset

The notebook expects a CSV file named `phishing_url_dataset_unique.csv` with `url`, `label`, and `source` columns. The dataset is not included in this repository. Add it only if its license and source terms allow redistribution.

## Notes

This is an educational project. Predictions are not a guarantee that a URL is safe. Do not visit suspicious URLs to test them.

## Author

Pavan Kumar Souda — [@pavansouda235](https://github.com/pavansouda235)
