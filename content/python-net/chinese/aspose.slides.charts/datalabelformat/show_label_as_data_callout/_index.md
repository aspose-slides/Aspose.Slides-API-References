---
title: show_label_as_data_callout property
second_title: Aspose.Slides 用于 Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides.charts/datalabelformat/show_label_as_data_callout/
weight: 140
---
## show_label_as_data_callout 属性
确定指定图表的数据标签是显示为数据标注线还是显示为数据标签。

如果此 DataLabelFormat 对象的父对象是 DataLabelCollection 数据标签集合，则该
            属性获取或设置 ShowLabelAsDataCallout 属性的默认值，用于新数据 
            标签在 DataLabelCollection 集合中。
将此属性设置为某个值时，同样会将该值设置为 DataLabelCollection 中所有数据标签的 ShowLabelAsDataCallout 属性
            （即 "DataLabels.DefaultDataLabelFormat.ShowLabelAsDataCallout = val;" 会导致
            所有 DataLabels[i].ShowLabelAsDataCallout 等于 val）。

### 定义:
```python
@property
def show_label_as_data_callout(self):
    ...

@show_label_as_data_callout.setter
def show_label_as_data_callout(self, value):
    ...
```

### 另见
* 类 [`DataLabelFormat`](/slides/python-net/zh/aspose.slides.charts/datalabelformat)
* 模块 [`aspose.slides.charts`](/slides/python-net/zh/aspose.slides.charts)
* 库 [`Aspose.Slides`](/slides/python-net)