# Breast-Cancer-Prediction-using-Unsupervised-ML-Methods

Breast Cancer Prediction using Unsupervised and Semi-supervised Techniques

Breast Cancer dataset:
--------------------------

The Breast Cancer data set is a real-valued multivariate data that consists of two classes, where each class signifies whether a patient has breast cancer or not. The two categories are: malignant and benign.

The malignant class has 212 samples, whereas the benign class has 357 samples.

It has 30 features shared across all classes: radius, texture, perimeter, area, smoothness, fractal dimension, etc.


Below tasks are covered in the project:
---------------------------------------
* Apply various unsupervised techniques and compare what works best for the data
* Apply pca, kmeans as a preprocessing
* Determine the optimal number of clusters and plot the cluster of faces
* Take the test data and create labels for the test data using the semi-supervised method
* Have a validation dataset to verify the created labels are close to the validation test labels before propagating them into the test set
* `Final Result: Accuracy increased from 90% to 92% by propagating labels only to the instances that are really close to the centroid`
