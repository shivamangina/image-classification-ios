#  image-classification on on  webrtc

pytorch projects
 
this repository is build using uv. you should have the uv already installed.

```
To create the enviromne to run the code
uv venv --python 3.10

# to activate the enviroment
uv venv --python 3.10

# to run the jupiter server
jupyter lab

# to install new package
uv pip install pytorch
```




## Data collection

we are using a kaggle data set https://huggingface.co/datasets/Nattakarn/fruit-and-vegetable-image-recognition

1. Preprocess the image data using Keras
2. Visualize the data using Matplotlib
3. Split the dataset into train, validation and test sets
4. Shuffle and prefetch for performance
5. Creating a Layer for Resizing and Normalization
6. Image Augmentation


## convolutional neural network

1. build and train the model
2. evaluate the model and get the accuracy and loss
3. Make a graph of the accuracy and loss
4. save the model

<!-- I will complete this model today -->

## run the model
1. run the model using the torch.serving and fastapi
2. create a /predict endpoint to predict the image that take the image data as an imput and returns the prediction

## deploy the model on the 
1. deploy the model in the aws sagemaker






