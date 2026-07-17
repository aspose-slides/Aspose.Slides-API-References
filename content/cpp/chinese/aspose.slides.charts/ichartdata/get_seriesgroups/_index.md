---
title: get_SeriesGroups()
second_title: Aspose.Slides for C++ API 参考
description: 获取系列的组。只读 IChartSeriesGroupCollection.
type: docs
weight: 27
url: /zh/aspose.slides.charts/ichartdata/get_seriesgroups/
---
## IChartData::get_SeriesGroups() 方法

获取系列的组。只读 [IChartSeriesGroupCollection](../../ichartseriesgroupcollection/).

```cpp
virtual System::SharedPtr<IChartSeriesGroupCollection> Aspose::Slides::Charts::IChartData::get_SeriesGroups()=0
```

## 备注

1) 每个系列组包含具有可组合类型的系列。可组合系列类型的组由 CombinableSeriesTypesGroup 枚举定义并描述。并且每个系列组包含绘制在主坐标轴或次坐标轴上的系列（同一组中不会同时出现两者）。因此，系列分组的原则是按照上述类型组以及主/次绘图类型进行分组。

2) 系列组包含一些对组中每个系列通用的系列属性（“series group properties”）。[ChartSeriesGroup](../../chartseriesgroup/) 类中的 “Series group properties” 为读写。每个 “series group properties” 在 [ChartSeries](../../chartseries/) 类中可以有只读的投影。

## 另见

* 类型别名 [SharedPtr](../../../system/sharedptr/)
* 类 [IChartSeriesGroupCollection](../../ichartseriesgroupcollection/)
* 类 [IChartData](../)
* 命名空间 [Aspose::Slides::Charts](../../)
* 库 [Aspose.Slides](../../../)