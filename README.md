# 信用卡违约预测项目

## 📊 项目概述
基于台湾信用卡客户数据，预测客户下月是否违约。包含完整的特征工程、模型训练和评估流程。

## 🎯 项目目标
1. 构建高精度的信用卡违约预测模型
2. 实现完整的特征工程流程
3. 开发可解释的评分卡模型
4. 提供业务决策建议

## 📁 项目结构
credit-card-default-prediction/
├── data/ # 数据集
├── notebooks/ # 探索性分析和实验
├── src/ # 源代码
├── tests/ # 单元测试
├── docs/ # 文档
├── models/ # 训练好的模型
├── reports/ # 结果报告
└── config/ # 配置文件

## 📈 数据集
- **来源**: UCI Machine Learning Repository
- **样本数**: 30,000
- **特征数**: 23
- **目标变量**: default payment next month (1=违约, 0=未违约)

## 🔧 技术栈
- Python 3.8+
- pandas, numpy, scikit-learn
- XGBoost, LR
- matplotlib, seaborn
