---
title: position property
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides.charts/datalabelformat/position/
weight: 90
---
## 位置属性
表示数据标签的位置。
读/写 [`LegendDataLabelPosition`](/slides/python-net/zh/aspose.slides.charts/legenddatalabelposition).

### 备注

如果此 DataLabelFormat 对象的父对象是一个 DataLabelCollection 数据标签集合，则此属性获取或设置 DataLabelCollection 集合中新数据标签的 Position 属性的默认值。
表示 DataLabel 对象的位置。
为此属性设置值时，还会将该值设置为 DataLabelCollection 集合中所有数据标签的 Position 属性。
（例如 "DataLabels.DefaultDataLabelFormat.Position = val;" 会导致所有 DataLabels[i].Position 等于 val。）

### 定义：
```python
@property
def position(self):
    ...

@position.setter
def position(self, value):
    ...
```

### 另请参阅
* 类 [`DataLabelFormat`](/slides/python-net/zh/aspose.slides.charts/datalabelformat)
* 枚举 [`LegendDataLabelPosition`](/slides/python-net/zh/aspose.slides.charts/legenddatalabelposition)
* 模块 [`aspose.slides.charts`](/slides/python-net/zh/aspose.slides.charts)
* 库 [`Aspose.Slides`](/slides/python-net)