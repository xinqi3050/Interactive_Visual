# 期末项目
世界女性就业情况调查
## 项目介绍
通过页面展示数据图表，对比各国女性在农业、工业、服务业中就业人员数据，确定女性在新时代中的工作方向
## 项目背景
每一次工业革命，都带来全新的行业和大量的就业机会，这一次也不例外。互联网时代的到来不仅仅改变了人们的生活方式，还预示着女性就业黄金时代的来临。基于数字化重组的产业链分工、行业界限的模糊、虚拟与现实的融合、精细化推送高质量产品和服务……甚至日本提出了“社会5.0"概念，预期了“超智能社会”的前景。多元化的同时，数字经济的准入门槛更低、环境也更中性，女性将有更多获取工作和创富机会、也将有更多影响和改变世界的机会。
## 数据来源
[世界银行数据](https://data.worldbank.org.cn/indicator)
## 数据信息查看：
- [农业女性就业人员（占女性就业的百分比）](https://data.worldbank.org.cn/indicator/SL.AGR.EMPL.FE.ZS?view=chart)
- [工业女性就业人员（占女性就业的百分比）](https://data.worldbank.org.cn/indicator/SL.IND.EMPL.FE.ZS?view=chart)
- [服务业女性就业人员（占女性就业的百分比）](https://data.worldbank.org.cn/indicator/SL.SRV.EMPL.FE.ZS?view=chart)
## 数据信息下载：
- [农业女性就业人员（占女性就业的百分比）](https://github.com/xinqi3050/Interactive_Visual/blob/master/API_SL.AGR.csv)
- [工业女性就业人员（占女性就业的百分比）](https://github.com/xinqi3050/Interactive_Visual/blob/master/API_SL.IND.csv)
- [服务业女性就业人员（占女性就业的百分比）](https://github.com/xinqi3050/Interactive_Visual/blob/master/API_SL.SRV.csv)
## 数据处理方式
- 先用excel对无用的数据做简单的筛选处理；
- 再使用python的pandas，plotly等模块对数据进行可视化处理；
- 最后用制作可交互性的功能数据图。
## 合作伙伴
掌握python语言基础操作，学会在pythonanywhere上成功架站

## 项目展示
- [使用Jupyter notebook做的图表和故事](http://xinqi3050.gitee.io/visual_end_project)
- [使用pythonanywhere的网站](http://ldfckk.pythonanywhere.com/)

### 17级《交互》评分点：
#### 数据清洗和收集难度，数据集丰富程度
##### 数据来源
[世界银行数据](https://data.worldbank.org.cn/indicator)
##### 数据信息查看：
- [农业女性就业人员（占女性就业的百分比）](https://data.worldbank.org.cn/indicator/SL.AGR.EMPL.FE.ZS?view=chart)
- [工业女性就业人员（占女性就业的百分比）](https://data.worldbank.org.cn/indicator/SL.IND.EMPL.FE.ZS?view=chart)
- [服务业女性就业人员（占女性就业的百分比）](https://data.worldbank.org.cn/indicator/SL.SRV.EMPL.FE.ZS?view=chart)
##### 数据信息下载：
- [农业女性就业人员（占女性就业的百分比）](https://github.com/xinqi3050/Interactive_Visual/blob/master/API_SL.AGR.csv)
- [工业女性就业人员（占女性就业的百分比）](https://github.com/xinqi3050/Interactive_Visual/blob/master/API_SL.IND.csv)
- [服务业女性就业人员（占女性就业的百分比）](https://github.com/xinqi3050/Interactive_Visual/blob/master/API_SL.SRV.csv)
##### 数据处理方式
- 先用excel对无用的数据做简单的筛选处理；
- 再使用python的pandas，plotly等模块对数据进行可视化处理；
- 最后用制作可交互性的功能数据图。

##### 整体数据产品/数据故事的选题是否有吸引力、有价值

每一次工业革命，都带来全新的行业和大量的就业机会，这一次也不例外。互联网时代的到来不仅仅改变了人们的生活方式，还预示着女性就业黄金时代的来临。基于数字化重组的产业链分工、行业界限的模糊、虚拟与现实的融合、精细化推送高质量产品和服务……甚至日本提出了“社会5.0"概念，预期了“超智能社会”的前景。多元化的同时，数字经济的准入门槛更低、环境也更中性，女性将有更多获取工作和创富机会、也将有更多影响和改变世界的机会。

所以我通过页面展示数据图表，对比各国女性在农业、工业、服务业中就业人员数据，确定女性在新时代中的工作方向。

##### 【地图的】交互功能对于强化数据产品或者数据故事表现力的程度

- 时间轴，可帮助用户了解近十年里各国的变化趋势
- 可选区间，可帮助用户快速筛选出自己想要的区间

##### 【非地图的】交互功能对于强化数据产品或者数据故事表现力的程度

- 交互设计极大增强了表现力，主要使用折线图和条形图，更能展示数据的变化趋势


##### 交互界面是否美观、得体（用plotly、pyecharts、网页CSS样式等渠道实现的都包含在内）

- 交互界面配色使用网页css，使整体布局更加明显；
- 字体使用红色和加粗，起到突出的作用；
- 信息准确度和完整度较高，没有因为代码作图而导致数据丢失。

##### 整体数据产品/数据故事的交互设计是否能引导用户探索信息，产生有价值的观点

- 总结在pythonanywhere部署的网站可看，也可在Jupyter notebook做的图表和故事中看到
