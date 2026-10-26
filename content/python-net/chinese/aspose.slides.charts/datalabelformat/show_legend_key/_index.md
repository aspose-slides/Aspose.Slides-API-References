---
title: show_legend_key property
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides.charts/datalabelformat/show_legend_key/
weight: 170
---
## show_legend_key 属性
表示指定图表的数据标签图例键的显示行为。 
            如果数据标签图例键可见，则为 True。 
            读/写 **bool**.

### Remarks

如果此 DataLabelFormat 对象的父对象是 DataLabelCollection 数据标签集合，则此
            属性获取或设置新数据的 ShowLegendKey 属性的默认值，用于 DataLabelCollection 集合中
            的标签。 
            使用该值设置此属性也会将此值设置到 ShowLegendKey 属性 
            用于 DataLabelCollection 集合中的所有数据标签
            (例如 "DataLabels.DefaultDataLabelFormat.ShowLegendKey = val;" 会导致 
            所有 DataLabels[i].ShowLegendKey 等于 val)。

### 定义：
```python
@property
def show_legend_key(self):
    ...

@show_legend_key.setter
def show_legend_key(self, value):
    ...
```

### 参见
* 类 [`DataLabelFormat`](/slides/python-net/zh/aspose.slides.charts/datalabelformat)
* 模块 [`aspose.slides.charts`](/slides/python-net/zh/aspose.slides.charts)
* 库 [`Aspose.Slides`](/slides/python-net)