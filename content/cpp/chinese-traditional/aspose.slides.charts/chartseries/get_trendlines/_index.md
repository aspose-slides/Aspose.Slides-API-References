---
title: get_TrendLines()
second_title: Aspose.Slides for C++ API 參考
description: 系列趨勢線的集合。唯讀 ITrendlineCollection.
type: docs
weight: 209
url: /zh-hant/aspose.slides.charts/chartseries/get_trendlines/
---
## ChartSeries::get_TrendLines() 方法

系列趨勢線的集合。唯讀 [ITrendlineCollection](../../itrendlinecollection/)。

```cpp
System::SharedPtr<ITrendlineCollection> Aspose::Slides::Charts::ChartSeries::get_TrendLines() override
```

## 備註

TrendLines 在未堆疊的 2-D 面積圖、長條圖、柱狀圖、折線圖、股票圖、xy（散佈圖）以及氣泡圖中可用（非 null）。在任何已堆疊或 3-D 的圖表類型中，trendline 均不可用。TrendLines 也不可用於雷達圖、圓餅圖、曲面圖或甜甜圈圖。

## 另請參閱

* Typedef [SharedPtr](../../../system/sharedptr/)
* 類別 [ITrendlineCollection](../../itrendlinecollection/)
* 類別 [ChartSeries](../)
* 命名空間 [Aspose::Slides::Charts](../../)
* 函式庫 [Aspose.Slides](../../../)