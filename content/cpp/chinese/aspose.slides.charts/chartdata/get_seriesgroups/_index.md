---
title: get_SeriesGroups()
second_title: Aspose.Slides C++ API 参考
description: 获取系列的组。只读 IChartSeriesGroupCollection.
type: docs
weight: 27
url: /zh/aspose.slides.charts/chartdata/get_seriesgroups/
---
## ChartData::get_SeriesGroups() 方法

获取系列的组。只读 [IChartSeriesGroupCollection](../../ichartseriesgroupcollection/).

```cpp
System::SharedPtr<IChartSeriesGroupCollection> Aspose::Slides::Charts::ChartData::get_SeriesGroups() override
```

## 备注

1) 每个系列组包含具有可组合类型的系列。可组合系列类型的组使用 CombinableSeriesTypesGroup 枚举定义和描述。此外，每个系列组包含绘制在主坐标轴或次坐标轴上的系列（一个组中不会同时出现两种情况）。因此，系列分组的原则是按上述类型组以及主/次绘制类型进行分组。

2) 系列组包含一些对该组中每个系列通用的系列属性（“系列组属性”）。在 [ChartSeriesGroup](../../chartseriesgroup/) 类中，“系列组属性”是可读写的。每个“系列组属性”在 [ChartSeries](../../chartseries/) 类中可以有只读投影。

## 另见

* 类型别名 [SharedPtr](../../../system/sharedptr/)
* 类 [IChartSeriesGroupCollection](../../ichartseriesgroupcollection/)
* 类 [ChartData](../)
* 命名空间 [Aspose::Slides::Charts](../../)
* 库 [Aspose.Slides](../../../)