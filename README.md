# LARP_Assignment
Linear Algebra Assignment 1
 CS-6015 Linear Algebra and Random Processes July – Nov 2017 Programming Assignment-1
Date : September 21, 2017
Deadline for submission of PDF file of report: 7 PM, Friday, October 6, 2017

Q1. Write programs to
a. Find the projection matrix Pc onto the column space of matrix A
b. Find the 3x3 projection matrix PR onto the row space of A. Multiply B = PCAPR. Your answer B should be a little surprising -- Can you explain it?

Q2. You are given eigen vectors matrix in the image space and a set of 10 grayscale images.

a. For each image, plot the intensity histogram. The intensity histogram of an image is a
histogram that shows the number of pixels in an image at each different intensity value
found in that image.

b. Convert the basis to images and plot the same. The basis are same as the set of eigen
vectors given

c. For each image, project image onto the eigen space and find the top K (K<8464)
directions such that the relative error(frobenius norm) is < 1% for reconstruction of image using these eigenvectors.
Refer this link for eigen space

The Frobenius norm is a matrix norm of an m×n matrix A is defined as the square root of the sum of the absolute squares of its elements,
Data:

1. EigenVectors.mat: Contains the eigen basis for the image space. Common for all the groups. 2. Set of 10 images: The images for your team is in folder s[team Number].
Prepare and submit a report with the answers to the problems above by Oct 5, 4 pm. You could use MATLAB or Python or Octave to solve the problems. The submitted report should contain (i) solutions for question 1a-b (ii) intensity histograms and Frobenius norm plots for question 2a-c. In addition, the code used to solve Q2 should accompany the report.
There will be an oral exam after the deadline, where the team will be quizzed on the results submitted in their report. So, be prepared to justify the conclusions drawn for each of the problems.
     
