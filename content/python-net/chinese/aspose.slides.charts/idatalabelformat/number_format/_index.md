---
title: number_format property
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides.charts/idatalabelformat/number_format/
weight: 80
---
## number_format property
表示 DataLabels 对象的格式字符串。
            读/写 **str**。


### 备注

如果此 DataLabelFormat 对象的父对象是 DataLabelCollection（数据标签的集合），则此
            属性获取或设置新数据标签在 DataLabelCollection 集合中的 NumberFormat 属性的默认值。
            当此属性被设置为某个值时，该值也会为 DataLabelCollection 中所有数据标签的 NumberFormat 属性设置相同的值
            （即 "DataLabels.DefaultDataLabelFormat.NumberFormat = val;" 导致所有 DataLabels[i].NumberFormat 等于 val）。

### 定义：
```python
@property
def number_format(self):
    ...

@number_format.setter
def number_format(self, value):
    ...
```


### 另见
* 类 [`IDataLabelFormat`](/slides/python-net/zh/aspose.slides.charts/idatalabelformat)
* 模块 [`aspose.slides.charts`](/slides/python-net/zh/aspose.slides.charts)
* 库 [`Aspose.Slides`](/slides/python-net)