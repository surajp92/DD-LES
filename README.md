# DD-LES
This repository contains codes for different machine learning algorithms for two-dimensional Kraichnan turbulence. We investigate decision tree regreesor, random forest regressor, feedforward neural network, and convolutional neural network in this study.  

### A top-level directory layout

    .
    ├── data_spectral    # data for training and testing (Fine grid = 1024 x 1024, coarse grid = 64 x 64)
    ├── ml_codes         # Codes related to decision tree, random forest, and neural network (ANN, CNN) 
    ├── spectral_solver  # Spectral solver codes for 2D decaying homegenous turbulence problem
    ├── LICENSE
    └── README.md

### Required python packages:
- Numpy, SciPy, Matplotlib
- scikit-learn, Keras, Tensorflow 
