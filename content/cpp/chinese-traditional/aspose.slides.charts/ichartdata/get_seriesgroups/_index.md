---
title: get_SeriesGroups()
second_title: Aspose.Slides for C++ API 參考
description: 取得系列的群組。唯讀 IChartSeriesGroupCollection.
type: docs
weight: 27
url: /zh-hant/aspose.slides.charts/ichartdata/get_seriesgroups/
---
## IChartData::get_SeriesGroups() 方法

取得系列的群組。唯讀 [IChartSeriesGroupCollection](../../ichartseriesgroupcollection/)。

```cpp
virtual System::SharedPtr<IChartSeriesGroupCollection> Aspose::Slides::Charts::IChartData::get_SeriesGroups()=0
```

## 備註

1) 每個系列群組包含具有可組合類型的系列。可組合系列類型的群組是使用 CombinableSeriesTypesGroup enum 定義並說明的。此外，每個系列群組包含的系列會繪製於主坐標軸或次坐標軸（同一群組不會同時在兩者上）。因此，系列分組的原則是根據上述的類型群組以及主/次繪製類型進行分組。

2) 系列群組包含一些對每個群組內系列共用的系列屬性（「series group properties」）。在 [ChartSeriesGroup](../../chartseriesgroup/) 類別中的「Series group properties」為可讀寫。每個「series group properties」在 [ChartSeries](../../chartseries/) 類別中可以有唯讀的投影。

## 另見

* Typedef [SharedPtr](../../../system/sharedptr/)
* 類別 [IChartSeriesGroupCollection](../../ichartseriesgroupcollection/)
* 類別 [IChartData](../)
* 命名空間 [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)