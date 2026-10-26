---
title: series_groups property
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides.charts/chartdata/series_groups/
weight: 140
---
## series_groups 属性
获取系列的分组。
只读 [`IChartSeriesGroupCollection`](/slides/python-net/zh/aspose.slides.charts/ichartseriesgroupcollection).

### 备注

1) 每个系列组包含具有可组合类型的系列。可组合系列类型的组由 CombinableSeriesTypesGroup 枚举定义并描述。  
此外，每个系列组包含在主轴或次轴上绘制的系列（同一组中不会同时出现两种情况）。因此，系列分组的原则是按照上述类型组以及主/次绘图类型进行分组。

2) 系列组包含一些对组中每个系列通用的系列属性（“series group properties”）。  
ChartSeriesGroup 类中的 “Series group properties” 为读/写。  
每个 “series group properties” 可以在 ChartSeries 类中具有只读投影。

### 定义:
```python
@property
def series_groups(self):
    ...
```

### 另请参见
* 类 [`ChartData`](/slides/python-net/zh/aspose.slides.charts/chartdata)
* 类 [`IChartSeriesGroupCollection`](/slides/python-net/zh/aspose.slides.charts/ichartseriesgroupcollection)
* 模块 [`aspose.slides.charts`](/slides/python-net/zh/aspose.slides.charts)
* 库 [`Aspose.Slides`](/slides/python-net)