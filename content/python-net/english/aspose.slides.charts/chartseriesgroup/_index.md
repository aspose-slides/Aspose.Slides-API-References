---
title: ChartSeriesGroup
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides.charts/chartseriesgroup/
---


ChartSeriesGroup class

Represents group of series.

The ChartSeriesGroup type exposes the following members:

## Properties

| Property | Description |
| :- | :- |
| [type](/slides/python-net/aspose.slides.charts/chartseriesgroup/type/) | Returns a type of this series group.<br/>            Read-only [`CombinableSeriesTypesGroup`](/slides/python-net/aspose.slides.charts/combinableseriestypesgroup). |
| [plot_on_second_axis](/slides/python-net/aspose.slides.charts/chartseriesgroup/plot_on_second_axis/) | Indicates if series of this group is plotted on secondary axis.<br/>            Read-only .NET type System.Boolean. |
| [series](/slides/python-net/aspose.slides.charts/chartseriesgroup/series/) | Returns a collection of series.<br/>            Read-only [`IChartSeriesReadonlyCollection`](/slides/python-net/aspose.slides.charts/ichartseriesreadonlycollection). |
| [up_down_bars](/slides/python-net/aspose.slides.charts/chartseriesgroup/up_down_bars/) | Provede access to up/down bars of Line- or Stock-chart.<br/>            Read-only [`IUpDownBarsManager`](/slides/python-net/aspose.slides.charts/iupdownbarsmanager). |
| [gap_width](/slides/python-net/aspose.slides.charts/chartseriesgroup/gap_width/) | Specifies the space between bar or column clusters, as a percentage of the bar or column width.<br/>            Read/write .NET type System.UInt16. |
| [gap_depth](/slides/python-net/aspose.slides.charts/chartseriesgroup/gap_depth/) | Returns or sets the distance, as a percentage of the marker width, between the data series in a 3D chart.<br/>            Read/write .NET type System.UInt16. |
| [first_slice_angle](/slides/python-net/aspose.slides.charts/chartseriesgroup/first_slice_angle/) | Gets or sets the angle of the first pie or doughnut chart slice, <br/>            in degrees (clockwise from up, from 0 to 360 degrees).<br/>            Read/write .NET type System.UInt16. |
| [doughnut_hole_size](/slides/python-net/aspose.slides.charts/chartseriesgroup/doughnut_hole_size/) | Specifies the size of the hole in a doughnut chart (can be between 0 and 90 percents <br/>            of the size of the plot area.).<br/>            Read/write .NET type System.Byte. |
| [overlap](/slides/python-net/aspose.slides.charts/chartseriesgroup/overlap/) | Specifies how much bars and columns shall overlap on 2-D charts (from -100 to 100).<br/>            Read/write .NET type System.SByte. |
| [second_pie_size](/slides/python-net/aspose.slides.charts/chartseriesgroup/second_pie_size/) | Specifies the size of the second pie or bar of a pie-of-pie chart or <br/>            a bar-of-pie chart, as a percentage of the size of the first pie (can <br/>            be between 5 and 200 percents).<br/>            Read/write .NET type System.UInt16. |
| [bubble_size_representation](/slides/python-net/aspose.slides.charts/chartseriesgroup/bubble_size_representation/) | Specifies how the bubble size values are represented on the bubble chart.<br/>            Read/write [`BubbleSizeRepresentationType`](/slides/python-net/aspose.slides.charts/bubblesizerepresentationtype). |
| [pie_split_position](/slides/python-net/aspose.slides.charts/chartseriesgroup/pie_split_position/) | Specifies a value that shall be used to determine which data points <br/>            are in the second pie or bar on a pie-of-pie or bar-of-pie chart. <br/>            Is used together with PieSplitBy property.<br/>            Read/write .NET type System.Double. |
| [pie_split_by](/slides/python-net/aspose.slides.charts/chartseriesgroup/pie_split_by/) | Specifies how to determine which data points are in the second pie or bar <br/>            on a pie-of-pie or bar-of-pie chart.<br/>            Read/write [`PieSplitType`](/slides/python-net/aspose.slides.charts/piesplittype). |
| [is_color_varied](/slides/python-net/aspose.slides.charts/chartseriesgroup/is_color_varied/) | Specifies that each data marker in the series has a different color.<br/>            Read/write .NET type System.Boolean. |
| [has_series_lines](/slides/python-net/aspose.slides.charts/chartseriesgroup/has_series_lines/) | True if chart has series lines. Applied to stacked bar and OfPie charts.<br/>            Read/write .NET type System.Boolean. |
| [hi_low_lines_format](/slides/python-net/aspose.slides.charts/chartseriesgroup/hi_low_lines_format/) | Specifies HiLowLines format. <br/>            HiLowLines applied with HiLowClose, OpenHiLowClose, VolumeHiLowClose and VolumeOpenHiLowClose chart types. |
| [bubble_size_scale](/slides/python-net/aspose.slides.charts/chartseriesgroup/bubble_size_scale/) | Specifies the scale factor for the bubble chart (can be <br/>            between 0 and 300 percents of the default size).<br/>            Read/write .NET type System.Int32. |
| [pie_split_custom_points](/slides/python-net/aspose.slides.charts/chartseriesgroup/pie_split_custom_points/) | The custom split information for a pie-of-pie or bar-of-pie chart with a custom split.<br/>            Contains data points that shall be drawn in the second pie or bar in a pie-of-pie or <br/>            bar-of-pie chart.<br/>            Read-only [`PieSplitCustomPointCollection`](/slides/python-net/aspose.slides.charts/piesplitcustompointcollection). |
| [chart](/slides/python-net/aspose.slides.charts/chartseriesgroup/chart/) | Returns the parent chart.<br/>            Read-only [`IChart`](/slides/python-net/aspose.slides.charts/ichart). |
| [as_i_chart_component](/slides/python-net/aspose.slides.charts/chartseriesgroup/as_i_chart_component/) |  |
| [as_i_slide_component](/slides/python-net/aspose.slides.charts/chartseriesgroup/as_i_slide_component/) |  |
| [slide](/slides/python-net/aspose.slides.charts/chartseriesgroup/slide/) |  |
| [as_i_presentation_component](/slides/python-net/aspose.slides.charts/chartseriesgroup/as_i_presentation_component/) |  |
| [presentation](/slides/python-net/aspose.slides.charts/chartseriesgroup/presentation/) |  |

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

