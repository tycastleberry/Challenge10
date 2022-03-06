## Cryptocurrency Analysis Using KMeans and Principle Component Analysis

The purpose of this project is to use unsupervised machine learning to cluster cryptocurrencies by their performance in different time periods. The KMeans algorithm will be used on the original data to analyze and plot the crypto performances. Then, principle component analysis (PCA) will be performed on the data to reduce the number of features before running the KMeans algorithm again on this data. The results will be plotted side-by-side and analyzed.
---

## Technologies

This project will be coded in Python. We will use multiple libraries and dependencies, including pandas and hvplot as well as KMeans, PCA, and StandardScaler from the sklearn library.
---

## Installation Guide

This application was built in a Jupyter notebook, and the code is fully executed. The KMeans algorithm is run on the original data and plotted using hvplot, then PCA is used to reduce the number of features before running the KMeans algorithm again. The original results are then plotted next to the PCA results for easier visualation and interpretation. 

---

## Usage

The Jupyter notebook will already be fully executed upon opening. The following is what the elbow curves should look like when finding the appropriate value for k with the original data vs the PCA data. As shown, the k value for both the original data and the PCA data is 4.

![elbow curves](https://raw.githubusercontent.com/tycastleberry/Challenge10/main/c10_elbow_curves.png)

The following shows what the clusters look like with the original data compared to the PCA data. The PCA data created clusters that are more tightly clustered together, signaling a lower inertia among the data points. This is due to the PCA data having fewer features than the original data.

![clusters](https://raw.githubusercontent.com/tycastleberry/Challenge10/main/c10_clusters.png)

---

## Contributors

Tyler Castleberry was the sole contributor to this project. 

---

## License

MIT License

Copyright (c) 2022 Tyler Castleberry

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.