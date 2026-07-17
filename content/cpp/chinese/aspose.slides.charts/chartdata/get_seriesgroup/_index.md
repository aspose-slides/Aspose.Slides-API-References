---
title: get_SeriesGroup()
second_title: Aspose.Slides C++ API 参考
description: 
type: docs
weight: 222
url: /zh/aspose.slides.charts/chartdata/get_seriesgroup/
---
## ChartData::get_SeriesGroup(System::SharedPtr\<IChartSeries\>) 方法

```cpp
System::SharedPtr<IChartSeriesGroup> Aspose::Slides::Charts::ChartData::get_SeriesGroup(System::SharedPtr<IChartSeries> ofSeries) override
```

## ChartData::get_SeriesGroup(int32_t) 方法

返回指定索引处的系列组。

```cpp
System::SharedPtr<IChartSeriesGroup> Aspose::Slides::Charts::ChartData::get_SeriesGroup(int32_t index) override
```

## 备注

1) 每个系列组包含具有可组合类型的系列。使用 CombinableSeriesTypesGroup enum 定义并描述可组合系列类型的组。每个系列组还包含绘制在主坐标轴或次坐标轴上的系列（同一组中不会同时出现两种情况）。因此，系列分组的原则是按上述类型组以及主/次坐标轴绘制类型进行分组。 2) 系列组包含一些对组内每个系列都通用的系列属性（"series group properties"）。"series group properties" 在 [ChartSeriesGroup](../../chartseriesgroup/) 类 中是 read/write。每个 "series group properties" 在 [ChartSeries](../../chartseries/) 类 中可以有只读的投影。

## 另见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [IChartSeriesGroup](../../ichartseriesgroup/)
* 类 [IChartSeries](../../ichartseries/)
* 类 [ChartData](../)
* 命名空间 [Aspose::Slides::Charts](../../)
* 库 [Aspose.Slides](../../../)