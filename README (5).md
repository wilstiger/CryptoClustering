
# CryptoClustering

This repository contains the `CryptoClustering` project, where we apply machine learning techniques like **K-Means Clustering** and **Principal Component Analysis (PCA)** to classify cryptocurrencies based on their price fluctuations across various timeframes. The project demonstrates the use of **unsupervised learning** to identify clusters within a dataset of cryptocurrency price data, showcasing skills in data processing, dimensionality reduction, clustering, and visualization.

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Contributing](#contributing)


## Overview

The goal of this project is to explore and classify cryptocurrencies based on their price behavior over various timeframes, using techniques like **K-Means Clustering** and **PCA** for dimensionality reduction. By analyzing the elbow method for choosing the optimal number of clusters and using PCA to reduce the feature space, we can better understand the relationships and potential clusters within the cryptocurrency market data.

## Features

- **K-Means Clustering**: Identify optimal clusters based on the elbow method using both the original and PCA-reduced data.
- **Principal Component Analysis (PCA)**: Reduce high-dimensional data to three principal components to improve clustering performance.
- **Data Visualization**: Generate elbow plots to determine the best value for k and scatter plots for visualizing the clusters.
- **Feature Influence Analysis**: Examine feature weights on each principal component to understand the strongest influences.

## Technologies Used

- **Python**: Programming language used for the entire project.
- **Jupyter Notebook**: For interactive development and visualization.
- **Pandas**: Data manipulation and analysis library.
- **Scikit-Learn**: Machine learning library for K-Means clustering and PCA.
- **Matplotlib** and **hvPlot**: Data visualization libraries.

## Installation

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/YOUR_USERNAME/CryptoClustering.git
   ```
2. **Navigate to the Project Directory**:
   ```bash
   cd CryptoClustering
   ```
3. **Install Dependencies**: It is recommended to use a virtual environment. Run the following command to install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
   Ensure `requirements.txt` includes the necessary libraries:
   ```
   pandas
   scikit-learn
   matplotlib
   hvplot
   holoviews
   ```

## Usage

1. **Open Jupyter Notebook**:
   ```bash
   jupyter notebook
   ```
2. **Run the `Crypto_Clustering.ipynb` Notebook**:
   - This notebook walks through data loading, scaling, PCA transformation, K-Means clustering, and visualization.
   - Follow each cell and review comments for explanations on the implementation.

### Key Sections in the Notebook

- **Finding the Best Value for k**: Uses the elbow method on both original scaled data and PCA data.
- **Clustering Cryptocurrencies**: Applies K-Means with the optimal k value and visualizes clusters on scatter plots.
- **PCA Transformation**: Reduces the data to three principal components, calculates explained variance, and visualizes in reduced dimensions.
- **Feature Influence Analysis**: Displays PCA component loadings to identify influential features.

## Project Structure

```
CryptoClustering/
├── Crypto_Clustering.ipynb    # Main notebook with the project implementation
├── crypto_market_data.csv     # Sample data file for cryptocurrency prices
├── requirements.txt           # List of dependencies
└── README.md                  # Project documentation
```

## Contributing

Contributions are welcome! Please follow these steps:

1. **Fork the repository**.
2. **Create a new branch**:
   ```bash
   git checkout -b feature-branch
   ```
3. **Commit your changes**:
   ```bash
   git commit -m "Add new feature"
   ```
4. **Push to the branch**:
   ```bash
   git push origin feature-branch
   ```
5. **Create a Pull Request** on GitHub.

