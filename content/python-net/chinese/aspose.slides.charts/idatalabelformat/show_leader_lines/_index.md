---
title: show_leader_lines property
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides.charts/idatalabelformat/show_leader_lines/
weight: 160
---
## show_leader_lines 属性
表示指定 chart 的 data label leader lines 显示行为。 
True 显示 leader lines。 False 隐藏。 
读/写 **bool**。

### 备注

If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this 属性 gets or sets the default value of the ShowLeaderLines 属性 for the new data 
labels in the DataLabelCollection collection.
Set this 属性 with value also sets this value to the ShowLeaderLines 属性 
for all data labels in the DataLabelCollection collection
(i.e. "DataLabels.DefaultDataLabelFormat.ShowLeaderLines = val;" cause to 
all DataLabels[i].ShowLeaderLines is equal to val).

### 定义:
```python
@property
def show_leader_lines(self):
    ...

@show_leader_lines.setter
def show_leader_lines(self, value):
    ...
```

### 另请参阅
* 类 [`IDataLabelFormat`](/slides/python-net/zh/aspose.slides.charts/idatalabelformat)
* 模块 [`aspose.slides.charts`](/slides/python-net/zh/aspose.slides.charts)
* 库 [`Aspose.Slides`](/slides/python-net)