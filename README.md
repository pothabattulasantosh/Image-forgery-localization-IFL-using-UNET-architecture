# Image-forgery-localization-IFL-using-UNET-architecture
This is the one of solution implemented for image forgery localization using deep learning techniques and architectures such as UNET, VGG  
### 1. Understanding the problem
#### 1.1 Problem Statement:
1. As there are a lot of software tools available for modifying authenticated digital content such as images or videos that leads to spread manipulated information across digital medium, which is also a one of the main reasons for losing the trust against the digital content.
2. On considering this problem, we can address the solution using some Artificial Intelligence techniques, as there is already active research at this particular area, we can find many exciting solutions to detect given image is manipulated or not, however this approach cannot ensure that which regions in the image are manipulated.
3. Realizing this, we are going to build the model so that it can predict manipulated regions at pixel level which is a little more advanced than the normal image classification.
#### 1.2 Objective
We need to build a model such that for a given any image it should predict the manipulated regions.
#### 1.3 Data Source
To train and test the algorithms I am considering IEEE IFS-TC Image Forensics Challenge data that has both authenticated and manipulated images.
For every manipulated image we have its corresponding maks that contain only white and black color pixels.
For more understanding of the data, please refer the follwoing link http://web.archive.org/web/20171013200331/http:/ifc.recod.ic.unicamp.br/fc.website/index.py?sec=5

### Files Description
#### 1. IFL_Part01.ipynb 
This file contains EDA part, Data manipulation part, Modeling part
#### 2. IFL_Part02.ipynb
This file contains modeling with VGG16+UNET architecture. 
