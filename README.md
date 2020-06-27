# Sandesh_OR_German_Shepherd
Convolutional neural network which classifies the images of Sandesh and German Shepherd.
The Dogs images are downloaded from the http://image-net.org/download. The Sandesh images are downloded from the my own collection from Photos. 

There are around 100 images including the training data and validation data for each class. The sample are not enough to make a good classifier. That's why the CNN made by me didn't performed well as it's couldn't extract the more features.

However, the 'InceptionV3' used as transfer learning did impressive job as it had several layers.

The training accuracy is 99% with validation accuracy of 99%. This accuracy was achieved because:
  - There were less data.
  - There wasn't a lot of varition in the images.
  - The Neural Network was Deep and Huge. 
 
 This could be impoved by feeding a huge amount of images with a lot of variation. 
 
 Libraires Used: Numpy, Keras, Tenserflow, Matplotlib etc. 
