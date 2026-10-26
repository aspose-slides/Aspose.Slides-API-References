---
title: separator property
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides.charts/datalabelformat/separator/
weight: 110
---
## separator 属性
设置或返回表示图表上数据标签使用的 separator 的 Variant。
读取/写入 **str**。


### 备注

如果此 DataLabelFormat 对象的父对象是 DataLabelCollection（数据标签集合），则此属性获取或设置 DataLabelCollection 集合中新数据标签的 Separator 属性的默认值。将此属性设置为某个值时，也会将该值设置为 DataLabelCollection 集合中所有数据标签的 Separator 属性（即 "DataLabels.DefaultDataLabelFormat.Separator = val;" 会导致所有 DataLabels[i].Separator 等于 val）。

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
* 类 [`DataLabelFormat`](/slides/python-net/zh/aspose.slides.charts/datalabelformat)
* 模块 [`aspose.slides.charts`](/slides/python-net/zh/aspose.slides.charts)
* 库 [`Aspose.Slides`](/slides/python-net)