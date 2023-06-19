# Image Processing Semester Project
This repository contains code for image processing using the MLPClassifier algorithm. The code utilizes the scikit-learn library in Python to train and test a multi-layer perceptron (MLP) classifier on a dataset of handwritten digit images.

## Dataset
The code uses the digits dataset, which consists of grayscale images of handwritten digits (0-9). The dataset is loaded from a CSV file, which can be accessed from the following URL: digits.csv.

## Dependencies
The code requires the following dependencies:

1. numpy - for numerical computations on arrays
2. matplotlib - for visualization of images and plots
3. pandas - for data manipulation and loading the dataset
4. scikit-learn - for machine learning algorithms and evaluation metrics

These dependencies can be installed using pip with the following command:
```
 pip install numpy matplotlib pandas scikit-learn
```
## Usage
1. Clone the repository or download the code files.
2. Install the required dependencies mentioned above.
3. Run the script or execute the code in your preferred Python environment.
4. The code will load the dataset, split it into training and testing sets, and train an MLPClassifier using default parameter values.
5. The accuracy of the model on the test set will be printed.
6. RandomizedSearchCV is then utilized to find the best combination of hyperparameters for the MLPClassifier. The search is performed using a reduced training set size to shorten the training time.
7. The best parameter values found by RandomizedSearchCV are printed.
8. The best model is stored in a variable called *bestmodel*.
9. The accuracy score of the best model is calculated and printed.
10. A figure shows randomly selected images from the test set, along with their corresponding predictions made by the best model.

## Results
The README file provides an overview of the code and its usage. The code performs image classification on the handwritten digit dataset using an MLPClassifier. It demonstrates the improvement in model performance achieved by tuning hyperparameters with RandomizedSearchCV.

The code can serve as a starting point for understanding image processing and classification tasks using MLP algorithms. It also highlights the importance of hyperparameter tuning for achieving better model performance.

Feel free to explore the code, experiment with different hyperparameters, and adapt it for your own image-processing projects!
