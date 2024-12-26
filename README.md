# Iris Flower Classification

This repository contains a machine learning project designed to classify iris flowers into three species **Setosa**, **Versicolor**, and **Virginica** based on the famous [Iris dataset](https://archive.ics.uci.edu/ml/datasets/iris). The project demonstrates how to preprocess data, explore it visually, and train machine learning models.

## Dataset

The Iris dataset includes 150 observations with the following features:

- **SepalLengthCm**: Length of the sepal in centimeters.
- **SepalWidthCm**: Width of the sepal in centimeters.
- **PetalLengthCm**: Length of the petal in centimeters.
- **PetalWidthCm**: Width of the petal in centimeters.
- **Species**: Target variable, indicating the flower species (Setosa, Versicolor, Virginica).

## Key Libraries

The project leverages the following Python libraries:

- **Pandas**: For data manipulation and analysis.
- **NumPy**: For numerical computations.
- **Matplotlib & Seaborn**: For data visualization.
- **Scikit-learn**: For implementing and evaluating machine learning models.

## Machine Learning Models

Several machine learning algorithms were applied to classify the iris species:

- **Decision Tree Classifier**
- **K-Nearest Neighbors (KNN)**

## Project Workflow

1. **Data Preprocessing**:
   - Checking for missing values (no missing data in this dataset).
   - Splitting the dataset into training and testing sets.

2. **Exploratory Data Analysis (EDA)**:
   - Analyzing feature importance and separability among species.

3. **Model Training and Evaluation**:
   - Training the models on the training set.
   - Evaluating models using accuracy and Confusion Matrix.

4. **Results**:
   - The Decision Tree Classifier achieved the highest accuracy of **95.56%**

## Results Summary

The project achieved the following outcomes:
- The dataset is well-separated, enabling high classification accuracy with simple models.
- Petal length and petal width are the most discriminative features for species classification.

## How to Use

1. Clone this repository:
   ```bash
   git clone https://github.com/ramosmat/iris-predict.git
   ```

2. Navigate to the project directory:
   ```bash
   cd iris-predict
   ```

3. Install the required libraries:
   ```bash
   pip install -r requirements.txt
   ```

4. Run the Jupyter Notebook or Python script:
   ```bash
   jupyter notebook script.ipynb
   ```

## Contributing

Contributions are welcome! Feel free to submit issues or pull requests to enhance the project.