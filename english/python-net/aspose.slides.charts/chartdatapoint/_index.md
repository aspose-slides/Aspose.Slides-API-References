---
title: ChartDataPoint
second_title: Aspose.Sildes for Python via .NET API Reference
description: 
type: docs
weight: 140
url: /python-net/aspose.slides.charts/chartdatapoint/
---

## ChartDataPoint class

Represents series data point.

The ChartDataPoint type exposes the following members:
## Properties
| Name | Description |
| :- | :- |
|x_value|XValue.<br/>            Read-only [IStringOrDoubleChartValue](/slides/python-net/aspose.slides.charts/istringordoublechartvalue/).|
|y_value|YValue.<br/>            Read-only [IDoubleChartValue](/slides/python-net/aspose.slides.charts/idoublechartvalue/).|
|bubble_size|BubbleSize.<br/>            Read-only [IDoubleChartValue](/slides/python-net/aspose.slides.charts/idoublechartvalue/).|
|value|Value.<br/>            Read-only [IDoubleChartValue](/slides/python-net/aspose.slides.charts/idoublechartvalue/).|
|size_value|Returns the size value of chart data point.<br/>            Used with Treemap and Sunburst charts. <br/>            Read-only [IDoubleChartValue](/slides/python-net/aspose.slides.charts/idoublechartvalue/).|
|color_value|Returns the color value of chart data point.<br/>            Used with Map charts. <br/>            Read-only [IDoubleChartValue](/slides/python-net/aspose.slides.charts/idoublechartvalue/).|
|error_bars_custom_values|Represents series error bars values in case of Custom value type.<br/>            Read-only [IErrorBarsCustomValues](/slides/python-net/aspose.slides.charts/ierrorbarscustomvalues/).|
|label|Label.<br/>            Read-only [IDataLabel](/slides/python-net/aspose.slides.charts/idatalabel/).|
|is_bubble_3d|Specifies that the bubbles have a 3-D effect applied to them.<br/>            Read/write bool.|
|explosion|Specifies the amount the data point shall be moved from the center of the pie.<br/>            Read/write|
|format|Represents the formatting properties.<br/>            Read/write [IFormat](/slides/python-net/aspose.slides.charts/iformat/).|
|marker|Specifies a data marker.<br/>            Read-only [IMarker](/slides/python-net/aspose.slides.charts/imarker/).|
|set_as_total|Sets data point as total. Applied for Waterfall series type only.|
|related_legend_entry|Properties of corresponding legend entry in case of chart type from this list:<br/>            ChartType.BarOfPie,<br/>            ChartType.ExplodedPie,<br/>            ChartType.ExplodedPie3D,<br/>            ChartType.Pie,<br/>            ChartType.Pie3D,<br/>            ChartType.PieOfPie.<br/>            Read-only [ILegendEntryProperties](/slides/python-net/aspose.slides.charts/ilegendentryproperties/).|
|data_point_levels|Returns container of  data point levels. Applied for Treeamp and Sunburst series.<br/>            Data point levels indexing is zero-based.|
|invert_if_negative|Specifies the data point shall invert its colors if the value is negative.<br/>            Read/write bool.|
|actual_x|Specifies actual x location (left) of the chart element relative to the left top corner of the chart.<br/>            Call method IChart.ValidateChartLayout() before to get actual values. <br/>            Read|
|actual_y|Specifies actual top of the chart element relative to the left top corner of the chart.<br/>            Call method IChart.ValidateChartLayout() before to get actual values. <br/>            Read|
|actual_width|Specifies actual width of the chart element. Call method IChart.ValidateChartLayout() before to get actual values. <br/>            Read|
|actual_height|Specifies actual height of the chart element. Call method IChart.ValidateChartLayout() before to get actual values. <br/>            Read|
|as_i_actual_layout|Returns IActualLayout interface.|
## Methods
| Name | Description |
| :- | :- |
|remove()|Removes DataPoint from chart series.|
|get_automatic_data_point_color()|Returns an automatic color of data point based on series index, data point index, ParentSeriesGroup.IsColorVaried propery and chart style. <br/>            This color is used by default if FillType equals NotDefined.|

### See Also

* namespace [aspose.slides.charts](/slides/python-net/aspose.slides.charts/)
* assembly [Aspose.Slides](/slides/python-net/)

