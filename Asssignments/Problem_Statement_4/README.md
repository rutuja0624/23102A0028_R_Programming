# Image Classification using R and Keras

## Objective

The objective of this project is to implement an image classification model using R programming, EBImage and Keras. The project processes images, resizes them, prepares training and testing data, builds a neural network and evaluates its classification performance.

## Problem Statement

The project demonstrates image classification using a neural network. Images belonging to two classes are processed and used to train a classification model.

## Dataset

The dataset consists of 12 images belonging to two classes.

- Training images: 10
- Testing images: 2
- Image size: 28 × 28 × 3
- Number of classes: 2

## Technologies Used

- R Programming
- RStudio
- Keras
- TensorFlow
- EBImage
- Git
- GitHub

## R Packages Used

- EBImage
- keras3
- tensorflow
- reticulate

## Methodology

1. Read the input images.
2. Explore the images using R.
3. Resize images to 28 × 28 pixels.
4. Reshape the image data.
5. Prepare training and testing datasets.
6. Perform one-hot encoding of labels.
7. Build a sequential neural network.
8. Train the model for 30 epochs.
9. Evaluate the model on training data.
10. Evaluate the model on test data.
11. Generate predictions and compare predicted and actual classes.

## Model Architecture

- Input: 2352 features
- Dense layer: 256 neurons, ReLU
- Dense layer: 128 neurons, ReLU
- Output layer: 2 neurons, Softmax

## Training Configuration

- Epochs: 30
- Batch size: 32
- Validation split: 20%
- Optimizer: RMSprop
- Loss function: Binary Crossentropy
- Metric: Accuracy

## Results

The model was successfully trained and evaluated. Training and validation accuracy/loss were visualized using the training history plot. Predictions were also compared with actual class labels using a confusion table.

## How to Run

1. Install R and RStudio.
2. Install the required R packages.
3. Place the images in the project image folder.
4. Open the R project in RStudio.
5. Open `YT_R_PROJECT.R`.
6. Run the complete script.
7. Observe the training graph and prediction results.

## Conclusion

The project successfully demonstrates an end-to-end image classification workflow using R and Keras, including image preprocessing, neural network training, evaluation and prediction. The project was also maintained using Git and published on GitHub.