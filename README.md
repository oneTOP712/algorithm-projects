# Algorithm Projects

算法与深度学习课程项目集合，包含计算机视觉与自然语言处理方向的多个实践项目。

## 项目列表

| 项目 | 方向 | 技术栈 | 结果 |
|------|------|--------|------|
| Canny 边缘检测 | 计算机视觉 | Python、NumPy | 手工实现完整流程 |
| ResNet18 图像分类 | 计算机视觉 | PyTorch、CUDA | 测试准确率 86.68% |
| Shallow GoogLeNet | 计算机视觉 | PyTorch、CUDA | 测试准确率 71.99% |
| CNN 手写数字识别 | 计算机视觉 | PyTorch | 测试准确率 99.13% |
| LSTM 中文情感分析 | 自然语言处理 | PyTorch、jieba | 测试准确率约 95% |
| RNN 中文文本分类 | 自然语言处理 | PyTorch、jieba | 训练准确率 100% |

## 技术栈

- 编程语言：Python
- 深度学习：PyTorch
- 数据处理：NumPy、Pandas
- 可视化：Matplotlib
- 工具：Jupyter Notebook、CUDA

## 项目说明

### 1. Canny 边缘检测
从零实现 Canny 边缘检测完整流程，包括灰度化、高斯滤波、Sobel 梯度、非极大值抑制、双阈值检测与边缘连接。完成 6 组双阈值参数对比实验。

### 2. ResNet18 图像分类
手写 BasicBlock 与 ResNet 网络结构，在 CIFAR-10 数据集上完成训练，测试集准确率 86.68%。

### 3. Shallow GoogLeNet
实现 Inception 模块与 Shallow GoogLeNet，在 CIFAR-10 上完成 15 轮训练，测试集准确率 71.99%。

### 4. CNN 手写数字识别
自行实现 MNIST 本地数据读取类，搭建 CNN 模型，测试集准确率 99.13%。

### 5. LSTM 中文情感分析
基于微博情感数据集，完成分词、词典构建、LSTM 模型训练与预测接口，测试集准确率约 95%。

### 6. RNN 中文文本分类
实现标准 RNN 文本分类模型，支持 4 分类任务，训练准确率 100%。
