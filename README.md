# MovieRecommendation基于协同过滤算法的电影推荐系统
## 1、简介
Collaborative Filtering(TwoMethod)_0.3为包含User_CF协同过滤和 Item_CF协同过滤两种算法的程序，并包含了直接取平均值的混合模型的结果
 为了保证程序运行的效率， Collaborative Filtering(TwoMethod)_0.3只计算了测试集中电影的评分预测
 ## 程序说明
Frame.java  为简单的界面，由于没有计算全部的预测评分，所以推荐电影选项可能没有数据显示（通过简单修改可现实全部预测评分在4.5以上的电影）
application.java  计算出了MAE，并在控制台显示，在将数据导出到工程中的score.out文件中 数据格式为

用户编号  电影编号  User_CF评分预测  Item_CF评分预测  混合模型评分预测 实际评分  User_CF评分预测MAE  Item_CF评分预测MAE  混合模型评分预测MAE
