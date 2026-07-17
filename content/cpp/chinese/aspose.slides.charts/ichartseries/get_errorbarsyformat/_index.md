---
title: get_ErrorBarsYFormat()
second_title: Aspose.Slides for C++ API 参考
description: 表示具有 Y 方向的系列 ErrorBars。
type: docs
weight: 235
url: /zh/aspose.slides.charts/ichartseries/get_errorbarsyformat/
---
## IChartSeries::get_ErrorBarsYFormat() 方法


表示具有 Y 方向的系列 ErrorBars。

```cpp
virtual System::SharedPtr<IErrorBarsFormat> Aspose::Slides::Charts::IChartSeries::get_ErrorBarsYFormat()=0
```

## 备注


Y 方向的 ErrorBars 可用于 area、bar、line、scatter 和 bubble 类型的系列。对于其他类型的图表（包括 3D 图表），此属性返回 null。若使用自定义值，请使用 DataPoints 集合来指定值（使用 [IChartDataPoint::get_ErrorBarsCustomValues()](../../ichartdatapoint/get_errorbarscustomvalues/) 属性）。

只读 [IErrorBarsFormat](../../ierrorbarsformat/)。 
## 另见

* Typedef [SharedPtr](../../../system/sharedptr/)
* 类 [IErrorBarsFormat](../../ierrorbarsformat/)
* 类 [IChartSeries](../)
* 命名空间 [Aspose::Slides::Charts](../../)
* 库 [Aspose.Slides](../../../)