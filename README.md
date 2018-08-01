# HandWritten-Digit-Recognition
A python based Machine-Learning program based on SVM (support vector machine) algorithm, to recognize hand written digits.


# Teach a Neural Network to Read Handwriting
   # (Sachin Kumar Sharma)

# *Abstract
Handwritten character recognition (HWCR) is the ability of a computer to receive and interpret intelligible handwritten input from source such as paper documents, photographs, touchscreens and other devices. There are many devices now can take handwriting as an input such as smartphones, tablets and PDA to a touch screen through a stylus or finger. This is useful as it allows the user to quickly write down number and text to the devices.
In this internship, I have made a neural network that will read and recognise the digits based on MNIST digit dataset. I have used one of the widely used algorithms, SVM (Support Vector Machine).

# *Advantages of using SVM
  1.	Support Vector Machine gives a high accuracy of 97.91%, whereas other Machine Learning algorithm had lesser accuracy
  2.	Support vector machines are naturally resistant to overfitting and work very well when identifying boundary regions.
  3.	Robust to noises.
  4.	Easier to implement, personally I feel it is easier for me to implement SVM classifier.
  5.	The advantage of SVM is that once a boundary is established, most of the training data is redundant. All it needs is a core set of         points which can help identify and set the boundary.

# *Implementation
1.	Unzip the folder. The four MNIST data file are already downloaded and stored into a folder named HandWritten-digit-recognition. 
2.	Navigate to: Handwritten-Digit-Recognition\\ SVM and run the following python command >>python svm.py
3.	Once the execution begins, the program loads the MNIST data which includes both training and testing data. It prepares the                 classifier and also plots a confusion matrix.
4.	Apart from the confusion matrix it also tells us about predicted labels for test images and accuracy of classifier on test images.
5.	In the end, it shows the Test Images with Original and Predicted Labels.
