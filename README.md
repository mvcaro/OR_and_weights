Object recognition

Library of object recognition models for object detection and instance segmentation. It includes the original paper, pretrained weights available, and deep learning framework used by code shared.


===
- PT = PyTorch    
- TF = TensorFlow
- C = Caffe       
- MXN = MXNet
- MCN = MaxConvNet
- T = Torch

* ~ Code not very accurate / incomplete 
* / Not available

| No. | Name     | Year | Paper |   PT    |     TF     |    C   |   MXN |    MCN    |   T   | Pre-trained weights|
|:---:|----------|------| :---: | :---:   | :---:      |  :---: | :---: |   :---:   | :---: |    :---:           |
| 1 |Mask R-CNN | 2017 | [ * ](https://arxiv.org/pdf/1703.06870.pdf) |  [PT](https://github.com/facebookresearch/maskrcnn-benchmark) | [ TF ](https://github.com/matterport/Mask_RCNN) | [ C ](https://github.com/facebookresearch/Detectron) | | | | [PyTorch](https://github.com/facebookresearch/maskrcnn-benchmark/blob/master/MODEL_ZOO.md), [Tensorflow](https://github.com/matterport/Mask_RCNN) |
| 2 |FCIS: Fully convolutional instance-aware semantic segmentation | 2016 | [ * ](https://arxiv.org/pdf/1611.07709.pdf) |  |  |  | [ MXN ](https://github.com/msracver/FCIS)| | | [MXNet](https://github.com/msracver/FCIS)|
| 3 |Instance-sensitive Fully Convolutional Networks | 2016 | [ * ](https://arxiv.org/pdf/1603.08678.pdf) | | | | | | | / | 
| 4 | Object detection via region-based fully convolutional networks | 2016 |[ * ](https://arxiv.org/pdf/1605.06409.pdf) | | | [ C ](https://github.com/facebookresearch/detectron) | | | | [Caffe](https://github.com/facebookresearch/Detectron/blob/master/MODEL_ZOO.md) |
| 5 | MNC: Instance-aware semantic segmentation via multi-task network cascades | 2015 |[ * ](https://arxiv.org/pdf/1512.04412.pdf) | | | [C](https://github.com/daijifeng001/MNC) | | | | [Caffe](https://github.com/daijifeng001/MNC) |
| 6 | R-FCN: Object detection via region-based fully convolutional networks | 2016 | [ * ](https://arxiv.org/pdf/1605.06409.pdf) | | [TF](https://github.com/xdever/RFCN-tensorflow) | [C](https://github.com/facebookresearch/detectron) | [MXN](https://github.com/msracver/Deformable-ConvNets)| | |[PyTorch](https://github.com/mvcaro/Detectron.pytorch), [TensorFlow](https://github.com/xdever/RFCN-tensorflow), [Caffe](https://github.com/facebookresearch/detectron), [MxNet](https://github.com/msracver/Deformable-ConvNets) |
| 7 | Instancecut: from edges to instances with multicut | 2016 | [ * ](https://arxiv.org/pdf/1611.08272v1.pdf) | | | | | | | / |
| 8 | Deep Watershed Transform for Instance Segmentation | 2016 | [ * ](https://arxiv.org/pdf/1611.08303.pdf) | | [TF](https://github.com/min2209/dwt)| | |  | | [TensorFlow](https://github.com/min2209/dwt)|
| 9 | Pixelwise Instance Segmentation with a Dynamically Instantiated Network | 2017 | [ * ](https://arxiv.org/pdf/1704.02386.pdf)| | | | | | | / |
|10 | SGN: Sequential Grouping Networks for Instance Segmentation| 2017 | [ * ](http://openaccess.thecvf.com/content_ICCV_2017/papers/Liu_SGN_Sequential_Grouping_ICCV_2017_paper.pdf) | | | | | | | / |
|11 | DeepMask: Learning to segment object candidates | 2015 | [ * ](https://arxiv.org/pdf/1506.06204.pdf) | [PT](https://github.com/foolwood/deepmask-pytorch) |  | | | | [T](https://github.com/facebookresearch/deepmask) | [PyTorch](https://github.com/foolwood/deepmask-pytorch), [Torch](https://github.com/facebookresearch/deepmask) |
|12 | SharpMask: Learning to refine object segments | 2016 | [ * ](https://arxiv.org/pdf/1603.08695.pdf) | | [TF](https://github.com/aby2s/sharpmask) |  |  |  | [T](https://github.com/facebookresearch/deepmask) | [TensorFlow](https://github.com/aby2s/sharpmask) , [Torch](https://github.com/facebookresearch/deepmask) |
|13 | A MultiPath Network for Object Detection | 2016 | [ * ](https://arxiv.org/pdf/1604.02135v2.pdf) | | | | | | [T](https://github.com/facebookresearch/multipathnet) | [Torch](https://github.com/facebookresearch/multipathnet) |
|14 | Iterative instance segmentation | 2015 | [ * ](https://arxiv.org/pdf/1511.08498.pdf) |  |  | |  | |
|15 | Recurrent Instance Segmentation | 2015 | [ * ](https://arxiv.org/pdf/1511.08250.pdf) | | | | | | [T](https://github.com/bernard24/RIS) | / |
|16 | MaskLab: Instance Segmentation by Refining Object Detection with Semantic and Direction Features | 2017 | [ * ](https://arxiv.org/pdf/1712.04837.pdf) | | | | | |  | / |
|17 | Semantic Instance Segmentation via Deep Metric Learning | 2017 | [ * ](https://arxiv.org/pdf/1703.10277.pdf) |[~PT](https://github.com/alicranck/instance-seg) |  | | | | | / |
|18 | Recurrent Pixel Embedding for Instance Grouping| 2017 | [ * ](https://arxiv.org/pdf/1712.08273.pdf) | | | | | [MCN](https://github.com/aimerykong/Recurrent-Pixel-Embedding-for-Instance-Grouping) | | [MatConvNet](https://github.com/aimerykong/Recurrent-Pixel-Embedding-for-Instance-Grouping)|
|19 | End-to-End Instance Segmentation with Recurrent Attention| 2017 | [ * ](https://arxiv.org/pdf/1605.09410.pdf)| | [TF](https://github.com/renmengye/rec-attend-public) |  |  |  | | [TensorFlow](https://github.com/aimerykong/Recurrent-Pixel-Embedding-for-Instance-Grouping)
|20 | PANet: Path Aggregation Network for Instance Segmentation | 2018 | [ * ](https://arxiv.org/pdf/1803.01534.pdf) |  [PT](https://github.com/ShuLiu1993/PANet) | | | | | | [PyTorch](https://github.com/ShuLiu1993/PANet) |
|21 | BlitzNet: A Real-Time Deep Network for Scene Understanding | 2017 | [ * ](https://arxiv.org/pdf/1708.02813.pdf) | | [ TF ](https://github.com/dvornikita/blitznet) | | | | | [TensorFlow](https://github.com/dvornikita/blitznet/blob/master/test.py) |
|22 | FastMask: Segment Multi-scale Object Candidates in One Shot | 2017 | [ * ](https://arxiv.org/pdf/1612.08843.pdf) | | | [C ](https://github.com/voidrank/FastMask) | | | | [Caffe](https://github.com/voidrank/FastMask) |
|23 | Deep Residual Learning for Image Recognition | 2016 | [* ](http://openaccess.thecvf.com/content_cvpr_2016/papers/He_Deep_Residual_Learning_CVPR_2016_paper.pdf) | | | [C](https://github.com/KaimingHe/deep-residual-networks) | | | | |
|24 | Feature pyramid networks for object detection |2016 | [ * ](https://arxiv.org/abs/1612.03144) | | | | | | | / | 
|25 | Deep Residual Learning for Image Recognition | 2015 | [* ](https://arxiv.org/abs/1512.03385) | | [TF](https://github.com/tensorpack/tensorpack/tree/master/examples/ResNet) | | [MCN](https://github.com/zhanghang1989/ResNet-Matconvnet) | [T](https://github.com/KaimingHe/deep-residual-networks) | | [TensorFlow](https://github.com/tensorpack/tensorpack/tree/master/examples/ResNet), [MatConvNet](https://github.com/zhanghang1989/ResNet-Matconvnet), [Torch](https://github.com/KaimingHe/deep-residual-networks) | | | | [Caffe](https://github.com/zhaoweicai/cascade-rcnn) |
|26 | Cascade R-CNN: Delving into High Quality Object Detection | 2017 | [* ](https://arxiv.org/abs/1712.00726) | | | [C](https://github.com/zhaoweicai/cascade-rcnn) | | | | [Caffe](https://github.com/zhaoweicai/cascade-rcnn) |
|27 | FastMask: Segment Multi-scale Object Candidates in One Shot | 2016 | [* ](https://arxiv.org/abs/1612.08843) | | | [C](https://github.com/voidrank/FastMask) | | | | [Caffe](https://github.com/voidrank/FastMask) | 
|28 | Pseudo Mask Augmented Object Detection | 2018 | [ * ](https://arxiv.org/abs/1803.05858) | | | | | | | / |
|29 | One-Shot Instance Segmentation | 2018 | [* ](https://arxiv.org/pdf/1811.11507.pdf) | | [TF](https://github.com/bethgelab/siamese-mask-rcnn) | | | | | [TensorFlow](https://github.com/bethgelab/siamese-mask-rcnn) |
|30 | YOLACT: Real-time Instance Segmentation| 2019 | [* ](https://arxiv.org/pdf/1904.02689.pdf) | [PT](https://github.com/dbolya/yolact) | | | | | | [PyTorch](https://github.com/dbolya/yolact) |
|31 | Instance-Level Salient Object Segmentation | 2017 | [ * ](https://arxiv.org/pdf/1704.03604.pdf) | | | | | | | / |
|32 | Semantic Instance Segmentation with a Discriminative Loss Function | 2017 | [* ](https://arxiv.org/pdf/1708.02551.pdf) |
|33 | Recurrent Neural Networks for Semantic Instance Segmentation | 2017 | [ * ](https://arxiv.org/pdf/1712.00617.pdf) | [PT](https://github.com/imatge-upc/rsis) | | | | | | [PyTorch](https://github.com/imatge-upc/rsis) |
|34 | One-Shot Instance Segmentation (Siamese Mask R-CNN) | 2018 | [ * ](https://arxiv.org/pdf/1811.11507.pdf) |  | [TF](https://github.com/bethgelab/siamese-mask-rcnn) | | | | | [TensorFlow](https://github.com/bethgelab/siamese-mask-rcnn) | 
|35 | Affinity Derivation and Graph Merge forInstance Segmentation | 2018 | [ * ](https://arxiv.org/pdf/1811.10870.pdf) | | [TF](https://github.com/xck36/GMIS) | | | | | [TensorFlow](https://github.com/xck36/GMIS) |
|36 | DASNet: Reducing Pixel-level Annotations forInstance and Semantic Segmentation | 2018 |[* ](https://arxiv.org/pdf/1809.06013.pdf)| | | | | | | / |
|37 | Predicting Future Instance Segmentation by Forecasting Convolutional Feature | 2018 | [ * ](https://arxiv.org/pdf/1803.11496.pdf) | | | [C](https://github.com/facebookresearch/instpred) | | | | [Caffe](https://github.com/facebookresearch/instpred) |
|38 | RetinaMask: Learning to predict masks improves state-of-the-art single-shot detection for free | 2019 | [PT](https://github.com/chengyangfu/retinamask) | | | | | | | [PyTorch](https://github.com/chengyangfu/retinamask) |
|  |  |  |  |  |  |  |  |  |  |
|A1 | Convolutional feature masking for joint object and stuff segmentation | 2014 | [ * ](https://arxiv.org/pdf/1412.1283.pdf) |
|A2 | Rich feature hierarchies for accurate object detection and semantic segmentation | 2013 | [ * ](https://arxiv.org/pdf/1311.2524.pdf)| [~PT](https://paperswithcode.com/paper/semantic-instance-segmentation-with-a#code) | | | | | | / |
|A3 | Simultaneous detection and segmentation | 2014 | [ * ](https://arxiv.org/pdf/1407.1808.pdf) |
|A4 | Hypercolumns for object segmentation and fine-grained localization | 2014 | [ * ](https://arxiv.org/pdf/1411.5752.pdf)|
