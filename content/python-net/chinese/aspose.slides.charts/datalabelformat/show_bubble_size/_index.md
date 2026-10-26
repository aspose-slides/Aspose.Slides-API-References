---
title: show_bubble_size property
second_title: Aspose.Slides 用于 Python 的 .NET API 参考
description: 
type: docs
url: /zh/aspose.slides.charts/datalabelformat/show_bubble_size/
weight: 120
---
## show_bubble_size 属性
表示指定图表的数据标签气泡大小值的显示行为。 
True 显示气泡大小值。False 隐藏。读/写 **bool**。


### 备注

如果此 DataLabelFormat 对象的父对象是 DataLabelCollection 数据标签集合，则此属性获取或设置 DataLabelCollection 集合中新数据标签的 ShowBubbleSize 属性的默认值。  
将此属性设为某值也会将该值设置为 DataLabelCollection 集合中所有数据标签的 ShowBubbleSize 属性（即 "DataLabels.DefaultDataLabelFormat.ShowBubbleSize = val;" 导致所有 DataLabels[i].ShowBubbleSize 等于 val）。


### 定义:
```python
@property
def show_bubble_size(self):
    ...

@show_bubble_size.setter
def show_bubble_size(self, value):
    ...
```


### 另请参见
* 类 [`DataLabelFormat`](/slides/python-net/zh/aspose.slides.charts/datalabelformat)
* 模块 [`aspose.slides.charts`](/slides/python-net/zh/aspose.slides.charts)
* 库 [`Aspose.Slides`](/slides/python-net)