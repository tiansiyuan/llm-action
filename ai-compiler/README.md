




## 传统编译器


## AI编译器


## AI 编译器前端优化

前端优化作为AI编译器的整体架构主要模块，主要优化的对象是计算图，而计算图是通过AI框架产生的，值得注意的是并不是所有的AI框架都会生成计算图，有了计算图就可以结合深度学习的原理知识进行图的优化。 

- 计算图层（Graph IR）
- 算子融合（OP Fusion）
- 布局转换（Layout Transform）
- 内存分配（Memory Allocation）
- 常量折叠（Constant Fold）
- 公共子表达式消除（CSE）
- 死代码消除（DCE）
- 代数简化（ARM）



## AI 编译器后端优化

后端优化作为AI编译器跟硬件之间的相连接的模块，更多的是算子或者Kernel进行优化，而优化之前需要把计算图转换称为调度树等IR格式，然后针对每一个算子/Kernel进行循环优化、指令优化和内存优化等技术。 


- 算子循环优化
- 指令和内存优化










## 树模型

- https://mlsys.org/Conferences/doc/2018/196.pdf
- https://github.com/dmlc/treelite
- https://treelite.readthedocs.io/en/latest/


- https://zhuanlan.zhihu.com/p/347514385
- https://zhuanlan.zhihu.com/p/487539515
Treelite是用于有效部署决策树集合的模型编译器。


- 决策树Ensemble的编译优化：https://zhuanlan.zhihu.com/p/597511551










