---
title: get_ErrorBarsXFormat()
second_title: Aspose.Slides for C++ API 参考
description: 表示方向为 X 的系列的 ErrorBars。
type: docs
weight: 222
url: /zh/aspose.slides.charts/chartseries/get_errorbarsxformat/
---
## ChartSeries::get_ErrorBarsXFormat() 方法

表示方向为 X 的系列的 ErrorBars。

```cpp
System::SharedPtr<IErrorBarsFormat> Aspose::Slides::Charts::ChartSeries::get_ErrorBarsXFormat() override
```

## 备注

ErrorBars 在 X 方向上可用于类型为 area、bar、scatter 和 bubble 的系列。对于其他任何图表类型，此属性返回 null（包括 3D 图表）。若使用自定义值，请使用 DataPoints 集合来指定值（使用 [IChartDataPoint::get_ErrorBarsCustomValues()](../../ichartdatapoint/get_errorbarscustomvalues/) 属性）。

只读 [IErrorBarsFormat](../../ierrorbarsformat/). 
## 另见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [IErrorBarsFormat](../../ierrorbarsformat/)
* 类 [ChartSeries](../)
* 命名空间 [Aspose::Slides::Charts](../../)
* 库 [Aspose.Slides](../../../)