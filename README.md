# DeepFake
Deepfakes (a portmanteau of "deep learning" and "fake") are synthetic media in which a person in an existing image or video is replaced with someone else's likeness.
In this project we use the Celeb-DF dataset.Deepfake dataset contains original videos and fake or duplicates.In this dataset contain the real videos of 590.Fake videos of 5639.
ResNet stands for Residual Network and convolutional neural network (CNN) based model.It consists of a series of convolutional blocks.The main advantage is to avoid the vanishing gradient problem. By having a skip connection.
Xception is an extension of the Inception architecture which replaces the standard Inception modules with depthwise separable convolutions.
We have transfer learning to retrain the final layers in the Xception model.Using the celeb version2 dataset.Transfer Learning: Having the pre-trained model.It saves time Number of parameters.Test accuracy 92.160%.
HOG:It stands for the histogram of oriented gradients.It looks at the gradient magnitude and gradient direction of the image.Binding then creates a vector.
CONCLUSION
In this project, we used Multi-classifier based DeepFake Detection
Multiple classifiers were formed by concatenating the dense layers from XceptionNet and ResNet
Further, fusion of hand-crafted HOG and Deep features was performed by feature level concatenation. It obtained the best performance.

![2022-12-06 (2)](https://user-images.githubusercontent.com/90169754/208802977-4838b6c8-7dc3-4482-838f-688d0afa54ae.png)
![2022-12-06 (1)](https://user-images.githubusercontent.com/90169754/208802983-0695bbc0-5d4b-4192-b9b6-7261a2dd2979.png)
