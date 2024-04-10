---
title: ErrorBarsFormat class
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides.charts/
---


## ErrorBarsFormat class

Represents error bars of chart series. ErrorBars custom values are in IChartDataPointCollection
            (in :py:attr:`aspose.slides.charts.IChartDataPoint.error_bars_custom_values` property).

The ErrorBarsFormat type exposes the following members:

## Properties

| Property | Description |
| :- | :- |
| [type](/slides/python-net/aspose.slides.charts/type) | Gets or sets type of error bars. <br/>            Read/write :py:enum:`aspose.slides.charts.ErrorBarType`. |
| [value_type](/slides/python-net/aspose.slides.charts/value_type) | Represents possible ways to determine the length of the error bars. <br/>            In case of custom value type to specify value use :py:attr:`aspose.slides.charts.IChartDataPoint.error_bars_custom_values` property of specific data point in DataPoints collection of series.<br/>            In case of Fixed, Percentage or StandardDeviation value type use Value property to specify value.  <br/>            Read/write :py:enum:`aspose.slides.charts.ErrorBarValueType`. |
| [has_end_cap](/slides/python-net/aspose.slides.charts/has_end_cap) | Specifies an end cap is not drawn on the error bars.<br/>            Read/write :py:class:`bool`. |
| [value](/slides/python-net/aspose.slides.charts/value) | Gets or sets value which is used with Fixed, Percentage and StandardDeviation value types to determine the length of the error bars. <br/>            In any other case will return NaN.<br/>            Read/write :py:class:`float`. |
| [format](/slides/python-net/aspose.slides.charts/format) | Represents the format of the error bars.<br/>            Read/write :py:class:`aspose.slides.charts.IFormat`. |
| [chart](/slides/python-net/aspose.slides.charts/chart) | Returns the parent chart.<br/>            Read-only :py:class:`aspose.slides.charts.IChart`. |
| [is_visible](/slides/python-net/aspose.slides.charts/is_visible) | Gets or sets Error Bars visibility .<br/>            Read/write :py:class:`bool`. |
| [as_i_chart_component](/slides/python-net/aspose.slides.charts/as_i_chart_component) |  |
| [as_i_slide_component](/slides/python-net/aspose.slides.charts/as_i_slide_component) |  |
| [slide](/slides/python-net/aspose.slides.charts/slide) |  |
| [as_i_presentation_component](/slides/python-net/aspose.slides.charts/as_i_presentation_component) |  |
| [presentation](/slides/python-net/aspose.slides.charts/presentation) |  |

