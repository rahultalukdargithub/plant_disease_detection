# Tomato Plant Disease Detector:
# Overview :

This project aims to detect diseases in tomato plants using leaf pictures. The detection is accomplished through a Convolutional Neural Network (CNN) model. The CNN architecture is structured as a sequential model, involving resizing and rescaling of images, five 2D convolutional layers, and corresponding MaxPooling layers.

# CNN Architecture :
The CNN model follows a sequential structure, starting with an initial layer featuring 32 filters and a (3, 3) kernel, using the rectified linear unit (ReLU) activation function. Subsequent convolutional layers progressively increase the filter count to 64, maintaining ReLU activation. MaxPooling layers contribute to spatial down-sampling, and a Flatten layer precedes the final dense layers.

In the initial dense layer, 64 neurons are employed with ReLU activation, while the output layer uses the softmax activation function for disease classification. The model was trained with a batch size of 16.

# Training Results:
The trained model achieved an impressive accuracy of 97%, showcasing its effectiveness in identifying tomato plant diseases based on leaf images.

# Usage
To use the Tomato Plant Disease Detector:

Dataset: Make sure you have a suitable dataset of tomato plant leaf images for training and testing the model.

Training: Train the CNN model using the provided architecture and parameters on your dataset.

Testing: Evaluate the model's performance on a separate test set to ensure its accuracy.

Integration: Integrate the trained model into your application or system for real-time disease detection.

# Contributing
Contributions are welcome! If you find issues or have suggestions for improvements, please feel free to open an issue or submit a pull request.
