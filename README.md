# Bioinformatics Learning Website

王伟轩

---

## 课堂笔记

生物信息学-大数据驱动的科学：

1. 信息采集： 生物医学数据，包括基因序列、基因表达数据、蛋白质数据等；

2. 分析：
   - 数据清洗
   - 特征提取

3. 建模：用于数据分析和生物学问题的建模，如使用机器学习算法进行预测、分类、基因功能预测等。

**算法**：算法是一组明确的、有限的**步骤**，通常用于解决特定问题或执行某项任务。在生物信息学中，通常用于处理数据、执行计算任务及推导结果。常见的算法例如：

- 序列比对算法/BLAST：在数据库中找到与查询序列最相似的序列
- 聚类算法（如[K-means](https://blog.csdn.net/qq_38614074/article/details/137456095)）：根据相似性将数据点分组

**模型**：是对现实世界现象的**数学描述**，用于模拟、理解或预测。模型通常依赖于一定的假设、输入数据以及训练过程，目的是为了理解或预测生物学数据背后的机制。模型具有如下特征：

- 模型通常基于一定的理论假设或先验知识来构建。
- 模型的建立通常依赖于大量的训练数据，模型的准确性取决于数据的质量和训练的程度。
- 模型的目标往往是用来进行预测或推断。

例如机器学习模型（如[SVM](https://blog.csdn.net/qq_43634001/article/details/98470911)和[Random Forest](https://blog.csdn.net/z551646/article/details/144581193)）和生物学机制模型（如对基因调控机制的模拟）。

**模型依赖算法**：构建和训练模型常常需要使用算法。例如，训练一个机器学习模型（如神经网络）通常需要使用优化算法来更新模型的参数。

**算法实现模型**：模型的推断或预测常常通过算法来实现，算法为模型提供执行和计算的步骤。

## 学习计划

1. 编程技能
   - 熟悉常用的Linux指令
   - 熟悉编程语言R与Python
2. 了解常用生信工具原理与应用
   - 理解并应用 BLAST 工具进行序列比对
   - 分析基因或蛋白质的保守性
   - 了解基因的功能注释和通路分析
   - 掌握二代测序的原理与步骤，分析DNA、RNA测序数据
   - 学会构建基因分析调控网络
   - 识别RNA或DNA的功能性序列
3. 掌握机器学习的基本概念与方法，并在R和Python中实现机器学习算法
4. 阅读生物信息学文献，学会利用生物信息学方法探索并解决临床问题
