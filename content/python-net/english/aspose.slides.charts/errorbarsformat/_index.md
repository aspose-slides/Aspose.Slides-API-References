---
title: ErrorBarsFormat class
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides.charts/errorbarsformat/
---


## ErrorBarsFormat class

Represents error bars of chart series. ErrorBars custom values are in IChartDataPointCollection
            (in [`IChartDataPoint.error_bars_custom_values`](/slides/python-net/aspose.slides.charts/ichartdatapoint#error_bars_custom_values) property).

The ErrorBarsFormat type exposes the following members:

## Properties

| Property | Description |
| :- | :- |
| [`type`](/slides/python-net/aspose.slides.charts/errorbarsformat/type/) | Gets or sets type of error bars. <br/>            Read/write [`ErrorBarType`](/slides/python-net/aspose.slides.charts/errorbartype). |
| [`value_type`](/slides/python-net/aspose.slides.charts/errorbarsformat/value_type/) | Represents possible ways to determine the length of the error bars. <br/>            In case of custom value type to specify value use [`IChartDataPoint.error_bars_custom_values`](/slides/python-net/aspose.slides.charts/ichartdatapoint#error_bars_custom_values) property of specific data point in DataPoints collection of series.<br/>            In case of Fixed, Percentage or StandardDeviation value type use Value property to specify value.  <br/>            Read/write [`ErrorBarValueType`](/slides/python-net/aspose.slides.charts/errorbarvaluetype). |
| [`has_end_cap`](/slides/python-net/aspose.slides.charts/errorbarsformat/has_end_cap/) | Specifies an end cap is not drawn on the error bars.<br/>            Read/write **bool**. |
| [`value`](/slides/python-net/aspose.slides.charts/errorbarsformat/value/) | Gets or sets value which is used with Fixed, Percentage and StandardDeviation value types to determine the length of the error bars. <br/>            In any other case will return NaN.<br/>            Read/write **float**. |
| [`format`](/slides/python-net/aspose.slides.charts/errorbarsformat/format/) | Represents the format of the error bars.<br/>            Read/write [`IFormat`](/slides/python-net/aspose.slides.charts/iformat). |
| [`chart`](/slides/python-net/aspose.slides.charts/errorbarsformat/chart/) | Returns the parent chart.<br/>            Read-only [`IChart`](/slides/python-net/aspose.slides.charts/ichart). |
| [`is_visible`](/slides/python-net/aspose.slides.charts/errorbarsformat/is_visible/) | Gets or sets Error Bars visibility .<br/>            Read/write **bool**. |
| [`as_i_chart_component`](/slides/python-net/aspose.slides.charts/errorbarsformat/as_i_chart_component/) |  |
| [`as_i_slide_component`](/slides/python-net/aspose.slides.charts/errorbarsformat/as_i_slide_component/) |  |
| [`slide`](/slides/python-net/aspose.slides.charts/errorbarsformat/slide/) |  |
| [`as_i_presentation_component`](/slides/python-net/aspose.slides.charts/errorbarsformat/as_i_presentation_component/) |  |
| [`presentation`](/slides/python-net/aspose.slides.charts/errorbarsformat/presentation/) |  |

### See Also
* module [`aspose.slides.charts`](/slides/python-net/aspose.slides.charts)
* library [`Aspose.Slides`](/slides/python-net)
