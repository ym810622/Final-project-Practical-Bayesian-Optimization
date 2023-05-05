# Final-project-Practical-Bayesian-Optimization
Final project of ECE50024 Purdue University-Cheng_Han_Yang

The GaussianProcess.ipynb demonstrate how the predicted mean and covariance change according to prior. 
Inside this file is an 1-D function example.

Acquisition_function.ipynb shows how Bayesien optimization suggest the next point to evaluate. 
The example function is the same as  GaussianProcess.ipynb.

Integrated_Expected_Improvement.ipynb demonstrates the behaviors of different hyperparameter sets in convariance function.
Also demonstrates the difference between each acquisition funcrion and the integrated one.

branin_hoo_example_sklearn.ipynb is the main experiment in the final report, which apply most of the concepts of Bayesian optimization
idea proposed in the paper to optimize the Branin-Hoo function. It compares the behaviors of different kernels and acquisition functions.
