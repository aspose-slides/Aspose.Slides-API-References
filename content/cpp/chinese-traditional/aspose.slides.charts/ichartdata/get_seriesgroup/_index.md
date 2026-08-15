---
title: get_SeriesGroup()
second_title: Aspose.Slides for C++ API 參考手冊
description: 
type: docs
weight: 222
url: /zh-hant/aspose.slides.charts/ichartdata/get_seriesgroup/
---
## IChartData::get_SeriesGroup(System::SharedPtr\<IChartSeries\>) 方法




```cpp
virtual System::SharedPtr<IChartSeriesGroup> Aspose::Slides::Charts::IChartData::get_SeriesGroup(System::SharedPtr<IChartSeries> ofSeries)=0
```

## IChartData::get_SeriesGroup(int32_t) 方法


傳回在指定索引處的系列組。

```cpp
virtual System::SharedPtr<IChartSeriesGroup> Aspose::Slides::Charts::IChartData::get_SeriesGroup(int32_t index)=0
```

## 備註


1) 每個系列群組包含具有可組合類型的系列。可組合系列類型的群組以 CombinableSeriesTypesGroup enum 定義並描述。且每個系列群組包含的系列會繪製於主要軸或次要軸（同一群組不會同時包含兩者）。因此，系列分組的原則是依上述類型群組以及主要/次要繪製類型進行分組。2) 系列群組包含一些對該群組中每個系列共通的系列屬性（「系列群組屬性」）。「系列群組屬性」在 [ChartSeriesGroup](../../chartseriesgroup/) 類別中是可讀寫的。每個「系列群組屬性」在 [ChartSeries](../../chartseries/) 類別中可以有唯讀的投影。 
## 另請參閱

* 型別別名 [SharedPtr](../../../system/sharedptr/)
* 類別 [IChartSeriesGroup](../../ichartseriesgroup/)
* 類別 [IChartSeries](../../ichartseries/)
* 類別 [IChartData](../)
* 命名空間 [Aspose::Slides::Charts](../../)
* 函式庫 [Aspose.Slides](../../../)