# Machine Learning Engineer Nanodegree
## Capstone Project: Dogs vs. Cats Redux 

### Install

* Python 3
* TensorFlow
* NumPy
* SciPy
* matplotlib

### Code

4 files are included for this project

1. Dogs_vs_Cats_Data Exploration.ipynb
2. Dogs_vs_Cats_Data Preprocessing & Export.ipynb
3. Dogs_vs_Cats_LeNet_Baseline.ipynb
4. Dogs_vs_Cats_CNN_Model.ipynb

### Run

In a terminal or command window, navigate to the top-level project directory `Capstone Project/` (that contains this README) and run one of the following commands:

```bash
ipython notebook Dogs_vs_Cats_Data Exploration.ipynb
```  
or
```bash
jupyter notebook Dogs_vs_Cats_Data Exploration.ipynb
```

This will open the Jupyter Notebook software and project file in your browser.

### Data

The dataset could be downloaded from (https://www.kaggle.com/c/dogs-vs-cats-redux-kernels-edition/data). The orginal training folder contains 25,000 images, only 2,500 images in training folder are used in this project. Download and unzip the training folder, manually pick the first 1,250 images labeled from 0 to 1249 for dog and cat.

1,250 dog images: dog.0.jpg to dog.1249.jpg
1,250 cat images: cat.0.jpg to cat.1249.jpg

After putting these 2,500 images into a new folder and compress it as zip format, since in Dogs_vs_Cats_Data Preprocessing & Export.ipynb and Dogs_vs_Cats_Data Exploration.ipynb, zip format is used as input.