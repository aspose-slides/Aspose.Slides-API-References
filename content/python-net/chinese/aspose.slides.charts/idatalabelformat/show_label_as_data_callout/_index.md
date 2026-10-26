---
title: show_label_as_data_callout property
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides.charts/idatalabelformat/show_label_as_data_callout/
weight: 140
---
## show_label_as_data_callout 属性
确定指定图表的数据标签是显示为数据标注还是显示为数据标签。

如果此 DataLabelFormat 对象的父对象是 DataLabelCollection（数据标签集合），则此属性获取或设置 DataLabelCollection 中新数据标签的 ShowLabelAsDataCallout 属性的默认值。

将此属性设置为某个值时，也会将该值设置到 DataLabelCollection 中所有数据标签的 ShowLabelAsDataCallout 属性上（即 "DataLabels.DefaultDataLabelFormat.ShowLabelAsDataCallout = val;" 会导致所有 DataLabels[i].ShowLabelAsDataCallout 等于 val）。

### 定义:
```python
@property
def show_label_as_data_callout(self):
    ...

@show_label_as_data_callout.setter
def show_label_as_data_callout(self, value):
    ...
```

### 另请参见
* 类 [`IDataLabelFormat`](/slides/python-net/zh/aspose.slides.charts/idatalabelformat)
* 模块 [`aspose.slides.charts`](/slides/python-net/zh/aspose.slides.charts)
* 库 [`Aspose.Slides`](/slides/python-net)