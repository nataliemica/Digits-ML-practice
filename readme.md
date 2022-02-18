# About this project
This project is working with the digits dataset from the `sklearn` package to practice machine learning with it. 

The data from this practice set looks like:

![handwritten_numbers](digits_images.png "Handwritten numbers with their target values")

The target values for each handwritten number appears in the top left of each box. 

My first attempts at handling the data were to lower the dimensionallity of it using Principal Component Analysis (`PCA`). However, reducing the dimensions of the problem down from 64 to 2 loses too much information from the original set - as can be seen by the very low variance ratio. This is a massive reduction, so perhaps not very surprising.

More to come on this project.