---
title: get_ErrorBarsYFormat()
second_title: Aspose.Slides for C++ API 参考
description: 表示具有 Y 方向的系列的 ErrorBars。
type: docs
weight: 235
url: /zh/aspose.slides.charts/chartseries/get_errorbarsyformat/
---
## ChartSeries::get_ErrorBarsYFormat() 方法

表示具有 Y 方向的系列的 ErrorBars。

```cpp
System::SharedPtr<IErrorBarsFormat> Aspose::Slides::Charts::ChartSeries::get_ErrorBarsYFormat() override
```

## 备注

具有 Y 方向的 ErrorBars 适用于 area、bar、line、scatter 和 bubble 类型的系列。对于其他任何图表类型，此属性返回 null（包括 3D 图表）。如果使用自定义值，请使用 DataPoints 集合来指定值（使用 [IChartDataPoint::get_ErrorBarsCustomValues()](../../ichartdatapoint/get_errorbarscustomvalues/) 属性）。

只读 [IErrorBarsFormat](../../ierrorbarsformat/)。

## 另请参见

* Typedef [SharedPtr](../../../system/sharedptr/)
* 类 [IErrorBarsFormat](../../ierrorbarsformat/)
* 类 [ChartSeries](../)
* 命名空间 [Aspose::Slides::Charts](../../)
* 库 [Aspose.Slides](../../../)