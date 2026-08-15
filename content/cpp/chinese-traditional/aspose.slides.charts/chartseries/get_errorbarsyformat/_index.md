---
title: get_ErrorBarsYFormat()
second_title: Aspose.Slides for C++ API 參考
description: 代表具有 Y 方向的系列的 ErrorBars。
type: docs
weight: 235
url: /zh-hant/aspose.slides.charts/chartseries/get_errorbarsyformat/
---
## ChartSeries::get_ErrorBarsYFormat() 方法

代表具有 Y 方向的系列的 ErrorBars。

```cpp
System::SharedPtr<IErrorBarsFormat> Aspose::Slides::Charts::ChartSeries::get_ErrorBarsYFormat() override
```

## 備註

具有 Y 方向的 ErrorBars 可用於類型為 area、bar、line、scatter 和 bubble 的系列。對於其他任何類型的圖表，此屬性將返回 null（包括 3D 圖表）。若使用自訂值，請使用 DataPoints 集合指定值（使用 [IChartDataPoint::get_ErrorBarsCustomValues()](../../ichartdatapoint/get_errorbarscustomvalues/) 屬性）。

唯讀 [IErrorBarsFormat](../../ierrorbarsformat/)。

## 參見

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IErrorBarsFormat](../../ierrorbarsformat/)
* Class [ChartSeries](../)
* Namespace [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)