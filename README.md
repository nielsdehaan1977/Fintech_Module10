# Fintech_Module10

![PrincipalComponent_A_clustering.jpg](https://github.com/nielsdehaan1977/Fintech_Module10/blob/main/Images/PrincipalComponent_A_clustering.jpg)

## Crypto Clustering, Cluster Cryptocurrencies with K-means Using the Original Data and Cluster Cryptocurrencies with K-means Using the PCA Data 

## crypto_investments.ipynb
---

### This Jupyter notebook can be used as a template for cluster analysis for datasets using unsupervised learning

The tool can help with analyzing clusters in a dataset.  
* Anaylsis is done on the following steps: 
1. Find the Best Value for `k` Using the Original Data
2. Cluster Cryptocurrencies with K-means Using the Original Data
3. Optimize Clusters with Principal Component Analysis
4. Find the Best Value for `k` Using the PCA Data
5. Cluster the Cryptocurrencies with K-means Using the PCA Data
6. Visualize and Compare the Results


---
## Table of Content

- [Tech](#technologies)
- [Installation Guide](#installation-guide)
- [Usage](#usage)
- [Contributor(s)](#contributor(s))
- [License(s)](#license(s))

---
## Tech

This project leverages python 3.9 and Jupyter Lab with the following packages:

* `Python 3.9`
* `Jupyter lab`

* [JupyterLab](https://jupyter.org/) - Jupyter Lab is the latest web-based interactive development environment for notebooks, code, and data.

* [pandas](https://pandas.pydata.org/pandas-docs/stable/index.html) - Pandas is an open source, BSD-licensed library providing high-performance, easy-to-use data structures and data analysis tools for the Python programming language.

* [hvplot](https://hvplot.holoviz.org/user_guide/Plotting.html) - hvplot is generate plots from Pandas DataFrames and many other data structures of the PyData ecosystem.

* [sklearn_KMeans](https://scikit-learn.org/stable/modules/generated/sklearn.cluster.KMeans.html) - KMeans analysis via sklearn.cluster

* [sklearn_PCA](https://scikit-learn.org/stable/modules/generated/sklearn.decomposition.PCA.html) - Principal component analysis (PCA) via sklearn.decomposition

* [sklearn_StandardScaler](https://scikit-learn.org/stable/modules/generated/sklearn.preprocessing.StandardScaler.html) - Standardize features by removing the mean and scaling to unit variance via sklearn.preprocessing

---

## Installation Guide

### Before running the application first install the following dependencies in either Gitbash or Terminal. (If not already installed)

#### Step1: Activate dev environment in Gitbash or Terminal to do so type:
```python
    conda activate dev
```
#### Step2: install the following libraries (if not installed yet) by typing:
```python
    pip install pandas
    pip install -U scikit-learn
    conda install -c pyviz hvplot

    
```
#### Step3: Start Jupyter Lab
Jupyter Lab can be started by:
1. Activate your developer environment in Terminal or Git Bash (already done in step 1)
2. Type "jupyter lab --ContentsManager.allow_hidden=True" press enter (This will open Jupyter Lab in a mode where you can also see hidden files)

![JupyterLab](https://github.com/nielsdehaan1977/Fintech_Module10/blob/main/Images/JupyterLab.PNG)


## Usage

To use the crypo_investments jupyter lab notebook, simply clone the full repository and open the **crypto_investments.ipynb** file in Jupyter Lab. 

The tool will go through the following steps:

### Import the Data
* Import of data to analyze

### Prepare the Data
* Prepare data for analysis

### Find the Best Value for k Using the Original Data
* Find the best value for the amount of clusters to use in analysis of original data via elbow method

![elbow_method_graph](https://github.com/nielsdehaan1977/Fintech_Module10/blob/main/Images/elbow.jpg)

### Cluster Cryptocurrencies with K-means Using the Original Data
* Cluster data using KMeans method using original data

![KMeans_org](https://github.com/nielsdehaan1977/Fintech_Module10/blob/main/Images/scatter_org.jpg)

### Optimize Clusters with Principal Component Analysis

* Performs a principal component analysis (PCA) and reduces the features to three principal components

### Find the Best Value for l Using the PCA Data
* Find the best value for the amount of clusters to use in PCA data analysis via elbow method

### Cluster the Cryptocurrencies with K-means Using the PCA Data
* Cluster data using KMeans method using PCA data

### Visualize and Compare the Results
* Visualize elbows and clusters for both original and pca data and compare results

![elbow_compare](https://github.com/nielsdehaan1977/Fintech_Module10/blob/main/Images/elbow_compare.jpg)
![cluster_compare](https://github.com/nielsdehaan1977/Fintech_Module10/blob/main/Images/cluster_compare.jpg)


## Contributor(s)

This project was created by Niels de Haan (nlsdhn@gmail.com)

---

## License(s)

MIT
