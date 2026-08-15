---
title: get_SeriesGroup()
second_title: Aspose.Slides for C++ API 參考文件
description: 
type: docs
weight: 222
url: /zh-hant/aspose.slides.charts/chartdata/get_seriesgroup/
---
## ChartData::get_SeriesGroup(System::SharedPtr\<IChartSeries\>) 方法

```cpp
System::SharedPtr<IChartSeriesGroup> Aspose::Slides::Charts::ChartData::get_SeriesGroup(System::SharedPtr<IChartSeries> ofSeries) override
```

## ChartData::get_SeriesGroup(int32_t) 方法

返回指定索引處的系列組。

```cpp
System::SharedPtr<IChartSeriesGroup> Aspose::Slides::Charts::ChartData::get_SeriesGroup(int32_t index) override
```

## 備註

1) 每個系列組包含具有可組合類型的系列。可組合系列類型的組別以 CombinableSeriesTypesGroup 列舉定義並加以說明。此外，每個系列組中的系列會繪製於主坐標軸或次坐標軸（同一組中不會同時出現在兩者）。因此，系列分組的原則是依上述的類型組以及主/次繪製類型進行分組。 2) 系列組包含一些對該組中每個系列皆共通的系列屬性（「系列組屬性」）。「系列組屬性」在 [ChartSeriesGroup](../../chartseriesgroup/) 類別中為可讀寫。每個「系列組屬性」在 [ChartSeries](../../chartseries/) 類別中可以有唯讀的投影。

## 另請參閱

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IChartSeriesGroup](../../ichartseriesgroup/)
* Class [IChartSeries](../../ichartseries/)
* Class [ChartData](../)
* Namespace [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)