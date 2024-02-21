# Horse and Human Classification TransferLearning 
This repository implements a convolutional neural network (CNN) for classifying images of horses and humans, leveraging the power of transfer learning with the pre-trained InceptionV3 model. Instead of training a new model from scratch, InceptionV3 will be used as a starting point. Then, the pre-trained features are freezed and new layers are being added on top. This saves time and effort and often leads to better accuracy.

## About Dataset
The dataset consists of images that are classified into 2 classes: Horse (0) and Human (1)
![image](https://github.com/mirandarsly/HorseHumanClassification-TransferLearning/assets/113633284/ebfa82bc-c7c9-4481-946e-e34400bf50b6)

## Brief Description About InceptionV3:
* Pre-trained on ImageNet with over 1 million images and 1000 classes. This pre-training imbues InceptionV3 with the ability to extract valuable and generic features from images, making it versatile for various tasks.
* Has 43 layers, creating a deep network capable of complex feature extraction and representation. Deeper networks can learn more intricate relationships between features, leading to better performance.
* Utilizes convolutional architecture, which consists of layers of filters or kernels that convolve across an image, capturing essential features like edges, shapes, and textures. These features are then combined progressively in deeper layers to identify more complex patterns and objects.
* Employs a unique building block called "Inception modules" that efficiently utilize different filter sizes within a single layer. This allows InceptionV3 to capture features at various scales simultaneously, increasing its accuracy and efficiency.


