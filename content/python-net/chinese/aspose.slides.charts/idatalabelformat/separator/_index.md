---
title: separator property
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides.charts/idatalabelformat/separator/
weight: 110
---
## separator 属性
设置或返回一个 Variant，表示图表中数据标签使用的 separator。
读/写 **str**.

### 备注

如果此 DataLabelFormat 对象的父对象是 DataLabelCollection（数据标签集合），则此属性获取或设置 DataLabelCollection 集合中新数据标签的 Separator 属性的默认值。使用该值设置此属性时，也会将此值设置为 DataLabelCollection 集合中所有数据标签的 Separator 属性（即 "DataLabels.DefaultDataLabelFormat.Separator = val;" 导致所有 DataLabels[i].Separator 等于 val）。

### 定义：
```python
@property
def separator(self):
    ...

@separator.setter
def separator(self, value):
    ...
```

### 另见
* 类 [`IDataLabelFormat`](/slides/python-net/zh/aspose.slides.charts/idatalabelformat)
* 模块 [`aspose.slides.charts`](/slides/python-net/zh/aspose.slides.charts)
* 库 [`Aspose.Slides`](/slides/python-net)