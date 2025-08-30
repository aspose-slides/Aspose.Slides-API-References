---
title: error_bars_x_format property
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides.charts/chartseries/error_bars_x_format/
weight: 80
---


## error_bars_x_format property
Represents ErrorBars of series with derection X. 

            ErrorBars with X direction are avalible for series of type area, bar, scatter and bubble. 
            For any other types of chart this property returns None (including 3D charts).
            In case of custom values use DataPoints collection to specify value
            (with [`IChartDataPoint.error_bars_custom_values`](/slides/python-net/aspose.slides.charts/ichartdatapoint/error_bars_custom_values) property).

            Read-only [`IErrorBarsFormat`](/slides/python-net/aspose.slides.charts/ierrorbarsformat).

### Definition:
```python
@property
def error_bars_x_format(self):
    ...
```


### See Also
* class [`ChartSeries`](/slides/python-net/aspose.slides.charts/chartseries)
* class [`IErrorBarsFormat`](/slides/python-net/aspose.slides.charts/ierrorbarsformat)
* module [`aspose.slides.charts`](/slides/python-net/aspose.slides.charts)
* library [`Aspose.Slides`](/slides/python-net)

