# Deep Learning and Computer Vision Projects

There are two deep learning and computer vision projects in this repository.

Project 1 is about binary image classification task and benchmark of deep learning architectures.

## Project 1 (Benchmark of Deep Learning Architectures)

### STEP 1: BICYCLE CLASSIFICATION - DATA EXPANSION AND MODEL COMPARISON

#### Task Description: 
In this project, it is expected to develop a simple image classification model using the FastAI library. 
This model should be able to distinguish two classes, "bicycle" and "non-bicycle". Using the Fastai library, collect bicycle images from search engines. 
Save these pictures in a folder called bikes. Then, collect images that do not contain bikes and save them in another folder called not_bikes. 
Keep these two folders under a folder called data. Expand your initial data set by duplicating these images in various ways (data augmentation). 
Then, use different deep learning models (e.g. ResNet, VGG, like CNN architectures) on this extended dataset and analyse which one performs better. 
Calculate the accuracy and loss function of your model. 
To demonstrate the performance of your model, perform an application showing your model's predictions and the actual labels on a few randomly selected images.

### 1.1 Data Collection and Augmentation

Collecting bicycle images from search engines using automated scripts. 
Bing Search API or Google Custom Search API or Unsplash API or Flickr API etc. 
It is expected to collect data with an API. These images should be collected in a folder named bikes. 
Thus, all data under this folder will be considered to be labelled as bikes. Please verify that the images in this folder are bicycle images. 
There may be errors in the images collected from search engines, or data labelled as bicycles when they are not bicycles, and these should be manually weeded out.

Collecting images of various non-bicycle objects in the same way. 
The names of the objects that are not bicycles should be realised by giving the appropriate keywords for the API to be used. 
The collected images should be stored in a folder named not_bikes. It is necessary to make sure that there are no bicycle images in this data.

Enrich your training dataset by using a data augmentation technique. 
This technique helps your model adapt to more diverse data by applying arbitrary rotations to existing images. 
The Fastai library supports a variety of transformations such as resizing, rescaling, rotating, mirroring, adjusting brightness and contrast of images. 
Observe how the data replication technique affects the accuracy of your model.

### 1.2 Model Selection and Development

#### Task Description:

In this phase, you will build a classification model using the collected data. 
The FastAI library and Python programming language will be used. 
You will experiment with different deep learning architectures (such as ResNet, VGG) to determine which one is most suitable for this task.

#### Stages:

#### Model Creation:
Using the FastAI library, create classification models with various deep learning architectures.
Determine the starting point of your model using pre-trained networks.

#### Model Training:
Train your model using collected and processed data.
Optimise the performance of your model by adjusting hyperparameters (e.g. learning rate, batch size) during the training process.

#### Architecture Comparison:
Compare the performance of different architectures such as ResNet, VGG, and Inception.
Evaluate the advantages and limitations of each model.

### 1.3 Evaluation of Results

#### Task Description:
In this phase, you will evaluate the performance of the models you have developed. 
You will use the model's accuracy, error rate and other performance metrics to determine the model that gives the best results.

#### Stages:

#### Performance Metrics:
Calculate metrics such as accuracy, error rate, precision and recall for each model.

#### Analysing the Results:
Analyse the comparison results to determine which model architecture and data augmentation method is most effective.

#### Plot:
Draw plots showing the model's predictions and the actual labels.
Visually present the model's successes and shortcomings so that you can better understand the model's performance.
