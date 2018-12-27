#Real-world Anomaly Detection in Surveillance Videos

In this section we try to reproduce the result of Sultani et al. (2018). The figure above describes the model of Sultani :

An important part of this model is to extract the C3D features fo each video segment. To do so, we use the results of Du Tran et al. (2015), they used 3D convolutianl layers in order to build a generic video descriptor.

The weights of the video descriptor was taken form https://github.com/adamcasson/c3d. 
