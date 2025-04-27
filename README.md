# Self-Organizing Map of Handwritten Digits
This notebook is an exercise to gain familiarity with the applications and functions of self-organizing maps (SOMs). The scikit-learn package for SOMs is applied to an MNIST database of handwritten digits to visualize a reduction in dimensionality from 784 features to 2. The goal of this exercise is to explore the visualization and predictive power of the SOM algorithm.

For an intuitive visualization of how the algorithm organizes the data, I have created a grid of images that correspond to the nodes of the self-organizing map. Each of these images are an average of all the images closest to the corresponding node in the map space. This visualization shows an intuitive grouping of similar images. For example, most of the images with a narrowly drawn digit (such as the 1's) were placed in the bottom-right corner of the map space by the algorithm. 
![image](https://github.com/user-attachments/assets/535a0302-59d3-47c9-9b5b-7a328c55ce6b)
