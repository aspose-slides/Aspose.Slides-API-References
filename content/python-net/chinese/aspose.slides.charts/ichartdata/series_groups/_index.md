---
title: series_groups property
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides.charts/ichartdata/series_groups/
weight: 140
---
## series_groups 属性
获取系列的分组。
只读 [`IChartSeriesGroupCollection`](/slides/python-net/zh/aspose.slides.charts/ichartseriesgroupcollection)。


### 备注

1) 每个系列组包含具有可组合类型的系列。可组合系列类型的组使用 CombinableSeriesTypesGroup 枚举定义和描述。另且每个系列组包含的系列会绘制在主坐标轴或次坐标轴上（同一个组中不会同时出现两种情况）。因此，系列分组的原则是按上述类型组以及主/次绘图类型进行分组。

2) 系列组包含一些对组内每个系列都通用的系列属性（“系列组属性”）。ChartSeriesGroup 类中的 “系列组属性” 是可读写的。每个 “系列组属性” 在 ChartSeries 类中可以有只读的投影。

### 定义:
```python
@property
def series_groups(self):
    ...
```


### 另见
* 类 [`IChartData`](/slides/python-net/zh/aspose.slides.charts/ichartdata)
* 类 [`IChartSeriesGroupCollection`](/slides/python-net/zh/aspose.slides.charts/ichartseriesgroupcollection)
* 模块 [`aspose.slides.charts`](/slides/python-net/zh/aspose.slides.charts)
* 库 [`Aspose.Slides`](/slides/python-net)