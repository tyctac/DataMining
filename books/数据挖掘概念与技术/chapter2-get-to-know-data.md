## 认识数据

### 知识点整理
- 属性，维度(dimension,数据仓库),特征(feature，机器学习),变量（variable，统计学),可以互换的使用
- 标称属性，均值，中位数没有意义，而众数是有意义的：
- 二元属性
- 序数属性
- 数值属性  
**只有这三类属性吗？？？**

1. 2 **数据的基本统计描述**
    - 中位数的近似值计算
2. **对象属性相似度计算**
    - 看来这里并不是对某一种属性而言的，而是对某一类型的而言，eg，把同为标称属性的属性放在一起求相似度
    - 介绍的给予不同种类属性的相似度计算方法，但是并没有介绍具体将不同属性整合到一起，虽然混合属性计算相似度在在特殊的条件下实现了这种整合，但是其系数只是单纯的使用的0和一，并不能体现不同属性的影响，对于不同维度的整合有什么通用的方法呢，还是暂时**只能靠经验呢**

### 习题二
- 2.5  
    - 标称属性：只有相同和不同，对于单个属性来说，相同为1，不同为零，对于多个属性来说，相同的个数除以总的该类型的属性
    - 非对称的二元属性：对于不重要的维度，
