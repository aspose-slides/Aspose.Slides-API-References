---
title: show_percentage property
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides.charts/datalabelformat/show_percentage/
weight: 180
---
## show_percentage 属性
表示指定图表的数据标签百分比值的显示行为。  
True 显示百分比值。False 隐藏。  
读/写 **bool**。


### 备注

如果此 DataLabelFormat 对象的父对象是 DataLabelCollection 数据标签集合，则此属性获取或设置 DataLabelCollection 集合中新数据标签的 ShowPercentage 属性的默认值。  
使用该值设置此属性也会将此值设置到 DataLabelCollection 集合中所有数据标签的 ShowPercentage 属性（即 "DataLabels.DefaultDataLabelFormat.ShowPercentage = val;" 会导致所有 DataLabels[i].ShowPercentage 等于 val）。

### 定义：
```python
@property
def show_percentage(self):
    ...

@show_percentage.setter
def show_percentage(self, value):
    ...
```


### 另见
* 类 [`DataLabelFormat`](/slides/python-net/zh/aspose.slides.charts/datalabelformat)
* 模块 [`aspose.slides.charts`](/slides/python-net/zh/aspose.slides.charts)
* 库 [`Aspose.Slides`](/slides/python-net)