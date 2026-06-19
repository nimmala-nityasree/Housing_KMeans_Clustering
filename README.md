# 🏠 Housing Data Analysis and K-Means Clustering

## 📌 Overview

This project demonstrates basic Exploratory Data Analysis (EDA) and K-Means Clustering on a housing dataset. The goal is to analyze housing features and group similar houses into clusters based on their characteristics.

## 🎯 Objectives

* Load and explore the housing dataset.
* Visualize housing data using plots.
* Preprocess numerical features.
* Apply K-Means Clustering.
* Visualize the resulting clusters.

## 📂 Dataset

The dataset used is **Housing.csv**, containing information about houses such as:

* Area
* Bedrooms
* Price
* Other housing-related attributes

## 🛠️ Technologies Used

* Python
* Pandas
* Matplotlib
* Scikit-learn
* Google Colab

## 📊 Data Visualization

The following visualizations were created:

### 1. Histogram

Shows the distribution of house prices.

### 2. Scatter Plot

Displays the relationship between house area and price.

## 🤖 K-Means Clustering

### Steps Performed

1. Selected numerical features:

   * Area
   * Bedrooms
   * Price

2. Handled missing values.

3. Standardized the data using `StandardScaler`.

4. Applied K-Means Clustering with **3 clusters**.

5. Assigned cluster labels to each house.

6. Visualized the clusters using a scatter plot.

## 📈 Results

The houses were successfully grouped into clusters based on their features. The clustering visualization helps identify patterns among different types of houses and their pricing characteristics.

## 🚀 How to Run

1. Open the notebook in Google Colab.
2. Upload `Housing.csv`.
3. Run all cells sequentially.
4. View the generated plots and clustering results.

## 📚 Learning Outcomes

* Understanding of Exploratory Data Analysis (EDA).
* Experience with data visualization using Matplotlib.
* Knowledge of feature scaling.
* Practical implementation of K-Means Clustering.
* Interpretation of clustering results in real-world datasets.
