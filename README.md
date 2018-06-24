# Artistic Neural Style Transfer using Convolution Neural Network 

1. With help of neural style transfer, content image and style image generate new artistic image.  
2. Hidden layer activations individually play important role in deep learning applications. 
3. Accurate value of hyper parameter depends on specific application. Sometimes just reducing cost by increasing number of iterations makes no sense. This is neural style transfer is perfect application of this as image at 1000 iterations is same as image at 2000 iterations. 
4. Using pre-trained networks with transfer learning can save lot of time as well as computation cost. 

4.5 Parameters/Hyper-parameters:
Hyper-parametersValueReason1. Style layer coefficient'conv1_1', 0.1
'conv2_1', 0.3
'conv3_1', 0.3
'conv4_1', 0.3
'conv5_1', 0.1Every layer may have same values. It's about weighting on certain layers. 2. Content & Style optimization proportion (?, ?)?= 2 or 1 for content image
? = 3  or 5 for style imageStyle coefficient should be higher for higher optimization of style3. Noise_ratio0.6Initially less part of content should be in noisy image4. Learning rate0.5Tried combinations to get good image styler image5. Iteration2000Minimized cost improved sense of image but took more time6. Visualization layer'conv4_3'Deep layer has deep features


