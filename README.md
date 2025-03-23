# The-resnet-18-model-is-fine-tuned-on-the-CIFAR-10
数据集在文件里，如果你想更换数据集，对resnet-18模型微调。首先下载你的数据集并解压，在代码中修改路径。之后在代码中reshape()你的图像形状适应预训练模型初始图像大小，同时修改分类头到划分具体几类。 最后图像的数据集太大，则有必要采用GPU进行训练。

代码中图像数据集的下载地址：给出数据集下载网址：https://www.kaggle.com/c/cifar-10
