---
title: series_groups property
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides.charts/chartdata/series_groups/
weight: 150
---
## series_groups 属性
获取系列的组。
只读 [`IChartSeriesGroupCollection`](/slides/python-net/zh/aspose.slides.charts/ichartseriesgroupcollection)。

### 备注

1) 每个系列组包含具有可组合类型的系列。可组合系列类型的组使用 CombinableSeriesTypesGroup 枚举定义和描述。  
此外，每个系列组包含在主坐标轴或次坐标轴上绘制的系列（同一组中不会出现两者同时绘制的情况）。  
因此，系列分组的原则是按上述类型组以及主/次绘制类型进行分组。

2) 系列组包含一些对组内每个系列都通用的系列属性（“series group properties”）。  
ChartSeriesGroup 类中的 “Series group properties” 是读/写。  
每个 “series group properties” 在 ChartSeries 类中可以有只读的投影。

### 定义：
```python
@property
def series_groups(self):
    ...
```

### 另见
* 类 [`ChartData`](/slides/python-net/zh/aspose.slides.charts/chartdata)
* 类 [`IChartSeriesGroupCollection`](/slides/python-net/zh/aspose.slides.charts/ichartseriesgroupcollection)
* 模块 [`aspose.slides.charts`](/slides/python-net/zh/aspose.slides.charts)
* 库 [`Aspose.Slides`](/slides/python-net)