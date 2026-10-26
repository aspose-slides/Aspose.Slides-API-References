---
title: show_label_value_from_cell property
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides.charts/datalabelformat/show_label_value_from_cell/
weight: 150
---
## show_label_value_from_cell 属性
表示指定图表的数据标签单元格值显示行为。 
            True 显示单元格值。 False 隐藏。 
            读写 **bool**。


### 备注

如果此 DataLabelFormat 对象的父对象是 DataLabelCollection 数据标签集合，则此
            属性获取或设置 DataLabelCollection 集合中新数据标签的 ShowLabelValueFromCell 属性的默认值。 
            将此属性设为某值也会将该值设置为 DataLabelCollection 集合中所有数据标签的 ShowLabelValueFromCell 属性 
            （即 “DataLabels.DefaultDataLabelFormat.ShowLabelValueFromCell = val;” 导致 
            所有 DataLabels[i].ShowLabelValueFromCell 等于 val）。


### 定义:
```python
@property
def show_label_value_from_cell(self):
    ...

@show_label_value_from_cell.setter
def show_label_value_from_cell(self, value):
    ...
```


### 另见
* 类 [`DataLabelFormat`](/slides/python-net/zh/aspose.slides.charts/datalabelformat)
* 模块 [`aspose.slides.charts`](/slides/python-net/zh/aspose.slides.charts)
* 库 [`Aspose.Slides`](/slides/python-net)