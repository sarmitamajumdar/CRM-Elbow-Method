# CRM- Using the Elbow Method for Customer Complaint Analysis

### Elbow Method for Optimal K in K-Means Clustering
### Overview
This project demonstrates how to determine the optimal number of clusters 𝐾
for K-Means clustering using the Elbow Method. It applies TF-IDF vectorization to convert textual data into numerical form and then plots the Elbow Curve to identify the best 𝐾

### Features
Converts text data into numerical representation using TF-IDF.
Implements K-Means clustering for different values of 𝐾.
Computes Within-Cluster Sum of Squares (WCSS) for each 𝐾 
Plots the Elbow Curve to identify the optimal number of clusters.


## Installation
#### Make sure you have Python 3.x installed, and install the required dependencies:
!pip install numpy matplotlib scikit-learn

git clone https://github.com/sarmitamajumdar/CRM-Elbow-Method.git


### Code Structure
elbow_method.py → Main script that applies TF-IDF, runs K-Means, computes WCSS, and plots the Elbow Curve.
README.md → Project documentation.


### License
This project is licensed under the Apache Version 2.0, January 2004
