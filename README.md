# Synthetic-based_GMMs
A set of ground motion models developed by 4 machine learning algorithms (ANN, RF, SVM, XGBoost) for synthetic accelerogram database.

This repository contains a Jupyter Notebook titled GMMs_Load_Predict.ipynb, which provides scripts for loading and using GMMs based on ANN, RF, SVM and XGBoost.

In the notebook, separate code cells are provided for each model, allowing users to conveniently load the corresponding model and predict PGA values based on user-defined inputs of magnitude, hypocentral distance and Vs30.

⚠️ Important: Ensure that the trained model files and their associated scaler files (e.g., .h5, .pkl) are placed in the same directory as the notebook to enable successful loading and prediction.
