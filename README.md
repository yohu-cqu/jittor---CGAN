| 第二届计图挑战赛热身赛开源

# Jittor 热身赛 CGAN

![主要结果](https://s3.bmp.ovh/imgs/2024/05/18/26e882c11619af13.png)

## 简介

本项目包含了第二届计图挑战赛计图热身赛 - 将在数字图片数据集 MNIST 上训练 Conditional GAN（Conditional generative adversarial nets）模型，通过输入一个随机向量 z 和额外的辅助信息 y (如类别标签)，生成特定数字的图像。

## 安装 

#### 运行环境
- ubuntu 20.04 LTS
- python = 3.7
- jittor = 1.3.8.5

#### 安装依赖
执行以下命令安装 python 依赖
```
pip install -r requirements.txt
```
jittor环境安装参考[官方文档](https://cg.cs.tsinghua.edu.cn/jittor/download/)

## 训练

python CGAN.py

模型保存在`model`目录下

生成的中间结果保存在`result`目录下

## 推理

生成测试集上的结果可以运行以下命令：

python CGAN_gen.py

## 致谢

此项目参考了 [jittor-gan](https://github.com/Jittor/gan-jittor)。