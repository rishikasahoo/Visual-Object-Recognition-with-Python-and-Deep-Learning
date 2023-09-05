# Visual-Object-Recognition-with-Python-and-Deep-Learning

This Jupyter Notebook provides a walkthrough of a visual object recognition project using Python and deep learning techniques.

## Installation and Configuration

1. **Install the Kaggle Library:** Ensure you have the Kaggle library installed to facilitate dataset acquisition.

2. **Configure the Kaggle.json File:** Set up your Kaggle API credentials by adding them to the `kaggle.json` file.

## Importing and Preprocessing Data

3. **Importing Datasets from Kaggle:** Use the Kaggle API command (assuming you have an API token) to import datasets. Execute the command using an exclamation mark.

4. **Creating Lists and Labels:** Create lists to store files with and without masks, and assign labels (1 for masks, 0 for without masks) to each image.

5. **Display Images:** Display both masked and without-masked images by specifying their paths.

6. **Converting Images to Numpy Arrays:** Convert the images to numpy arrays, resulting in three matrices representing the red, green, and blue intensity values. The dataset comprises 7553 images in the form of numpy arrays.

7. **Train-Test Splitting:** Split the dataset into training and testing sets.

8. **Scaling the Data:** Scale down the RGB values, ensuring white is represented as 1 and black as 0. All values should lie between 1 and 0.

## Building the Convolutional Neural Network

9. **Building the CNN:** Construct a Convolutional Neural Network for object recognition.

## Training the Neural Network

10. **Training the Model:** Train the neural network using the prepared dataset.

## Loss and Accuracy Visualization

11. **Visualizing Loss and Accuracy:** Plot loss and accuracy curves to assess the model's performance.

## Predictive System

12. **Building a Predictive System:** Create a system for making predictions based on the trained model.
