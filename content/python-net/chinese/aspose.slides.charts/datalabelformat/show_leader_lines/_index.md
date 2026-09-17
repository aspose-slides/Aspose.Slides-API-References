---
title: show_leader_lines property
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides.charts/datalabelformat/show_leader_lines/
weight: 160
---
## show_leader_lines 属性
表示指定图表的数据标签引导线的显示行为。 
            True 表示显示引导线，False 表示隐藏。
            读/写 **bool**。


### 备注

如果此 DataLabelFormat 对象的父对象是 DataLabelCollection 数据标签集合，则此属性获取或设置 DataLabelCollection 集合中新数据标签的 ShowLeaderLines 属性的默认值。 
            使用该值设置此属性也会将此值设置为 DataLabelCollection 集合中所有数据标签的 ShowLeaderLines 属性 (i.e. "DataLabels.DefaultDataLabelFormat.ShowLeaderLines = val;" cause to 
            all DataLabels[i].ShowLeaderLines is equal to val)。

### 定义:
```python
@property
def show_leader_lines(self):
    ...

@show_leader_lines.setter
def show_leader_lines(self, value):
    ...
```


### 另见
* 类 [`DataLabelFormat`](/slides/python-net/zh/aspose.slides.charts/datalabelformat)
* 模块 [`aspose.slides.charts`](/slides/python-net/zh/aspose.slides.charts)
* 库 [`Aspose.Slides`](/slides/python-net)