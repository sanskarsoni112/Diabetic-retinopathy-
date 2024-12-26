# Diabetic-retinopathy-
Overview
This project is a Diabetic Retinopathy Detection System designed to assist in the early detection of diabetic retinopathy through the analysis of retinal images. The system utilizes deep learning techniques, specifically transfer learning with the ResNet50 model, to classify images and determine the presence of diabetic retinopathy. The project achieved an accuracy of 85.6% on the validation dataset.

Features
Image Preprocessing: Includes steps for image enhancement and normalization.
Deep Learning Model: Utilizes ResNet50 with transfer learning for accurate image classification.
Performance Metrics: Achieved 85.6% accuracy on the validation dataset.
User-Friendly Interface: Easy to use for medical professionals and researchers.
Technologies Used
MATLAB: For image processing and model implementation.
Deep Learning Toolbox: For developing and training the deep learning model.
ResNet50 Model: Pre-trained model used for transfer learning.
Image Processing Techniques: To enhance and prepare images for the model.
Project Structure
├── data/                  # Directory for storing dataset images
├── models/                # Directory for storing the trained model
├── scripts/               # MATLAB scripts for training and evaluation
│   ├── preprocess.m       # Script for image preprocessing
│   ├── train_model.m      # Script for training the ResNet50 model
│   ├── evaluate_model.m   # Script for evaluating the model
├── results/               # Directory for storing output results
│   ├── accuracy.png       # Accuracy plot
│   ├── confusion_matrix.png  # Confusion matrix of the model
└── README.md              # Project documentation
Installation and Setup
Clone the Repository
git clone https://github.com/yourusername/Diabetic-Retinopathy-Detection-System.git
cd Diabetic-Retinopathy-Detection-System
2.Download the Dataset

Download the retinal image dataset and place it in the data/ directory.
3.Run the Preprocessing Script

Execute preprocess.m to prepare the images for training.
4.Train the Model

Run train_model.m to start training the ResNet50 model.
5.Evaluate the Model

Use evaluate_model.m to assess the performance of the trained model.
Results
Accuracy: 85.6% on the validation dataset.
Confusion Matrix
