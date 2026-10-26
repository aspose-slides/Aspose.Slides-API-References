---
title: get_ErrorBarsYFormat()
second_title: Aspose.Slides for C++ API 參考
description: 表示 Y 方向的系列 ErrorBars。
type: docs
weight: 235
url: /zh-hant/aspose.slides.charts/ichartseries/get_errorbarsyformat/
---
## IChartSeries::get_ErrorBarsYFormat() 方法

表示 Y 方向的系列 ErrorBars。

```cpp
virtual System::SharedPtr<IErrorBarsFormat> Aspose::Slides::Charts::IChartSeries::get_ErrorBarsYFormat()=0
```

## 備註

ErrorBars 具有 Y 方向時，適用於 area、bar、line、scatter 和 bubble 類型的系列。對於其他類型的圖表，此屬性會返回 null（包括 3D 圖表）。若使用自訂值，請使用 DataPoints 集合來指定值（使用 [IChartDataPoint::get_ErrorBarsCustomValues()](../../ichartdatapoint/get_errorbarscustomvalues/) 屬性）。

唯讀 [IErrorBarsFormat](../../ierrorbarsformat/).

## 另見

* 類型定義 [SharedPtr](../../../system/sharedptr/)
* 類別 [IErrorBarsFormat](../../ierrorbarsformat/)
* 類別 [IChartSeries](../)
* 命名空間 [Aspose::Slides::Charts](../../)
* 程式庫 [Aspose.Slides](../../../)