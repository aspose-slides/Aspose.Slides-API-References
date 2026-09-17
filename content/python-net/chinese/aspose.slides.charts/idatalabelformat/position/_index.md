---
title: position property
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides.charts/idatalabelformat/position/
weight: 90
---
## position 属性
表示数据标签的 position。
            读/写 [`LegendDataLabelPosition`](/slides/python-net/zh/aspose.slides.charts/legenddatalabelposition)。


### 备注

如果此 DataLabelFormat 对象的父对象是 DataLabelCollection 数据标签集合，则此
            属性获取或设置 DataLabelCollection 集合中新建数据标签的 Position 属性的默认值。
            表示 DataLabel 对象的 position。
            设置此属性的值时，同样会将该值设置为 DataLabelCollection 集合中所有数据标签的 Position 属性 (即 "DataLabels.DefaultDataLabelFormat.Position = val;" 导致所有 DataLabels[i].Position 等于 val)。

### 定义：
```python
@property
def position(self):
    ...

@position.setter
def position(self, value):
    ...
```


### 另请参见
* 类 [`IDataLabelFormat`](/slides/python-net/zh/aspose.slides.charts/idatalabelformat)
* 枚举 [`LegendDataLabelPosition`](/slides/python-net/zh/aspose.slides.charts/legenddatalabelposition)
* 模块 [`aspose.slides.charts`](/slides/python-net/zh/aspose.slides.charts)
* 库 [`Aspose.Slides`](/slides/python-net)