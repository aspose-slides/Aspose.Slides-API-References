---
title: get_ErrorBarsXFormat()
second_title: Aspose.Slides for C++ API Reference
description: Represents ErrorBars of series with derection X.
type: docs
weight: 222
url: /aspose.slides.charts/chartseries/get_errorbarsxformat/
---
## ChartSeries::get_ErrorBarsXFormat() method


Represents ErrorBars of series with derection X.

```cpp
System::SharedPtr<IErrorBarsFormat> Aspose::Slides::Charts::ChartSeries::get_ErrorBarsXFormat() override
```

## Remarks


ErrorBars with X direction are avalible for series of type area, bar, scatter and bubble. For any other types of chart this property returns null (including 3D charts). In case of custom values use DataPoints collection to specify value (with [IChartDataPoint::get_ErrorBarsCustomValues()](../../ichartdatapoint/get_errorbarscustomvalues/) property). 

Read-only [IErrorBarsFormat](../../ierrorbarsformat/). 
## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IErrorBarsFormat](../../ierrorbarsformat/)
* Class [ChartSeries](../)
* Namespace [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)