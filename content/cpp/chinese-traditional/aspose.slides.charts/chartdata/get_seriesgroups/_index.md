---
title: get_SeriesGroups()
second_title: Aspose.Slides for C++ API 參考
description: 取得系列的群組。唯讀 IChartSeriesGroupCollection.
type: docs
weight: 27
url: /zh-hant/aspose.slides.charts/chartdata/get_seriesgroups/
---
## ChartData::get_SeriesGroups() 方法

取得系列的群組。唯讀 [IChartSeriesGroupCollection](../../ichartseriesgroupcollection/).

```cpp
System::SharedPtr<IChartSeriesGroupCollection> Aspose::Slides::Charts::ChartData::get_SeriesGroups() override
```

## 備註

1) 每個系列群組包含具有可組合類型的系列。可組合系列類型的群組以 CombinableSeriesTypesGroup enum 定義和說明。另外，每個系列群組中的系列會繪製在主座標軸或次座標軸上（不會在同一群組同時出現在兩者）。因此，系列分組的原則是依上述類型群組以及主/次繪製類型進行分組。

2) 系列群組包含一些對該群組中每個系列皆通用的系列屬性（「系列群組屬性」）。在 [ChartSeriesGroup](../../chartseriesgroup/) 類別中，「系列群組屬性」是讀寫的。每個「系列群組屬性」在 [ChartSeries](../../chartseries/) 類別中可以有唯讀的投影。

## 另請參閱

* Typedef [SharedPtr](../../../system/sharedptr/)
* 類別 [IChartSeriesGroupCollection](../../ichartseriesgroupcollection/)
* 類別 [ChartData](../)
* 命名空間 [Aspose::Slides::Charts](../../)
* 函式庫 [Aspose.Slides](../../../)