---
title: has_series_lines property
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides.charts/ichartseries/has_series_lines/
weight: 180
---
## has_series_lines 属性
确定此系列及相关系列是否有系列线。
这不仅是此系列的属性，也是父系列组中所有系列的属性——这是相应组属性的投影。因此此属性为只读。
使用 ParentSeriesGroup 属性访问父系列组。
使用 ParentSeriesGroup.HasSeriesLines 读写属性来更改值。
使用 ParentSeriesGroup.SeriesLinesFormat 属性来设置系列线的格式。
只读 **bool**。

### 备注

这是属性 ParentSeriesGroup.HasSeriesLines 的投影。

### 定义：
```python
@property
def has_series_lines(self):
    ...
```

### 另见
* 类 [`IChartSeries`](/slides/python-net/zh/aspose.slides.charts/ichartseries)
* 模块 [`aspose.slides.charts`](/slides/python-net/zh/aspose.slides.charts)
* 库 [`Aspose.Slides`](/slides/python-net)