---
title: get_SeriesGroup()
second_title: Aspose.Slides for C++ API 参考
description: 
type: docs
weight: 222
url: /zh/aspose.slides.charts/ichartdata/get_seriesgroup/
---
## IChartData::get_SeriesGroup(System::SharedPtr\<IChartSeries\>) 方法

```cpp
virtual System::SharedPtr<IChartSeriesGroup> Aspose::Slides::Charts::IChartData::get_SeriesGroup(System::SharedPtr<IChartSeries> ofSeries)=0
```

## IChartData::get_SeriesGroup(int32_t) 方法

返回指定索引处的系列组。

```cpp
virtual System::SharedPtr<IChartSeriesGroup> Aspose::Slides::Charts::IChartData::get_SeriesGroup(int32_t index)=0
```

## 备注

1) 每个系列组包含具有可组合类型的系列。使用 CombinableSeriesTypesGroup 枚举定义并描述可组合系列类型的组。每个系列组还包含在主坐标轴或次坐标轴上绘制的系列（同一组中不会同时出现两种情况）。因此，系列分组的原则是按上述类型组以及主/次绘图类型进行分组。2) 系列组包含一些对组内每个系列通用的系列属性（\"series group properties\"）。[ChartSeriesGroup](../../chartseriesgroup/) 类中的 \"Series group properties\" 为读写。每个 \"series group properties\" 在 [ChartSeries](../../chartseries/) 类中可以有只读的投影。

## 参见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [IChartSeriesGroup](../../ichartseriesgroup/)
* 类 [IChartSeries](../../ichartseries/)
* 类 [IChartData](../)
* 命名空间 [Aspose::Slides::Charts](../../)
* 库 [Aspose.Slides](../../../)