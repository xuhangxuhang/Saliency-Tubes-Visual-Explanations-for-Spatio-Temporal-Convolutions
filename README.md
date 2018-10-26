# Keras Heatmaps for 3D Convolutions

## About
The purpose of this repository is to provide a multi-dimensional implementation of the heatmap visualisation for Deep Learning models in volumetric data. The output of the script is a folder containing consecutive frames. The base for the script has been Gabriel de Marmiesse's easy-to-follow [repo](https://github.com/gabrieldemarmiesse/heatmaps) of his heatmap implementation.

For videos, these frames can be turned to video/GIFs with tools such as [`ImageMagic`](https://github.com/ImageMagick/ImageMagick) or [`imageio`](http://imageio.github.io/).

<p align="center">
  <img  src="https://github.com/alexandrosstergiou/Inception_v3_TV_Human_Interactions/blob/master/inception_v3_activations_vis/layer_1_conv2d_1.png"></p>

*Heatmaps of 3D ResNet50 trained on UCF-101*



## Installation
Please make sure, Git is installed in your machine:
```sh
$ sudo apt-get update
$ sudo apt-get install git
$ git clone https://github.com/alexandrosstergiou/Keras-3DCNN-Heatmap.git
```

## Dependencies
The network was build with Keras with TensorFlow as backend.  `OpenCV` was used for processes in the frame level. For resizing the CAM to the original video dimensions we used `scipy.ndimage`.
```sh
$ pip install opencv-python
$ pip install scipy
```

## References
This work is based on the following two papers:
1. Selvaraju, Ramprasaath R. et al. "
Grad-CAM: Visual Explanations from Deep Networks via Gradient-Based Localization." ICCV, 2017. [[link]](http://openaccess.thecvf.com/content_iccv_2017/html/Selvaraju_Grad-CAM_Visual_Explanations_ICCV_2017_paper.html)


If you use this repository for your work, you can cite it as:
```sh
@misc{astergiou2018heatmaps},
title={3D CNN Heatmap}
author={Alexandros Stergiou}
year={2018}
```

## License
MIT


## Contact
Alexandros Stergiou

a.g.stergiou at uu.nl

Any queries or suggestions are much appreciated!
