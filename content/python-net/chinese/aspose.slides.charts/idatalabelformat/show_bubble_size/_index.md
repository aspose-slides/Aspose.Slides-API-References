---
title: show_bubble_size property
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides.charts/idatalabelformat/show_bubble_size/
weight: 120
---
## show_bubble_size 属性
表示指定图表的数据标签气泡大小值的显示行为。 
True 显示气泡大小值。False 隐藏。 
读/写 **bool**。


### 备注

如果此 DataLabelFormat 对象的父对象是 DataLabelCollection（数据标签集合），则此属性获取或设置 DataLabelCollection 中新数据标签的 ShowBubbleSize 属性的默认值。 使用该属性设置值时，也会将此值设置为 DataLabelCollection 中所有数据标签的 ShowBubbleSize 属性（即 "DataLabels.DefaultDataLabelFormat.ShowBubbleSize = val;" cause to all DataLabels[i].ShowBubbleSize is equal to val）。


### 定义：
```python
@property
def show_bubble_size(self):
    ...

@show_bubble_size.setter
def show_bubble_size(self, value):
    ...
```


### 另见
* 类 [`IDataLabelFormat`](/slides/python-net/zh/aspose.slides.charts/idatalabelformat)
* 模块 [`aspose.slides.charts`](/slides/python-net/zh/aspose.slides.charts)
* 库 [`Aspose.Slides`](/slides/python-net)