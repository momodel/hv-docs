Mo是一个支持 Python 的人工智能在线建模平台。它建立并提供一个能够将需求发布者、模块开发与组装者、应用使用者汇聚起来的平台环境。Mo始于数据，忠于用户，致力于`降低AI技术使用门槛、缩短学习曲线`，是一个为实现`人工智能民主化、应用普及化`目标而生的交互式线上数据模型设计、开发、应用平台。

<video src="http://files.momodel.cn/mo.mp4" controls="controls" poster="http://mo-imgs.momodel.cn/HomePage/cover.png" style="width: 880px; height: 535px;"></video>

## 流程介绍

开发机器学习算法大致分三步。首先需要`构建数据集`，这是算法建立的基础。然后需要进行数据挖掘和分析，提取出待训练的特征，`建立模型`并训练。算法完成之后`组装成应用`，进行部署就可以让别人调用了。

### 第一步，构建数据集

<img src='https://ws1.sinaimg.cn/large/006tNbRwly1fy3rfnf0vij31fa0u0n1v.jpg' width="100%" height="100%" />

### 第二步，开发模型

<img src='https://ws3.sinaimg.cn/large/006tNbRwly1fy3rhjvrfdj31ew0u043e.jpg' width="100%" height="100%" />

### 第三步，组装应用

<img src='https://ws3.sinaimg.cn/large/006tNbRwly1fy3riv38x5j31fg0u0tdg.jpg' width="100%" height="100%" />


## 概念介绍

### 数据集(Dataset)

`数据集`是由数据组成的集合, 机器学习建模的第一步是构建数据集。数据集可以自己上传，也可以导入使用其他人公开的。如果你想把数据集分享给他人，只需设置权限为`公开`。

#### 数据集的构建流程

1. 创建数据集项目（Create dataset project）
2. 上传数据（Upload data）
3. 预览数据（Preview data）
4. 公开发布（Public）


### 模块(Module)

拥有数据集之后，你就可以将它导入创建好的模块项目中进行分析和训练了。我们将`模块`分为两类，一类是不需要经过训练的算法，称之为`工具`；另一类是可以训练的算法，被叫做`模型`。

####  模块的开发流程

1. 创建模块项目（Create module project）
2. 导入数据集（Import datasets）
3. 分析数据（Analyze data）
4. 开发（Develop）
5. 训练 (Train)
5. 部署（Deploy）

#### 应用(App)

`应用`是由模块组成、有特定功能的软件程序，能够实现较复杂的功能。下面举两个简单的例子：

应用名称 | 功能 | 所需数据集 | 所需模块
-- | -- | -- | --
夫妻脸 | 寻找和自己最相似的异性明星 | 图片 | 性别分类器模型、面部特征提取工具
唐诗生成器 | 用给定的字词生成唐诗 | 唐诗 | 唐诗生成模型

利用平台已有的公开数据集和模型，你可以简单快捷地创造出属于自己`AI应用`。接着只需要使用我们的部署功能，就能将自己的作品变成服务，供其他用户使用。

#### App 的开发流程

1. 创建应用项目（Create app project）
2. 调用已有模块（Import modules）
3. 组装集成（Integrate）
4. 发布部署（Deploy）
5. 运行调用（Use）