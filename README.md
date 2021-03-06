# pytorch-semseg

[![license](https://img.shields.io/github/license/mashape/apistatus.svg)](https://github.com/meetshah1995/pytorch-semseg/blob/master/LICENSE)

## Semantic Segmentation Algorithms Implemented in PyTorch

This repository aims at mirroring popular semantic segmentation architectures in PyTorch. 

<img src="https://meetshah1995.github.io/images/blog/ss/ptsemseg.png" width="80%">

### Networks implemented

* [Segnet](https://arxiv.org/abs/1511.00561) - With Unpooling using Maxpool indices
* [FCN](https://arxiv.org/abs/1411.4038) - All 1( FCN8s), 2 (FCN16s) and 3 (FCN8s) stream variants
* [U-Net](https://arxiv.org/abs/1505.04597) - With optional deconvolution and batchnorm
* [Link-Net](https://codeac29.github.io/projects/linknet/)

#### Upcoming 

* [PSPNet](https://arxiv.org/abs/1612.01105)
* [E-Net](https://arxiv.org/abs/1606.02147)
* [RefineNet](https://arxiv.org/abs/1611.06612)
* [MaskRCNN](https://arxiv.org/abs/1703.06870)

### DataLoaders implemented

* [CamVid](http://mi.eng.cam.ac.uk/research/projects/VideoRec/CamVid/)
* [Pascal VOC](http://host.robots.ox.ac.uk/pascal/VOC/voc2012/segexamples/index.html)
* [Cityscapes](https://www.cityscapes-dataset.com/)
* [ADE20K](http://groups.csail.mit.edu/vision/datasets/ADE20K/)

#### Upcoming

* [NYUDv2](http://cs.nyu.edu/~silberman/datasets/nyu_depth_v2.html)
* [Sun-RGBD](http://rgbd.cs.princeton.edu/)
* [MS COCO](http://mscoco.org/)
