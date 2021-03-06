# challenge_10
Module 10 Challenge Assignment

## Clustering Cryptocurrencies by Performance Using Unsupervised Learning
This is a Python application written with Pandas in Jupyter Lab. It uses the Pandas to create a DataFrame from a provided CSV file, and prepare the data by scaling it using the StandardScaler module. We use KMeans to cluster the data, and the elbow method is used to determine the best value for k. The clusters are then optimized using principal component analysis, and HvPlot is used to create interactive graphs to examine the data.

![Market Data](/Images/Market_Data.jpg)
![Elbow Curve](/Images/Elbow_Curve.jpg)
![Scatter k=4](/Images/Scatter_k_4.jpg)
![Scatter k=5](/Images/Scatter_k_5.jpg)


---

## Technologies

The application is written using Pandas

The following packages are used:

Pandas - to write and run the program [Pandas documentation](https://pandas.pydata.org/docs/)

hvPlot - to create graphs [hvPlot documentation](https://hvplot.holoviz.org/)

Pathlib - to create file paths [Pathlib documentation](https://docs.python.org/3/library/pathlib.html)

SciKit Learn - to cluster data, use principal component analysis, and scale data - [SciKit Learn documentation](https://scikit-learn.org/0.21/documentation.html)

---

## Installation Guide

Install the Pandas package using the following command: 'import pandas as pd'

Install the hvPlot library using the following command: 'import hvplot.pandas'

Install the Pathlib module using the following command: 'from pathlib import Path'

Install the SciKit Learn libraries using the following commands: 'from sklearn.cluster import KMeans', 'from sklearn.decomposition import PCA', 'from sklearn.preprocessing import StandardScaler'

--- 

## Usage

To run this program, clone the repository onto your computer, navigate to its source folder in your terminal and launch it using the command 'jupyter lab' then either run the entire program at once, or run the cells individually (in order) as you move through the file. 

---

## Contributors
Susannah Slocum 
suzyslocum@gmail.com

---

## License

None
