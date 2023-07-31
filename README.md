# Classifying Images based on Deep learning CNN Algorithm

## Pepper Bell Leaf whether it’s Diseased or Healthy!

| Model:- Classification | Domain:- Agricultural Industry | Internal Decisions |

## Data Collection, Pre-processing :

- In this project we have used ready-made data from Kaggle for training.
- The dataset was downloaded and the directory was named as "PlantVillage".
- We launched GitBash which allows us to run all the unix command, which inturn launched Jupyter notebook.
- To download the dataset into tf dataset TF data input pipeline, followed by data cleaning and we made our dataset ready for Model Training.
- Essential modules were downloaded.
- We used Tensorflow dataset to download all the images into tf.data.dataset .
- We created couple of constants such as Image_size, Batch_size, Channels and EPOCHS .
- We split our data into Train and Test.
- 80% of the data was kept as Training Data.
- 20% of the data was split into 10% Validation and 10% Test.
- Here 10% of the data used for test is used to check the accuracy of our model.
- We let Tensorflow determine how many batches to load while GPU is training.
- Dataset were optimised for Training performance such that training will run fast.
- We supplied preprocessing pipeline using an API which would scale the image.
- All the image dimensions were resized to 256 by 256, which is followed by Data augmentation to make our model robust.

## Model Building:

- We trained Convolutional Neural Network in Tensorflow using bell_pepper leaf images. The goal of this model would be to classify these images either healthy or Bacterial spot disease.
- We built a trained CNN model.
- Plotted training history on the graph.
- Made predictions/inference on sample images.
