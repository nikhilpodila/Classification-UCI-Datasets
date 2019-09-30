# Linear Classification - Red wine and Breast Cancer datasets
### Contributors: Shantanil Bagchi, Nikhil Podila, Surya

## Abstract
We investigate the performance of two linear classification techniques–**Logistic Regression** and **Linear Discriminant Analysis**–on the red wine quality and breast cancer datasets. We preprocess the data, analyse the features, before implementing the linear models and comparing their performance. <br>
We found that LDA is computationally more intensive than logistic regression, but that logistic regression needs careful selection of the hyper parameters such as the learning rate and stopping criteria. We also inferred that selection of appropriate features and transformations during data preprocessing are crucial for linear classification techniques. Additionally, we tested different learning rates for logistic regression, plotted individual feature histograms, perform correlation analysis on the features and compare the accuracies of the models.

## Repository Structure
The repository contains 6 files:
* 2 Jupyter notebook files - breast-cancer-dataset-analysis.ipynb and wine-dataset-analysis.ipynb
* 2 Dataset files - breast-cancer-wisconsin.data and winequality-red.csv
* 1 ReadMe file - ReadMe.md
* 1 Project writeup - writeup.pdf

## Code Usage - (Python 3.6.2, conda 4.3.23)
1. Install required python libraries from requirements.txt <br>
(refer to https://medium.com/python-pandemonium/better-python-dependency-and-package-management-b5d8ea29dff1 for steps to install libraries using requirements.txt)
2. Download all Jupyter notebook and Dataset files into one directory.
3. Open Jupyter notebook into that directory.
4. Select the required notebook (.ipynb file) and select "Run All" inside the jupyter notebook file.
