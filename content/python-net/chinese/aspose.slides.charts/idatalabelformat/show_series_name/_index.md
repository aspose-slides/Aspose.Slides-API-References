---
title: show_series_name property
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides.charts/idatalabelformat/show_series_name/
weight: 190
---
## show_series_name 属性
返回或设置一个布尔值，以指示图表上数据标签的系列名称显示行为。 
True 表示显示系列名称。False 表示隐藏。 
读/写 **bool**。


### 备注

如果此 DataLabelFormat 对象的父对象是一个 DataLabelCollection 数据标签集合，则此属性获取或设置 DataLabelCollection 中新数据标签的 ShowSeriesName 属性的默认值。 
使用该属性的值还会将此值设置为 DataLabelCollection 中所有数据标签的 ShowSeriesName 属性 
（即 “DataLabels.DefaultDataLabelFormat.ShowSeriesName = val;” 导致所有 DataLabels[i].ShowSeriesName 等于 val）。

### 定义：
```python
@property
def show_series_name(self):
    ...

@show_series_name.setter
def show_series_name(self, value):
    ...
```


### 参见
* 类 [`IDataLabelFormat`](/slides/python-net/zh/aspose.slides.charts/idatalabelformat)
* 模块 [`aspose.slides.charts`](/slides/python-net/zh/aspose.slides.charts)
* 库 [`Aspose.Slides`](/slides/python-net)