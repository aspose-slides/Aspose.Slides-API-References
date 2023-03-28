---
title: get_ErrorBarsYFormat()
second_title: Aspose.Slides for C++ API Reference
description: Represents ErrorBars of series with derection Y.
type: docs
weight: 235
url: /cpp/aspose.slides.charts/ichartseries/get_errorbarsyformat/
---
## IChartSeries::get_ErrorBarsYFormat() method


Represents ErrorBars of series with derection Y.

```cpp
virtual System::SharedPtr<IErrorBarsFormat> Aspose::Slides::Charts::IChartSeries::get_ErrorBarsYFormat()=0
```

## Remarks


ErrorBars with Y direction are avalible for series of type area, bar, line, scatter and bubble. For any other types of chart this property returns null (including 3D charts). In case of custom values use DataPoints collection to specify value (with [IChartDataPoint::get_ErrorBarsCustomValues()](../../ichartdatapoint/get_errorbarscustomvalues/) property). 

Read-only [IErrorBarsFormat](../../ierrorbarsformat/). 
## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IErrorBarsFormat](../../ierrorbarsformat/)
* Class [IChartSeries](../)
* Namespace [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)
