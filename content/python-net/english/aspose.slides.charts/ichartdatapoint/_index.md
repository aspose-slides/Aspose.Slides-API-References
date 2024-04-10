---
title: IChartDataPoint
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides.charts/ichartdatapoint/
---


IChartDataPoint class

Represents series data point.

The IChartDataPoint type exposes the following members:

## Properties

| Property | Description |
| :- | :- |
| [x_value](/slides/python-net/aspose.slides.charts/ichartdatapoint/x_value/) | Returns the x value of chart data point.<br/>            Read-only :py:class:`aspose.slides.charts.IStringOrDoubleChartValue`. |
| [y_value](/slides/python-net/aspose.slides.charts/ichartdatapoint/y_value/) | Returns the y value of chart data point.<br/>            Read-only :py:class:`aspose.slides.charts.IDoubleChartValue`. |
| [bubble_size](/slides/python-net/aspose.slides.charts/ichartdatapoint/bubble_size/) | Returns the bubble size of chart data point.<br/>            Read-only :py:class:`aspose.slides.charts.IDoubleChartValue`. |
| [value](/slides/python-net/aspose.slides.charts/ichartdatapoint/value/) | Returns the value of chart data point.<br/>            Read-only :py:class:`aspose.slides.charts.IDoubleChartValue`. |
| [size_value](/slides/python-net/aspose.slides.charts/ichartdatapoint/size_value/) | Returns the size value of chart data point.<br/>            Used with Treemap and Sunburst charts. <br/>            Read-only :py:class:`aspose.slides.charts.IDoubleChartValue`. |
| [color_value](/slides/python-net/aspose.slides.charts/ichartdatapoint/color_value/) | Returns the color value of chart data point.<br/>            Used with Map charts. <br/>            Read-only :py:class:`aspose.slides.charts.IDoubleChartValue`. |
| [error_bars_custom_values](/slides/python-net/aspose.slides.charts/ichartdatapoint/error_bars_custom_values/) | Represents series error bars values in case of Custom value type.<br/>            Read-only :py:class:`aspose.slides.charts.IErrorBarsCustomValues`. |
| [label](/slides/python-net/aspose.slides.charts/ichartdatapoint/label/) | Represents the lable of chart data point.<br/>            Read-only :py:class:`aspose.slides.charts.IDataLabel`. |
| [is_bubble_3d](/slides/python-net/aspose.slides.charts/ichartdatapoint/is_bubble_3d/) | Specifies that the bubbles have a 3-D effect applied to them.<br/>            Read/write :py:class:`bool`. |
| [explosion](/slides/python-net/aspose.slides.charts/ichartdatapoint/explosion/) | Specifies the amount the data point shall be moved from the center of the pie.<br/>            Read/write :py:class:`int`. |
| [format](/slides/python-net/aspose.slides.charts/ichartdatapoint/format/) | Represents the formatting properties.<br/>            Read/write :py:class:`aspose.slides.charts.IFormat`. |
| [marker](/slides/python-net/aspose.slides.charts/ichartdatapoint/marker/) | Specifies a data marker.<br/>            Read-only :py:class:`aspose.slides.charts.IMarker`. |
| [related_legend_entry](/slides/python-net/aspose.slides.charts/ichartdatapoint/related_legend_entry/) | Properties of corresponding legend entry in case of chart type from this list:<br/>            ChartType.BarOfPie,<br/>            ChartType.ExplodedPie,<br/>            ChartType.ExplodedPie3D,<br/>            ChartType.Pie,<br/>            ChartType.Pie3D,<br/>            ChartType.PieOfPie.<br/>            Read-only :py:class:`aspose.slides.charts.ILegendEntryProperties`. |
| [set_as_total](/slides/python-net/aspose.slides.charts/ichartdatapoint/set_as_total/) | Sets data point as total. Applied for Waterfall series type only. |
| [invert_if_negative](/slides/python-net/aspose.slides.charts/ichartdatapoint/invert_if_negative/) | Specifies the data point shall invert its colors if the value is negative.<br/>            Read/write :py:class:`bool`. |
| [data_point_levels](/slides/python-net/aspose.slides.charts/ichartdatapoint/data_point_levels/) | Returns container of  data point levels. Applied for Treeamp and Sunburst series.<br/>            Data point levels indexing is zero-based. |
| [index](/slides/python-net/aspose.slides.charts/ichartdatapoint/index/) | Determines which of the parent's children collection this data point applies to.<br/>            Read :py:class:`int`. |
| [as_i_actual_layout](/slides/python-net/aspose.slides.charts/ichartdatapoint/as_i_actual_layout/) | Returns IActualLayout interface. |
| [actual_x](/slides/python-net/aspose.slides.charts/ichartdatapoint/actual_x/) |  |
| [actual_y](/slides/python-net/aspose.slides.charts/ichartdatapoint/actual_y/) |  |
| [actual_width](/slides/python-net/aspose.slides.charts/ichartdatapoint/actual_width/) |  |
| [actual_height](/slides/python-net/aspose.slides.charts/ichartdatapoint/actual_height/) |  |

## Methods

| Method | Description |
| :- | :- |
| [remove](/slides/python-net/aspose.slides.charts/ichartdatapoint/ichartdatapoint/#/) | Removes DataPoint from chart series. |
| [get_automatic_data_point_color](/slides/python-net/aspose.slides.charts/ichartdatapoint/ichartdatapoint/#/) | Returns an automatic color of data point based on series index, data point index, ParentSeriesGroup.IsColorVaried propery and chart style. <br/>            This color is used by default if FillType equals NotDefined. |

