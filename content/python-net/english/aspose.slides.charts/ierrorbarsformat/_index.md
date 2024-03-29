---
title: IErrorBarsFormat
second_title: Aspose.Sildes for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides.charts/ierrorbarsformat/
---

## IErrorBarsFormat class

Represents error bars of chart series. ErrorBars custom values are in IChartDataPointCollection<br/>            (in [error_bars_custom_values](/slides/python-net/aspose.slides.charts/ichartdatapoint/) property).

The IErrorBarsFormat type exposes the following members:
## Properties
| Name | Description |
| :- | :- |
|type|Gets or sets type of error bars. <br/>            Read/write [ErrorBarType](/slides/python-net/aspose.slides.charts/errorbartype/).|
|value_type|Represents possible ways to determine the length of the error bars. <br/>            In case of custom value type to specify value use [error_bars_custom_values](/slides/python-net/aspose.slides.charts/ichartdatapoint/) property of specific data point in DataPoints collection of series.  <br/>            Read/write [ErrorBarValueType](/slides/python-net/aspose.slides.charts/errorbarvaluetype/).|
|has_end_cap|Specifies an end cap is not drawn on the error bars.<br/>            Read/write bool.|
|value|Gets or sets value which is used with Fixed, Percentage and StandardDeviation value types to determine the length of the error bars. <br/>            Read/write|
|format|Represents the format of the error bars.<br/>            Read/write [IFormat](/slides/python-net/aspose.slides.charts/iformat/).|
|is_visible|Gets or sets Error Bars visibility.<br/>            Read/write bool.|
|as_i_chart_component|Returns IChartComponent interface.<br/>            Read-only [IChartComponent](/slides/python-net/aspose.slides.charts/ichartcomponent/).|
|chart|Returns the chart.<br/>            Read-only [IChart](/slides/python-net/aspose.slides.charts/ichart/).|
|as_i_slide_component|Allows to get base ISlideComponent interface.<br/>            Read-only [ISlideComponent](/slides/python-net/aspose.slides/islidecomponent/).|
|slide|Returns the base slide.<br/>            Read-only [IBaseSlide](/slides/python-net/aspose.slides/ibaseslide/).|
|as_i_presentation_component|Allows to get base IPresentationComponent interface.<br/>            Read-only [IPresentationComponent](/slides/python-net/aspose.slides/ipresentationcomponent/).|
|presentation|Returns the presentation. <br/>            Read-only [IPresentation](/slides/python-net/aspose.slides/ipresentation/).|

### See Also

* namespace [aspose.slides.charts](/slides/python-net/aspose.slides.charts/)
* assembly [Aspose.Slides](/slides/python-net/)

