**迁移DeblurGan网络做去雾工作**

DeblurGan论文：https://arxiv.org/pdf/1711.07064.pdf

## 1. 网络结构

Generator

![](https://ae01.alicdn.com/kf/HTB1tOehbAxz61VjSZFrq6xeLFXad.jpg)

Discriminator

![](https://ae01.alicdn.com/kf/HTB1E7evcL1G3KVjSZFkq6yK4XXaa.jpg)

## 2. 训练

训练所用数据集来自 [RESIDE数据集](<https://sites.google.com/view/reside-dehaze-datasets/reside-v0>)

## 3. 效果



![](https://ae01.alicdn.com/kf/HTB1czyDcGWs3KVjSZFxq6yWUXXaB.jpg)

![](https://ae01.alicdn.com/kf/HTB1gSKDcG5s3KVjSZFNq6AD3FXaD.jpg)

![](https://ae01.alicdn.com/kf/HTB1FUWibAxz61VjSZFtq6yDSVXa8.jpg)



### 4. 其它

参考了Deblur的实现：<https://github.com/KupynOrest/DeblurGAN>

其余去雾算法：

1. [DCP去雾Matlab实现](<https://github.com/raven-dehaze-work/DCP-Dehaze>)
2. [MSCNN去雾Matlab实现](https://github.com/raven-dehaze-work/MSCNN_MATLAB)
3. [MSCNN去雾Keras实现](https://github.com/raven-dehaze-work/MSCNN_Keras)
4. [MSCNN去雾TensorFlow实现](https://github.com/dishank-b/MSCNN-Dehazing-Tensorflow)
5. [Dehaze-GAN TensorFlow实现](https://github.com/raven-dehaze-work/Dehaze-GAN)