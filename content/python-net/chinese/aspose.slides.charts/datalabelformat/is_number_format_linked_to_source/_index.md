---
title: is_number_format_linked_to_source property
second_title: Aspose.Slides for Python via .NET API 参考文档
description: 
type: docs
url: /zh/aspose.slides.charts/datalabelformat/is_number_format_linked_to_source/
weight: 70
---
## is_number_format_linked_to_source property
读/写 **bool**.

### 备注

如果此 DataLabelFormat 对象的父对象是 DataLabelCollection 数据标签集合，则此属性获取或设置 DataLabelCollection 集合中新数据标签的 IsNumberFormatLinkedToSource 属性的默认值。
将此属性设置为某个值时，也会将该值设置为 DataLabelCollection 集合中所有数据标签的 IsNumberFormatLinkedToSource 属性
（例如 "DataLabels.DefaultDataLabelFormat.IsNumberFormatLinkedToSource = val;" 会导致所有 DataLabels[i].IsNumberFormatLinkedToSource 等于 val）。

### 定义:
```python
@property
def is_number_format_linked_to_source(self):
    ...

@is_number_format_linked_to_source.setter
def is_number_format_linked_to_source(self, value):
    ...
```

### 另请参阅
* 类 [`DataLabelFormat`](/slides/python-net/zh/aspose.slides.charts/datalabelformat)
* 模块 [`aspose.slides.charts`](/slides/python-net/zh/aspose.slides.charts)
* 库 [`Aspose.Slides`](/slides/python-net)