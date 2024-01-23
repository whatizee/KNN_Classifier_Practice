# KNN Classifier

## Introduction
This project implements a simple k-nearest neighbors (KNN) classifier using Python with Pandas and NumPy. The classifier predicts the category/class of a given sample based on its nearest neighbors in the training dataset.

## Files
- `KNN_Classifier.py`: Python script containing the implementation of the KNN classifier for two different datasets.
- `README.md`: Documentation file.

## Datasets
1. `Dataset 1` (`df1`):
    - Features: X2, Y2
    - Target: Category (Blue, Orange)

2. `Dataset 2` (`df2`):
    - Features: Age, Weight
    - Target: Gender (Male, Female)

## Usage
1. Install required libraries:
    ```bash
    pip install pandas numpy scikit-learn
    ```

2. Run the script:
    ```bash
    python KNN_Classifier.py
    ```

## Implementation Details
- The code uses the `train_test_split` function from scikit-learn to split the dataset into training and testing sets.
- Euclidean distance is calculated to find the similarity between the samples.
- The classifier predicts the category/class of a given sample based on the majority class of its k-nearest neighbors.

## Sample Output
Sample is
X2 28
Y2 176
Name: 3, dtype: int64
Distance from sample to all X_train values
[12.041594578792296, 16.0312195418814, 6.0, 11.0, 14.317821063276353, 13.416407864998739, 23.53720459187964, 0.0, 1.0]
Sorted index is
[7 8 2 5 0 3 1 4 6 9]
3 nearest index values are
[7 8 2]
KNN predicted that the given sample tends to be Blue


## Conclusion
This KNN Classifier is a basic implementation for educational purposes. It can be extended for more complex datasets and scenarios.

Feel free to experiment with different datasets and parameters to understand the behavior of the classifier.
