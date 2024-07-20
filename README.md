# Unsupervised Cross-domain Object Detection for the Surface Defect Detection of Aero-engine Blades
This repo is the official implementation of ["Unsupervised Cross-domain Object Detection for the Surface Defect Detection of Aero-engine Blades"] (Submitted to IEEE Sensors Journal)

The source code FGWNet and UCAB dataset will be published soon~~

In addition, the early operating environment of domain adaptive object detection uses the Pytorch 0.4 or 0.4.1, and the graphics card that can run these codes supports up to 2080Ti. Now 30 and 40 series graphics cards occupy the mainstream position in the market. Therefore, we rewrite the relevant code of the early domain adaptive object detection so that it can run on the 30 and 40 series GPUs.

## References
The code we rewritten includes DA, the pioneering work of domain adaptive object detection, as well as SW, SCL, GPA, UMT, and HTCN. And the original code links and our rewritten code links are as follows:

### 1、  Reference：Domain Adaptive Faster R-CNN for Object Detection in the Wild [2018]  
* Original code link：https://github.com/yuhuayc/da-faster-rcnn
* Our code：https://github.com/sean-Yo/DA

### 2、  Reference：Strong-Weak Distribution Alignment for Adaptive Object Detection [2019]
* Original code link：https://github.com/VisionLearningGroup/DA_Detection
* Our code：https://github.com/sean-Yo/SW

### 3、  Reference：SCL: Towards Accurate Domain Adaptive Object Detection via Gradient Detach Based Stacked Complementary Losses [2019]
* Original code link：https://github.com/harsh-99/SCL
* Our code：https://github.com/sean-Yo/SCL

### 4、  Reference：Unbiased Mean Teacher for Cross-domain Object Detection [2019]
* Original code link：https://github.com/kinredon/umt
* Our code：https://github.com/sean-Yo/UMT

### 5、  Reference：Cross-domain Detection via Graph-induced Prototype Alignment [2019]
* Original code link：https://github.com/ChrisAllenMing/GPA-detection
* Our code：https://github.com/sean-Yo/GPA

### 6、  Reference：Harmonizing Transferability and Discriminability for Adapting Object Detectors [2020]
* Original code link：https://github.com/chaoqichen/HTCN
* Our code：https://github.com/sean-Yo/HTCN
