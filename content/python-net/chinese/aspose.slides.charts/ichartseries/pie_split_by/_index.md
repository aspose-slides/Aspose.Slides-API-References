---
title: pie_split_by property
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides.charts/ichartseries/pie_split_by/
weight: 340
---
## pie_split_by 属性
指定如何确定哪些数据点位于第二个饼形或条形 
            适用于 pie-of-pie 或 bar-of-pie 图表。
            此属性不仅属于此序列，还属于父系列组的所有序列 
            group - 这是相应组属性的投影。因此此属性 
            为只读。
            使用 ParentSeriesGroup 属性访问父系列组。
            使用 ParentSeriesGroup.PieSplitBy 可读写属性来更改值。
            只读 [`PieSplitType`](/slides/python-net/zh/aspose.slides.charts/piesplittype).

### 备注

1) 这是属性 ParentSeriesGroup.PieSplitBy 的投影。
            2) 如果属性值为 PieSplitType.Custom，则可以定义自定义拆分 
            使用 ParentSeriesGroup.PieSplitCustomPoints 属性。

### 定义：
```python
@property
def pie_split_by(self):
    ...
```

### 另见
* 类 [`IChartSeries`](/slides/python-net/zh/aspose.slides.charts/ichartseries)
* 枚举 [`PieSplitType`](/slides/python-net/zh/aspose.slides.charts/piesplittype)
* 模块 [`aspose.slides.charts`](/slides/python-net/zh/aspose.slides.charts)
* 库 [`Aspose.Slides`](/slides/python-net)