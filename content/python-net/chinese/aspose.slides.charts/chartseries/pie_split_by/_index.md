---
title: pie_split_by property
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides.charts/chartseries/pie_split_by/
weight: 340
---
## pie_split_by 属性
指定如何确定哪些数据点位于第二个饼形或柱形
            在 pie-of-pie 或 bar-of-pie 图表上。
            此属性不仅属于此序列，还属于父序列组的所有序列
            组 - 这是相应组属性的投影。因此此属性
            是只读的。
            使用 ParentSeriesGroup 属性来访问父序列组。
            使用 ParentSeriesGroup.PieSplitBy 可读写属性来更改值。
            只读 [`PieSplitType`](/slides/python-net/zh/aspose.slides.charts/piesplittype)。

### 备注

1) 这是属性 ParentSeriesGroup.PieSplitBy 的投影。  
2) 如果属性值为 PieSplitType.Custom，则可以使用 ParentSeriesGroup.PieSplitCustomPoints 属性定义自定义拆分信息。

### 定义:
```python
@property
def pie_split_by(self):
    ...
```

### 另请参见
* 类 [`ChartSeries`](/slides/python-net/zh/aspose.slides.charts/chartseries)
* 枚举 [`PieSplitType`](/slides/python-net/zh/aspose.slides.charts/piesplittype)
* 模块 [`aspose.slides.charts`](/slides/python-net/zh/aspose.slides.charts)
* 库 [`Aspose.Slides`](/slides/python-net)