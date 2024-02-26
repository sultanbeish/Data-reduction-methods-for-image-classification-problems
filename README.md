# Data-reduction-methods-for-image-classification-problems
Image recognition is very popular problem of identifying images and categorizing them in one or several predefined distinct classes. Digital images usually require a very large number of bits, this causes critical problem for digital image data transmission and storage. Image compression is an application of data compression that encodes the original image with few bits. The objective of image compression is to reduce the redundancy of the image. Main goal of the project is to implement two data reduction techniques such as PCA and Wavelet and compare them between each other in terms of image classification problem (cat vs dogs). 

Hypothesis:
In this project we use two reduction methods (PCA and Haar Wavelet transform) with image classification. Our hypothesis is: reduction methods increase efficiency of image classification model. In other words we expect that the accuracy of classification will increase and the time performance will decrease without significant loss of information after implementation the reduction methods.

Conclusion:
Our proposed hypothesis says that reduction methods will increase efficiency of the classification. This hypothesis was tested for both reduction methods. 
 it can be said that: 
Reduction methods did not increase the classification accuracy, however classification with PCA is more accurate than with Wavelet. (0.98)
Wavelet reduction methods is the best one in terms of time performance (1.29).
With our configurations the resulted output shows the influence of reduction methods on the size of the dataset that we choose. The change of the size of dataset might change the output and needs in further investigation.
