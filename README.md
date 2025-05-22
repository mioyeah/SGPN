#  SmoothGasussPoseNet: 3D Motion Transfer based on Gaussian Splatting

 Due to the complexity and diversity of human clothing texture features and motion characteristics, 3D motion transfer is very challenging. Existing methods use MLP-based Neural Radiance Fields (NeRF) to render 3D people, but pure MLPs still have difficulty regressing pose-dependent clothing details. Therefore, this paper proposes a smooth motion transfer model based on 3D Gaussian splatting, called SmoothGaussPoseNet (SGPN). This method can transfer complex human motion videos using only a small number of human images. First, we design SpatioTemporal Cross Attention Blocks to address the problem of nonsmooth motion. Then, to address the artifact problem, we introduce the FLIP encoder combined with ResNet to propose a novel network that can effectively extract deep human image features and generate dynamic 3D human motion videos. Finally, in order to further adapt to the complex movement characteristics of the human, we propose an isometric regularized Gaussian loss to enhance the learning ability of the model. In the experimental section, we demonstrate that the proposed method outperforms recent approaches in terms of overall performance and various evaluation metrics.

 
## Approach

![SGPN](https://github.com/mioyeah/FDA-GAN/blob/main/data/FDA-GAN.jpg)

##  Panoptic studio datasets
[http://domedb.perception.cs.cmu.edu/]

##  Human3.6m datasets
[http://vision.imar.ro/human3.6m/description.php]

## Installation
### Environment Setup
Coming Soon
