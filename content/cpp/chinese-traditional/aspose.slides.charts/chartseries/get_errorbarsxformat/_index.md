---
title: get_ErrorBarsXFormat()
second_title: Aspose.Slides for C++ API 參考
description: 表示 X 方向的系列 ErrorBars。
type: docs
weight: 222
url: /zh-hant/aspose.slides.charts/chartseries/get_errorbarsxformat/
---
## ChartSeries::get_ErrorBarsXFormat() 方法

表示 X 方向的系列 ErrorBars。

```cpp
System::SharedPtr<IErrorBarsFormat> Aspose::Slides::Charts::ChartSeries::get_ErrorBarsXFormat() override
```

## 備註

X 方向的 ErrorBars 適用於 area、bar、scatter 和 bubble 類型的系列。對於其他任何圖表類型，此屬性會返回 null（包括 3D 圖表）。若使用自訂值，請使用 DataPoints 集合指定值（使用 [IChartDataPoint::get_ErrorBarsCustomValues()](../../ichartdatapoint/get_errorbarscustomvalues/) 屬性）。

唯讀 [IErrorBarsFormat](../../ierrorbarsformat/)。

## 另見

* 類型定義 [SharedPtr](../../../system/sharedptr/)
* 類別 [IErrorBarsFormat](../../ierrorbarsformat/)
* 類別 [ChartSeries](../)
* 命名空間 [Aspose::Slides::Charts](../../)
* 函式庫 [Aspose.Slides](../../../)