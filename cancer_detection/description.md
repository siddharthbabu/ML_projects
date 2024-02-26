Breast Cancer Prediction Using Logistic Regression and Decision Tree

This project focuses on predicting breast cancer using the Logistic Regression and Decision Tree algorithms. The dataset used contains features of breast masses. 

The features include:

-Radius: The mean distance from the center to points on the perimeter of the nucleus.<br />
-Texture: The standard deviation of gray-scale values in the nucleus.<br />
-Perimeter: The perimeter of the nucleus.<br />
-Area: The area of the nucleus.<br />
-Smoothness: A measure of local variation in radius lengths.<br />
-Compactness: Computed as the square of the perimeter divided by the area minus 1.0.<br />
-Concavity: Describes the severity of concave portions of the nucleus contour.<br />
-Concave points: Represents the number of concave portions of the nucleus contour.<br />
-Symmetry: Measures the symmetry of the nucleus.<br />
-Fractal dimension: Approximates the "coastline" of the nucleus, using the concept of fractal geometry.<br />

Logistic Regression:
Logistic Regression is a popular machine learning algorithm used for binary classification tasks. In this project, we use Logistic Regression to predict whether a breast mass is benign or malignant based on the provided features.

Decision Tree:
Decision Tree is a versatile machine learning algorithm that can perform both classification and regression tasks. In this project, we use Decision Tree for binary classification to predict breast cancer based on the specified features.

Methodology:<br />
-Data Preprocessing: The dataset is preprocessed to handle missing values, normalize the features, and split it into training and testing sets.<br />
-Model Training: Both the Logistic Regression and Decision Tree models are trained on the training set using the specified features.<br />
-Model Evaluation: The trained models are evaluated on the testing set using metrics such as accuracy, precision, recall, and F1-score.<br />
-Results: The results of the classification are analyzed and visualized to assess the performance of the Logistic Regression and Decision Tree models.<br />

Repository Contents:<br />
Jupyter Notebook containing the data preprocessing, model training, and evaluation code for both algorithms.
Dataset used for training and testing the models.

Technologies Used:<br />
-Python<br />
-scikit-learn<br />
-Jupyter Notebook<br />
