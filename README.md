# Sharpest_Minds
Entry to the Sharpest Minds program 

#Photo caption generator

Dataset: Flickr8k dataset, descriptions

Requirements:
Python 3.0+
Keras 2.1.2+
Sk-learn
matplotlib
numpy

Description:
Aim is to generate photo caption given a picture database and picture description database. 

About:
For photo data preparation, a pre-trained VGG model is used. The last layer is removed which is the one used for classification.

To run:
First run the caption_gen_load.py file in order to build the model, evaluate it
Next, run the caption_gen_standalone.py file to execute a standalone example for caption generation
