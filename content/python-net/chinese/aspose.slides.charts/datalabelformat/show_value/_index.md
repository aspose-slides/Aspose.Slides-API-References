---
title: show_value property
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides.charts/datalabelformat/show_value/
weight: 200
---
## show_value 属性
表示指定图表的数据标签百分比值显示行为。 
            True 显示百分比值。False 隐藏。
            读/写 **bool**.


### 备注

如果此 DataLabelFormat 对象的父对象是 DataLabelCollection 数据标签集合，则此
            属性获取或设置 DataLabelCollection 集合中新数据标签的 ShowValue 属性的默认值。
            设置此属性的值还会将该值设置为 DataLabelCollection 集合中所有数据标签的 ShowValue 属性
            （例如 "DataLabels.DefaultDataLabelFormat.ShowValue = val;" 会导致
            所有 DataLabels[i].ShowValue 等于 val）。

### 定义：
```python
@property
def show_value(self):
    ...

@show_value.setter
def show_value(self, value):
    ...
```


### 另见
* 类 [`DataLabelFormat`](/slides/python-net/zh/aspose.slides.charts/datalabelformat)
* 模块 [`aspose.slides.charts`](/slides/python-net/zh/aspose.slides.charts)
* 库 [`Aspose.Slides`](/slides/python-net)