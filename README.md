# XGBoost-model使用说明
## 文件说明：
* XGBoost模型文件：gv_model.pkl
* 测试文件：x_test.csv
## 代码运行说明：
--- 在python 3 环境下，运行下列代码
* import pandas     # 载入pandas包
* import joblib      # 载入joblib包
* gv_test=joblib.load("gv_model.pkl")    # 载入模型文件
* x_test.pd.read_csv('x_test.csv')       # 载入测试文件
* gv_test.predict_proba(x_test)[:,1]     # 得到预测值

