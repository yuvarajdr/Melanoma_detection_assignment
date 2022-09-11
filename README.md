# Melanoma_detection_assignment

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- Find the distribution of classes in the training dataset.
- **['actinic keratosis', 'seborrheic keratosis', 'pigmented benign keratosis', 'squamous cell carcinoma', 'vascular lesion', 'basal cell carcinoma', 'dermatofibroma', 'melanoma', 'nevus']**
-  Which class has the least number of samples?
-  **seborrheic keratosis has least number of samples**
- Which classes dominate the data in terms proportionate number of samples?
- **pigmented benign keratosis dominate the data in terms proportionate number of samples**
- Rectify the class imbalance -> **Rectified by usng Augmentor pipeline**

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- overfitting model can be reduced by adding layers 
- adding filters with padding
- adding drooput layers
- Classes are imbalance so we have to use data augmentation for balancing classes

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- tensorflow 
- PIL 
- Augmentor 

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
- This project was based on [tensorflow tutorial](tensorflow.org/tutorials/load_data/images).


## Contact
Created by [@yuvarajdr] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
