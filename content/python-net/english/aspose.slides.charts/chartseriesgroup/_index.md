---
title: ChartSeriesGroup class
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides.charts/
---


## ChartSeriesGroup class

Represents group of series.

The ChartSeriesGroup type exposes the following members:

## Properties

| Property | Description |
| :- | :- |
| [type](/slides/python-net/aspose.slides.charts/type) | Returns a type of this series group.<br/>            Read-only :py:enum:`aspose.slides.charts.CombinableSeriesTypesGroup`. |
| [plot_on_second_axis](/slides/python-net/aspose.slides.charts/plot_on_second_axis) | Indicates if series of this group is plotted on secondary axis.<br/>            Read-only :py:class:`bool`. |
| [series](/slides/python-net/aspose.slides.charts/series) | Returns a collection of series.<br/>            Read-only :py:class:`aspose.slides.charts.IChartSeriesReadonlyCollection`. |
| [up_down_bars](/slides/python-net/aspose.slides.charts/up_down_bars) | Provede access to up/down bars of Line- or Stock-chart.<br/>            Read-only :py:class:`aspose.slides.charts.IUpDownBarsManager`. |
| [gap_width](/slides/python-net/aspose.slides.charts/gap_width) | Specifies the space between bar or column clusters, as a percentage of the bar or column width.<br/>            Read/write :py:class:`int`. |
| [gap_depth](/slides/python-net/aspose.slides.charts/gap_depth) | Returns or sets the distance, as a percentage of the marker width, between the data series in a 3D chart.<br/>            Read/write :py:class:`int`. |
| [first_slice_angle](/slides/python-net/aspose.slides.charts/first_slice_angle) | Gets or sets the angle of the first pie or doughnut chart slice, <br/>            in degrees (clockwise from up, from 0 to 360 degrees).<br/>            Read/write :py:class:`int`. |
| [doughnut_hole_size](/slides/python-net/aspose.slides.charts/doughnut_hole_size) | Specifies the size of the hole in a doughnut chart (can be between 0 and 90 percents <br/>            of the size of the plot area.).<br/>            Read/write :py:class:`int`. |
| [overlap](/slides/python-net/aspose.slides.charts/overlap) | Specifies how much bars and columns shall overlap on 2-D charts (from -100 to 100).<br/>            Read/write :py:class:`int`. |
| [second_pie_size](/slides/python-net/aspose.slides.charts/second_pie_size) | Specifies the size of the second pie or bar of a pie-of-pie chart or <br/>            a bar-of-pie chart, as a percentage of the size of the first pie (can <br/>            be between 5 and 200 percents).<br/>            Read/write :py:class:`int`. |
| [bubble_size_representation](/slides/python-net/aspose.slides.charts/bubble_size_representation) | Specifies how the bubble size values are represented on the bubble chart.<br/>            Read/write :py:enum:`aspose.slides.charts.BubbleSizeRepresentationType`. |
| [pie_split_position](/slides/python-net/aspose.slides.charts/pie_split_position) | Specifies a value that shall be used to determine which data points <br/>            are in the second pie or bar on a pie-of-pie or bar-of-pie chart. <br/>            Is used together with PieSplitBy property.<br/>            Read/write :py:class:`float`. |
| [pie_split_by](/slides/python-net/aspose.slides.charts/pie_split_by) | Specifies how to determine which data points are in the second pie or bar <br/>            on a pie-of-pie or bar-of-pie chart.<br/>            Read/write :py:enum:`aspose.slides.charts.PieSplitType`. |
| [is_color_varied](/slides/python-net/aspose.slides.charts/is_color_varied) | Specifies that each data marker in the series has a different color.<br/>            Read/write :py:class:`bool`. |
| [has_series_lines](/slides/python-net/aspose.slides.charts/has_series_lines) | True if chart has series lines. Applied to stacked bar and OfPie charts.<br/>            Read/write :py:class:`bool`. |
| [hi_low_lines_format](/slides/python-net/aspose.slides.charts/hi_low_lines_format) | Specifies HiLowLines format. <br/>            HiLowLines applied with HiLowClose, OpenHiLowClose, VolumeHiLowClose and VolumeOpenHiLowClose chart types. |
| [bubble_size_scale](/slides/python-net/aspose.slides.charts/bubble_size_scale) | Specifies the scale factor for the bubble chart (can be <br/>            between 0 and 300 percents of the default size).<br/>            Read/write :py:class:`int`. |
| [pie_split_custom_points](/slides/python-net/aspose.slides.charts/pie_split_custom_points) | The custom split information for a pie-of-pie or bar-of-pie chart with a custom split.<br/>            Contains data points that shall be drawn in the second pie or bar in a pie-of-pie or <br/>            bar-of-pie chart.<br/>            Read-only :py:class:`aspose.slides.charts.PieSplitCustomPointCollection`. |
| [chart](/slides/python-net/aspose.slides.charts/chart) | Returns the parent chart.<br/>            Read-only :py:class:`aspose.slides.charts.IChart`. |
| [as_i_chart_component](/slides/python-net/aspose.slides.charts/as_i_chart_component) |  |
| [as_i_slide_component](/slides/python-net/aspose.slides.charts/as_i_slide_component) |  |
| [slide](/slides/python-net/aspose.slides.charts/slide) |  |
| [as_i_presentation_component](/slides/python-net/aspose.slides.charts/as_i_presentation_component) |  |
| [presentation](/slides/python-net/aspose.slides.charts/presentation) |  |

## Indexer

| Name | Description |
| :- | :- |
| [index] |  |


### Remarks


            1) See summary and remarks for ChartSeriesGroupCollection class and CombinableSeriesTypesGroup enum.
            2) Group of series contains some series properies whitch is common for 
            each series in group ("series group properties").
            "Series group properties" in ChartSeriesGroup class is read/write.
            Each of "series group properties" can have a read-only projection in ChartSeries class.
            


