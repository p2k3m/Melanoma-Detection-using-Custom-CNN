# Melanoma Detection using Custom CNN

## Project Overview
This project involves building a Convolutional Neural Network (CNN) from scratch to accurately detect melanoma, a type of skin cancer, using image data. Melanoma is a deadly form of skin cancer responsible for 75% of skin cancer deaths. Early detection through automated image analysis can significantly reduce the manual effort required by dermatologists and improve diagnosis rates.

## Objective
- Develop a custom CNN model without transfer learning to classify images into 9 distinct classes.
- Provide a reliable image classification model that can assist in early diagnosis of melanoma.

## Dataset
- The dataset consists of training and test images categorized into 9 classes.
- Images have been resized to 180x180 pixels for model training.
- The dataset has been split into training and validation datasets with a batch size of 32.

## Project Workflow
### 1. Data Loading and Understanding
- Defined paths for train and test datasets.
- Images loaded and visualized for better understanding.

### 2. Dataset Preparation
- Created training and validation datasets using a batch size of 32.
- Applied image resizing to 180x180 pixels for consistency.

### 3. Dataset Visualization
- Visualized samples from each of the 9 classes to understand data distribution.

### 4. Model Building & Training
- Built a custom CNN model with multiple convolutional layers.
- Defined an appropriate optimizer (Adam) and loss function (categorical cross-entropy).
- Trained the model for 20 epochs.
- Identified signs of overfitting and underfitting with training metrics.

### 5. Data Augmentation
- Applied data augmentation techniques (flipping, rotation, and zoom) to address overfitting issues.

### 6. Class Distribution Analysis
- Analyzed class distribution and identified imbalances.
- Implemented strategies to address class imbalance using the `Augmentor` library.

### 7. Model Evaluation
- Evaluated the model on validation data.
- Compared performance metrics before and after augmentation.

## Technologies Used
- Python
- TensorFlow/Keras
- Augmentor
- Matplotlib
- Google Colab (for GPU runtime)

## Results
- The final model was able to classify the 9 melanoma-related classes effectively after augmentation.
- Class imbalance was addressed, and model performance improved post data augmentation.

## Key Findings
- Initial model faced overfitting, which was resolved using data augmentation.
- The data distribution was skewed, and handling imbalance improved the accuracy.

## How to Run the Project
1. Download the dataset using the provided link.
2. Open the Jupyter Notebook (`your_name_nn.ipynb`) in Google Colab.
3. Ensure a GPU runtime is selected.
4. Run all cells sequentially.

## Acknowledgements
- This project was developed as part of a learning assignment.
- Inspired by CNN-based image classification tasks.

## Contact
Created by [Pushkar Mishra] - Feel free to contact me!
