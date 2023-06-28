# human-activity-recognition
Human Activity Recognition (HAR) Dataset Analysis and Prediction

This repository contains three Jupyter Notebook files that focus on the analysis and prediction of human activities using the Human Activity Recognition (HAR) dataset. The dataset consists of readings from accelerometer and gyroscope sensors in a smartphone, recorded while 30 subjects performed various activities.

File Descriptions:

HAR_EDA.ipynb: This notebook provides an exploratory data analysis (EDA) of the HAR dataset. It includes visualizations and statistical summaries to gain insights into the dataset's structure, distributions, and relationships between variables. The EDA helps in understanding the data before applying machine learning algorithms.

Har_prediction_ml_models.ipynb: In this notebook, various machine learning models are built and trained to predict human activities based on the features extracted from the accelerometer and gyroscope data. The notebook covers preprocessing steps, feature selection, model training, evaluation, and comparison of different algorithms.

har_simple_neural_network.ipynb: This notebook explores the application of a simple neural network model for human activity prediction. It demonstrates the implementation of a basic neural network architecture using a deep learning framework and evaluates its performance on the HAR dataset.

Dataset Information:

The dataset consists of the following:

Sensor readings (accelerometer and gyroscope) captured from a smartphone worn on the waist of 30 subjects.
Activities recorded include Walking, Walking_Upstairs, Walking_Downstairs, Sitting, Standing, and Laying.
Readings are sampled in fixed-width windows of 2.56 seconds with a 50% overlap, resulting in 128 readings per window.
Features are derived from time and frequency domains, such as mean, standard deviation, median absolute deviation, maximum, minimum, energy, entropy, etc.
Repository Usage:

To replicate the analysis and prediction tasks:

Clone the repository to your local machine.
Ensure you have Jupyter Notebook or JupyterLab installed.
Open the desired notebook (HAR_EDA.ipynb, Har_prediction_ml_models.ipynb, or har_simple_neural_network.ipynb) in Jupyter.
Follow the instructions within the notebooks to execute the code cells and understand the analysis steps.
Make sure to have the HAR dataset files available in the correct directory as mentioned in the dataset description section.
Note: The notebooks assume a basic understanding of Python, data analysis, and machine learning concepts. It is recommended to have the required Python libraries (e.g., NumPy, Pandas, Matplotlib, scikit-learn, TensorFlow, etc.) installed beforehand.

Contributing:

Contributions to this repository are welcome. If you find any issues or have suggestions for improvements, feel free to open an issue or submit a pull request.

License:

The code provided in this repository is available under the MIT License. Please see the LICENSE file for more details.

Contact:

If you have any questions or need further assistance, please feel free to contact the repository owner.

Thank you for your interest in this project!
