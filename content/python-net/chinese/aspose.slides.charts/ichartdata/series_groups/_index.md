---
title: series_groups property
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides.charts/ichartdata/series_groups/
weight: 150
---
## series_groups 属性
获取系列的组。
            只读 [`IChartSeriesGroupCollection`](/slides/python-net/zh/aspose.slides.charts/ichartseriesgroupcollection)。


### 备注

1) 每个系列组包含具有可组合类型的系列。可组合系列类型的组由 
            CombinableSeriesTypesGroup 枚举定义和描述。
            同时，每个系列组包含的系列可以绘制在主坐标轴上或次坐标轴上（同一组中不同时出现两者）。
            因此，系列分组的原则是按照上述类型组以及主/次坐标轴绘制类型进行分组。
            
2) 系列组包含一些对组内每个系列通用的 series group properties（“series group properties”）。
            ChartSeriesGroup 类中的 “Series group properties” 为读写。
            每个 “Series group properties” 在 ChartSeries 类中可以有只读的投影。

### 定义:
```python
@property
def series_groups(self):
    ...
```


### 另请参阅
* 类 [`IChartData`](/slides/python-net/zh/aspose.slides.charts/ichartdata)
* 类 [`IChartSeriesGroupCollection`](/slides/python-net/zh/aspose.slides.charts/ichartseriesgroupcollection)
* 模块 [`aspose.slides.charts`](/slides/python-net/zh/aspose.slides.charts)
* 库 [`Aspose.Slides`](/slides/python-net)