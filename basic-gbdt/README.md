## 基本梯度提升树 GBDT

- 请实现一个标准的二分类GBDT，可以使用C, C++, Java, Python 等你熟悉的编程语言，**可以使用已有的建立决策树的库**，例如sklearn中的决策树模型。
- 实现XGBoost的二阶算法
- 实现AUC的计算算法
- 实现k-fold交叉验证
- 请 fork 这个代码仓库，然后增加自己的解答文件，然后发送PR提交作业
- 请不要抄袭，自己的解答文件请以 yourname.xx  形式提交
- 启动代码放在 `getstart/` 下面

## 一些有用的信息
- GBDT二分类的损失函数是 log(1+exp(-y*(wT x)))
- 数据集可以使用 iris 数据集，iris数据集有3个类别，请将第1类作为正例，其他类别作为负例，原则上可以实现100%准确率。
- 如果用python的话，可以利用sklearn.dataset.load_iris()直接加载数据集


## 实现列表
提交PR的时候,请在下方列出你的项目

- [getstart](getstart/)
- [tracholar](tracholar/)
- [wenshiqi](wenshiqi/)
- [chenrenbing](chenrenbing/)