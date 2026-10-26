---
title: overlap property
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides.charts/ichartseries/overlap/
weight: 310
---
## 重叠属性
Specifies how much bars and columns overlap on 2-D charts, as a percentage (from -100% to 100%). 
            This is the property not only of this series but of all series of parent series group. 
            It is a projection of the appropriate property in the parent series group, and so this property is Read-only.
            To change the value, use the ParentSeriesGroup.Overlap 读/写 property.
            只读 **int**.


### 备注

Overlap specifies the degree of overlap or spacing between bars and columns as a percentage of their width:
            - -100%: 最大间距（bars 完全分离）。
            - 0%: Bars 并排放置，没有重叠或间距。
            - 100%: 最大重叠（bars 完全相互重叠）。
            This is a projection of the property ParentSeriesGroup.Overlap.

### 定义:
```python
@property
def overlap(self):
    ...
```


### 另见
* 类 [`IChartSeries`](/slides/python-net/zh/aspose.slides.charts/ichartseries)
* 模块 [`aspose.slides.charts`](/slides/python-net/zh/aspose.slides.charts)
* 库 [`Aspose.Slides`](/slides/python-net)