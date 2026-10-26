---
title: number_format property
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides.charts/datalabelformat/number_format/
weight: 80
---
## number_format 属性
表示 DataLabels 对象的格式字符串。  
读/写 **str**.

### 备注

如果此 DataLabelFormat 对象的父对象是 DataLabelCollection 数据标签集合，则此属性获取或设置 NumberFormat 属性在 DataLabelCollection 集合中新数据标签的默认值。当此属性被赋值时，该值同样会被设置为 DataLabelCollection 集合中所有数据标签的 NumberFormat 属性的值 (即 "DataLabels.DefaultDataLabelFormat.NumberFormat = val;" 会导致所有 DataLabels[i].NumberFormat 等于 val)。

### 定义：
```python
@property
def number_format(self):
    ...

@number_format.setter
def number_format(self, value):
    ...
```

### 参见
* 类 [`DataLabelFormat`](/slides/python-net/zh/aspose.slides.charts/datalabelformat)
* 模块 [`aspose.slides.charts`](/slides/python-net/zh/aspose.slides.charts)
* 库 [`Aspose.Slides`](/slides/python-net)