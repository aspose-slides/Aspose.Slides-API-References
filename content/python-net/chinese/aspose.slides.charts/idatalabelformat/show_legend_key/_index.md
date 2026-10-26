---
title: show_legend_key property
second_title: Aspose.Slides 用于 Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides.charts/idatalabelformat/show_legend_key/
weight: 170
---
## show_legend_key 属性
表示指定图表的数据标签图例键的显示行为。 
            True if the data label legend key is visible.
            读/写 **bool**.


### 备注

如果此 DataLabelFormat 对象的父对象是 DataLabelCollection（数据标签集合），则此属性获取或设置 DataLabelCollection 中新数据标签的 ShowLegendKey 属性的默认值。 
            使用该值设置此属性时，也会将此值设置为 DataLabelCollection 中所有数据标签的 ShowLegendKey 属性（例如 "DataLabels.DefaultDataLabelFormat.ShowLegendKey = val;" 导致所有 DataLabels[i].ShowLegendKey 等于 val）。

### 定义:
```python
@property
def show_legend_key(self):
    ...

@show_legend_key.setter
def show_legend_key(self, value):
    ...
```


### 另请参见
* 类 [`IDataLabelFormat`](/slides/python-net/zh/aspose.slides.charts/idatalabelformat)
* 模块 [`aspose.slides.charts`](/slides/python-net/zh/aspose.slides.charts)
* 库 [`Aspose.Slides`](/slides/python-net)