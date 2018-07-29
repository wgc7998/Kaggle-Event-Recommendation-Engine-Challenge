# Kaggle-Event-Recommendation-Engine-Challenge
KMeans / PCA

## 1 任务说明：
    根据活动的关键词（count_1, count_2, ..., count_100，count_other属性）做KMeans聚类。
    尝试K=10，20，30，..., 100, 并计算各自CH_scores。
## 2 文件说明：
    1.	先运行0.EDA.ipynb，看一下竞赛所有数据的情况。
    2.	总体活动数目太多（300w+记录），只需对训练集train.csv和测试集test.cv出现的活动（13418条记录）举行聚类即可。
    运行1.Users_Events.ipynb可得到只在训练集train.csv和测试集test.cv出现的活动，再进行聚类。

