---
title: is_number_format_linked_to_source property
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides.charts/idatalabelformat/is_number_format_linked_to_source/
weight: 70
---
## is_number_format_linked_to_source 属性
读/写 **bool**.

### 备注

如果此 DataLabelFormat 对象的父对象是一个数据标签的 DataLabelCollection 集合，则此属性获取或设置 DataLabelCollection 集合中新数据标签的 IsNumberFormatLinkedToSource 属性的默认值。使用该值设置此属性时，还会将该值设置为 DataLabelCollection 集合中所有数据标签的 IsNumberFormatLinkedToSource 属性。(即 "DataLabels.DefaultDataLabelFormat.IsNumberFormatLinkedToSource = val;" 会导致所有 DataLabels[i].IsNumberFormatLinkedToSource 等于 val)。

### 定义:
```python
@property
def is_number_format_linked_to_source(self):
    ...

@is_number_format_linked_to_source.setter
def is_number_format_linked_to_source(self, value):
    ...
```

### 另见
* 类 [`IDataLabelFormat`](/slides/python-net/zh/aspose.slides.charts/idatalabelformat)
* 模块 [`aspose.slides.charts`](/slides/python-net/zh/aspose.slides.charts)
* 库 [`Aspose.Slides`](/slides/python-net)