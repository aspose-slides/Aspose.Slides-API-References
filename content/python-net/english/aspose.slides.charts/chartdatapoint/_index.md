---
title: ChartDataPoint
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides.charts/chartdatapoint/
---


ChartDataPoint class

Represents series data point.

The ChartDataPoint type exposes the following members:

## Properties

| Property | Description |
| :- | :- |
| [x_value](/slides/python-net/aspose.slides.charts/chartdatapoint/x_value/) | XValue.<br/>            Read-only <br/>[`IStringOrDoubleChartValue`](/slides/python-net/aspose.slides.charts/istringordoublechartvalue). |
| [y_value](/slides/python-net/aspose.slides.charts/chartdatapoint/y_value/) | YValue.<br/>            Read-only <br/>[`IDoubleChartValue`](/slides/python-net/aspose.slides.charts/idoublechartvalue). |
| [bubble_size](/slides/python-net/aspose.slides.charts/chartdatapoint/bubble_size/) | BubbleSize.<br/>            Read-only <br/>[`IDoubleChartValue`](/slides/python-net/aspose.slides.charts/idoublechartvalue). |
| [value](/slides/python-net/aspose.slides.charts/chartdatapoint/value/) | Value.<br/>            Read-only <br/>[`IDoubleChartValue`](/slides/python-net/aspose.slides.charts/idoublechartvalue). |
| [size_value](/slides/python-net/aspose.slides.charts/chartdatapoint/size_value/) | Returns the size value of chart data point.<br/>            Used with Treemap and Sunburst charts. <br/>            Read-only <br/>[`IDoubleChartValue`](/slides/python-net/aspose.slides.charts/idoublechartvalue). |
| [color_value](/slides/python-net/aspose.slides.charts/chartdatapoint/color_value/) | Returns the color value of chart data point.<br/>            Used with Map charts. <br/>            Read-only <br/>[`IDoubleChartValue`](/slides/python-net/aspose.slides.charts/idoublechartvalue). |
| [error_bars_custom_values](/slides/python-net/aspose.slides.charts/chartdatapoint/error_bars_custom_values/) | Represents series error bars values in case of Custom value type.<br/>            Read-only <br/>[`IErrorBarsCustomValues`](/slides/python-net/aspose.slides.charts/ierrorbarscustomvalues). |
| [label](/slides/python-net/aspose.slides.charts/chartdatapoint/label/) | Label.<br/>            Read-only <br/>[`IDataLabel`](/slides/python-net/aspose.slides.charts/idatalabel). |
| [is_bubble_3d](/slides/python-net/aspose.slides.charts/chartdatapoint/is_bubble_3d/) | Specifies that the bubbles have a 3-D effect applied to them.<br/>            Read/write <br/>.NET type System.Boolean. |
| [explosion](/slides/python-net/aspose.slides.charts/chartdatapoint/explosion/) | Specifies the amount the data point shall be moved from the center of the pie.<br/>            Read/write <br/>.NET type System.Int32. |
| [format](/slides/python-net/aspose.slides.charts/chartdatapoint/format/) | Represents the formatting properties.<br/>            Read/write <br/>[`IFormat`](/slides/python-net/aspose.slides.charts/iformat). |
| [marker](/slides/python-net/aspose.slides.charts/chartdatapoint/marker/) | Specifies a data marker.<br/>            Read-only <br/>[`IMarker`](/slides/python-net/aspose.slides.charts/imarker). |
| [set_as_total](/slides/python-net/aspose.slides.charts/chartdatapoint/set_as_total/) | Sets data point as total. Applied for Waterfall series type only. |
| [related_legend_entry](/slides/python-net/aspose.slides.charts/chartdatapoint/related_legend_entry/) | Properties of corresponding legend entry in case of chart type from this list:<br/>            ChartType.BarOfPie,<br/>            ChartType.ExplodedPie,<br/>            ChartType.ExplodedPie3D,<br/>            ChartType.Pie,<br/>            ChartType.Pie3D,<br/>            ChartType.PieOfPie.<br/>            Read-only <br/>[`ILegendEntryProperties`](/slides/python-net/aspose.slides.charts/ilegendentryproperties). |
| [data_point_levels](/slides/python-net/aspose.slides.charts/chartdatapoint/data_point_levels/) | Returns container of  data point levels. Applied for Treeamp and Sunburst series.<br/>            Data point levels indexing is zero-based. |
| [index](/slides/python-net/aspose.slides.charts/chartdatapoint/index/) |  |
| [invert_if_negative](/slides/python-net/aspose.slides.charts/chartdatapoint/invert_if_negative/) | Specifies the data point shall invert its colors if the value is negative.<br/>            Read/write <br/>.NET type System.Boolean. |
| [actual_x](/slides/python-net/aspose.slides.charts/chartdatapoint/actual_x/) | Specifies actual x location (left) of the chart element relative to the left top corner of the chart.<br/>            Call method IChart.ValidateChartLayout() before to get actual values. <br/>            Read <br/>.NET type System.Single. |
| [actual_y](/slides/python-net/aspose.slides.charts/chartdatapoint/actual_y/) | Specifies actual top of the chart element relative to the left top corner of the chart.<br/>            Call method IChart.ValidateChartLayout() before to get actual values. <br/>            Read <br/>.NET type System.Single. |
| [actual_width](/slides/python-net/aspose.slides.charts/chartdatapoint/actual_width/) | Specifies actual width of the chart element. Call method IChart.ValidateChartLayout() before to get actual values. <br/>            Read <br/>.NET type System.Single. |
| [actual_height](/slides/python-net/aspose.slides.charts/chartdatapoint/actual_height/) | Specifies actual height of the chart element. Call method IChart.ValidateChartLayout() before to get actual values. <br/>            Read <br/>.NET type System.Single. |
| [as_i_actual_layout](/slides/python-net/aspose.slides.charts/chartdatapoint/as_i_actual_layout/) |  |

## Methods

| Method | Description |
| :- | :- |
| [remove](/slides/python-net/aspose.slides.charts/chartdatapoint/chartdatapoint/#/) | Removes DataPoint from chart series. |
| [get_automatic_data_point_color](/slides/python-net/aspose.slides.charts/chartdatapoint/chartdatapoint/#/) | Returns an automatic color of data point based on series index, data point index, ParentSeriesGroup.IsColorVaried property and chart style.<br/>            This color is used by default if FillType equals NotDefined. |

