# Transfer-Learning-Project-Pneumonia-Detection-from-Chest-X-Rays
- This is a project completed during the Udacity's AI in Healthcare Nanodegree programme.
- In this project I exhibit how to utilize Transfer Learning to solve pneumonia detection from chest X-rays.

The following techniques are used:
* Creating a training set that has equal amount of pneumonia and no pneumonia classes
* Image augmentation using ImageDataGenerator from keras.preproccesing
* Visualizing augmented data (This is helpful for understanding the extent to which data is being manipulated prior to training, and can be compared with how the raw      data look prior to augmentation)
* Moddeling: - pre-trained network downloaded from Keras for fine-tuning
             - loading VGG16
             - freezing all weights, leaving just the last layer for manipulation/add-ons
             - using Adam as optimizer and binary crossentropy as the loss function
* Visualizing model performance metrics: ROC-auc curve, Precision-Recall curve, F1-score
* Visualizing loss and accuracy during training epochs
