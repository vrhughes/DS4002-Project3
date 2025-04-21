# DS4002-Project3
Group 13's (Avery, Dana and Viv) repository for our third project in DS 4002.

## Data:
https://www.kaggle.com/datasets/puneet6060/intel-image-classification/data

## Goal
The goal of this project is to build a satellite image classification model that can differentiate between landscapes (buildings, mountain, sea, forest, glacier) using the TensorFlow package that includes Keras which contains the pre trained convolutional neural network (CNN) VGG16. Can our model achieve an accuracy above 90% when differentiating between the 5 landscapes? We will implement the optimizer Adam and calculate the accuracy of our model to determine if we have reached our goal.

## Software/Platform
We are using Jupter Notebooks for this program that run on Python 3 (prefferably 3.10+). Our code can be run on Google Colab by importing our notebooks from the SCRIPTS folder. All files will need a Python environment with some or all of the following packages: Pandas, Numpy, Matplotlib, Seaborn, TensorFlow, Keras, glob, os, and PIL. All files will need support for Jupyter Notebooks and can be run on Windows, Linux, or Mac.

## Documentation
The files and folders are broken down into this structure:
```
- root
  -- OUTPUTS
    -- .gitattributes
    -- epoch15_model.keras
  -- SCRIPTS
    -- 15epoch.ipynb
    -- SingleEpochVGG16.ipynb
    -- VGG16.ipynb
    -- VGG16_2epochs.ipynb
    -- VGG16_cleaning.ipynb
  -- README.md
  -- LICENSE.md
```
The SCRIPTS folder contains multiple Jupyter Notebooks that have been used to clean and analyse the data, run the VGG16 models with varying amounts of epochs, create graphs, and do error analysis. The OUTPUT folder contains generated models from SCRIPTS.

## Steps to Reproduce
To reproduce the results of the project you must clone the repo with the following command: `` git clone https://github.com/vrhughes/DS4002-Project3 ``` Then you can use the link from above in the "Data" section of the README to see the data you will be working with. The data does not need to be downloaded, instead you can just access it as shown in the scripts. The VGG16.ipynb and VGG16_cleaning.ipynb notebooks are what we first used to play with the data, but they did not end up producing anything, so you could first take a look at those. Next, you would move on to the SingleEpochVGG16.ipynb file and run a single epoch VGG16 model and see the accuracy it has. Second, you would move on to the VGG_2epochs.ipynb script and do the same to see how the model improves with a second epoch. Lastly, you would run the 15epoch.ipynb script to get the finished model (epoch15_model.keras) and analyze the graphs and tables to see how you did.

1. VGG16.ipynb
2. VGG16_cleaning.ipynb
3. SingleEpochVGG16.ipynb
4. VGG16_2epochs.ipynb
5. 15epoch.ipynb

## References and Example Code
- https://www.kaggle.com/code/avikumart/computervision-intel-image-classification-project
- https://www.kaggle.com/code/mhmmadalewi/transfer-learning-vgg16-acc-87-5
- https://www.kaggle.com/code/tawfikelmetwally/intel-images-classifier-vgg16
- https://www.kaggle.com/code/janvichokshi/transfer-learning-cnn-resnet-vgg16-iceptionv3
- [1] Satellite Imaging Corporation, "Natural Disasters - Environmental Impact Studies," Satellite Imaging Corporation, [Online]. Available: https://www.satimagingcorp.com/applications/environmental-impact-studies/natural-disasters/. [Accessed: 07-Apr-2025].
