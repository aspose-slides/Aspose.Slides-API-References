---
title: get_ErrorBarsXFormat()
second_title: Aspose.Slides C++ API 參考
description: 表示 X 方向系列的 ErrorBars。
type: docs
weight: 222
url: /zh-hant/aspose.slides.charts/ichartseries/get_errorbarsxformat/
---
## IChartSeries::get_ErrorBarsXFormat() 方法

表示 X 方向的系列 ErrorBars。

```cpp
virtual System::SharedPtr<IErrorBarsFormat> Aspose::Slides::Charts::IChartSeries::get_ErrorBarsXFormat()=0
```

## 備註

ErrorBars 具有 X 方向僅適用於 area、bar、scatter 和 bubble 類型的系列。對於其他任何圖表類型，此屬性將返回 null（包括 3D 圖表）。若使用自訂值，請使用 DataPoints 集合指定值（使用 [IChartDataPoint::get_ErrorBarsCustomValues()](../../ichartdatapoint/get_errorbarscustomvalues/) 屬性）。

唯讀 [IErrorBarsFormat](../../ierrorbarsformat/)。

## 參見

* 型別定義 [SharedPtr](../../../system/sharedptr/)
* 類別 [IErrorBarsFormat](../../ierrorbarsformat/)
* 類別 [IChartSeries](../)
* 命名空間 [Aspose::Slides::Charts](../../)
* 函式庫 [Aspose.Slides](../../../)