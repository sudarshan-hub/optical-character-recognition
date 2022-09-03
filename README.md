# Optical-Character-Recognition

Optical Character Recognition (OCR) is a method for extracting text from images and turning it into machine-readable text that programmers can access and alter as a string variable (or any other computer language). However, using OCR, the image can be converted into a text file and its constituent parts recorded as text data.

## Dataset used
MNIST is the “Hello World” dataset for computer vision (“Modified National Institute of Standards and Technology”). Since its 1999 publication, this well-known collection of handwritten images has served as the standard for categorization algorithms. Even as new machine learning techniques are created, MNIST remains a reliable resource.

The data set consists of 10,000 test images and 60,000 training images. The data is separated into training and testing datasets in this case. The x_train and x_test employ grayscale codes, while the y_test and y_train employ labels that list the digits 0 through 9. You can tell if a dataset can be used with CNN by looking at its form. You can see that our result is (60000,28,28), meaning that there are 60000 images in our collection, each of which has a size of 28×28 pixels. To use the Keras API, we need a 4-dimensional array, however as the image above shows, we only have a 3-dimensional numpy array.
