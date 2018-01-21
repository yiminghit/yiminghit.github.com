---
layout: default
---

## Intelligent Diagnose of Lung Nodules
[back](./)


### Algorithm flowchart

* * *

![](https://github.com/yiminghit/yiminghit.github.com/blob/master/Octree2.png)



### Highlights:

1.Preprocessed lung CT data and extracted the mask of the lung region in the CT image
2. Used U-Net to study the characteristics of lung nodules and segmented test images
3. Extracted the 3D connected domain and obtained 3D data of all the suspected lung nodules
4. Set up a 3D-CNN classification network. The 3-D data was fed to the classification network for training. Used the trained network to classify the test set and the layer outputted the probability of this region

