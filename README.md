Cassava Disease Classification
This project uses deep learning to classify cassava leaf images into three categories: Cassava Brown Streak Disease (CBSD), Cassava Mosaic Disease (CMD), and Healthy. The model is trained on RGB images, resized to 128x128 pixels, and leverages a convolutional neural network (CNN) built with TensorFlow/Keras.

Features
-Loads and preprocesses cassava leaf images from local directories
-Trains a CNN to distinguish between CBSD, CMD, and healthy leaves
-Saves the trained model for future predictions
-Allows prediction on new images without retraining

Usage
-Place your cassava images in the specified folders (cbsd, cmd, healthy).
-Run the notebook to preprocess data, train the model, and save it.
-Use the prediction cell to load the saved model and classify new images.

Requirements
-Python 3.x
-TensorFlow
-NumPy
-OpenCV
-Matplotlib
-Pillow