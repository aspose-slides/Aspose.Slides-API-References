---
title: get_ErrorBarsXFormat()
second_title: Aspose.Slides for C++ API 参考
description: 表示系列在 X 方向的 ErrorBars。
type: docs
weight: 222
url: /zh/aspose.slides.charts/ichartseries/get_errorbarsxformat/
---
## IChartSeries::get_ErrorBarsXFormat() method

表示系列在 X 方向的 ErrorBars。

```cpp
virtual System::SharedPtr<IErrorBarsFormat> Aspose::Slides::Charts::IChartSeries::get_ErrorBarsXFormat()=0
```
## 备注

在 X 方向的 ErrorBars 适用于 area、bar、scatter 和 bubble 类型的系列。对于其他任何图表类型，此属性返回 null（包括 3D 图表）。如果使用自定义值，请使用 DataPoints 集合来指定值（带有 [IChartDataPoint::get_ErrorBarsCustomValues()](../../ichartdatapoint/get_errorbarscustomvalues/) 属性）。

只读 [IErrorBarsFormat](../../ierrorbarsformat/)。
## 另请参见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [IErrorBarsFormat](../../ierrorbarsformat/)
* 类 [IChartSeries](../)
* 命名空间 [Aspose::Slides::Charts](../../)
* 库 [Aspose.Slides](../../../)