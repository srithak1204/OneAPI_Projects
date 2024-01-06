# OneAPI_Projects
This repository contains projects that are made using Intel OneAPI services
## cnn_animals.ipynb
This project implements a Convolutional Neural Network (CNN) for classifying images of animals. The goal is to accurately identify different animal species from input images using deep learning techniques.
### Features
- **Animal Species Classification:** The CNN is capable of accurately classifying images of various animal species, including cats,dogs and pandas.

- **Multi-Class Classification:** The model is trained to classify images into different categories, allowing it to distinguish between cats, dogs, and pandas.

- **Customizable:** The project is designed to be adaptable to different datasets, making it easy to extend the classification capabilities to include additional animal categories.
### Data
The dataset used for training and testing the model consists of images of various animal species. You can find the dataset from [Dataset Link](https://www.kaggle.com/datasets/sohampatel26/animal-detection-dataset-cats-dogs-and-pandas/download?datasetVersionNumber=1). Ensure the dataset is appropriately labeled for optimal results.

### Model Architecture
The CNN architecture used for this project consists of multiple convolutional and pooling layers, followed by fully connected layers. The details of the model architecture can be found in the notebook.
### Results
#### Model Performance
An overview of the model's performance:
- Training Accuracy: 100%
- Validation Accuracy: 70.33%
- Test Accuracy: 69.33%

### Jupyter Notebook
Explore the implementation details and code in the [Jupyter Notebook](https://github.com/srithak1204/OneAPI_Projects/blob/main/cnn_animals.ipynb).
### Usage
To view the Jupyter Notebook in a read-only format, click on the [Jupyter Notebook](https://github.com/srithak1204/OneAPI_Projects/blob/main/cnn_animals.ipynb) link. 
### Visualizations
- **Training Loss Curves:**

![Loss Curves](https://github.com/srithak1204/OneAPI_Projects/blob/main/image.png)

### Benefits of oneAPI Integration

- **Unified Programming Model**: oneAPI provided a unified programming model, allowing seamless integration of diverse hardware accelerators, streamlining development for both CPUs and GPUs in my animal CNN project.
- **Optimized Performance**: Leveraging oneAPI's performance libraries and optimizations significantly improved the computational efficiency of my CNN model, resulting in faster training and inference times.

- **Cross-Accelerator Portability**: With oneAPI, I achieved cross-accelerator portability, enabling my animal CNN to run efficiently across different hardware architectures without the need for extensive code modifications.

