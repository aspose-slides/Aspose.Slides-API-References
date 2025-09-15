---
title: IChartSeriesGroup class
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides.charts/ichartseriesgroup/
---


## IChartSeriesGroup class

Represents group of series.

The IChartSeriesGroup type exposes the following members:

## Properties

| Property | Description |
| :- | :- |
| [`type`](/slides/python-net/aspose.slides.charts/ichartseriesgroup/type/) | Returns a type of this series group.<br/>            Read-only [`CombinableSeriesTypesGroup`](/slides/python-net/aspose.slides.charts/combinableseriestypesgroup). |
| [`plot_on_second_axis`](/slides/python-net/aspose.slides.charts/ichartseriesgroup/plot_on_second_axis/) | Indicates if series of this group is plotted on secondary axis.<br/>            Read-only **bool**. |
| [`series`](/slides/python-net/aspose.slides.charts/ichartseriesgroup/series/) | Returns a readonly collection of chart series.<br/>            Read-only [`IChartSeriesReadonlyCollection`](/slides/python-net/aspose.slides.charts/ichartseriesreadonlycollection). |
| [`up_down_bars`](/slides/python-net/aspose.slides.charts/ichartseriesgroup/up_down_bars/) | Provede access to up/down bars of Line- or Stock-chart.<br/>            Read-only [`IUpDownBarsManager`](/slides/python-net/aspose.slides.charts/iupdownbarsmanager). |
| [`gap_width`](/slides/python-net/aspose.slides.charts/ichartseriesgroup/gap_width/) | Specifies the space between bar or column clusters, as a percentage of the bar or column width.<br/>            Read/write **int**. |
| [`gap_depth`](/slides/python-net/aspose.slides.charts/ichartseriesgroup/gap_depth/) | Returns or sets the distance, as a percentage of the marker width, between the data series in a 3D chart.<br/>            Read/write **int**. |
| [`first_slice_angle`](/slides/python-net/aspose.slides.charts/ichartseriesgroup/first_slice_angle/) | Gets or sets the angle of the first pie or doughnut chart slice, <br/>            in degrees (clockwise from up, from 0 to 360 degrees).<br/>            Read/write **int**. |
| [`is_color_varied`](/slides/python-net/aspose.slides.charts/ichartseriesgroup/is_color_varied/) | Specifies that each data marker in the series has a different color.<br/>            Read/write **bool**. |
| [`has_series_lines`](/slides/python-net/aspose.slides.charts/ichartseriesgroup/has_series_lines/) | True if chart has series lines. Applied to stacked bar and OfPie charts.<br/>            Read/write **bool**. |
| [`overlap`](/slides/python-net/aspose.slides.charts/ichartseriesgroup/overlap/) | Specifies how much bars and columns shall overlap on 2-D charts, as a percentage (from -100% to 100%).<br/>             - -100%: Maximum spacing (bars are completely separated).<br/>             - 0%: Bars are placed side by side without overlap or spacing.<br/>             - 100%: Maximum overlap (bars completely overlap each other).<br/>             This property is read/write **int**. |
| [`second_pie_size`](/slides/python-net/aspose.slides.charts/ichartseriesgroup/second_pie_size/) | Specifies the size of the second pie or bar of a pie-of-pie chart or <br/>            a bar-of-pie chart, as a percentage of the size of the first pie (can <br/>            be between 5 and 200 percents).<br/>            Read/write **int**. |
| [`pie_split_position`](/slides/python-net/aspose.slides.charts/ichartseriesgroup/pie_split_position/) | Specifies a value that shall be used to determine which data points <br/>            are in the second pie or bar on a pie-of-pie or bar-of-pie chart. <br/>            Is used together with PieSplitBy property.<br/>            Read/write **float**. |
| [`pie_split_by`](/slides/python-net/aspose.slides.charts/ichartseriesgroup/pie_split_by/) | Specifies how to determine which data points are in the second pie or bar <br/>            on a pie-of-pie or bar-of-pie chart.<br/>            Read/write [`PieSplitType`](/slides/python-net/aspose.slides.charts/piesplittype). |
| [`pie_split_custom_points`](/slides/python-net/aspose.slides.charts/ichartseriesgroup/pie_split_custom_points/) | The custom split information for a pie-of-pie or bar-of-pie chart with a custom split.<br/>            Contains data points that shall be drawn in the second pie or bar in a pie-of-pie or <br/>            bar-of-pie chart.<br/>            Read-only [`IPieSplitCustomPointCollection`](/slides/python-net/aspose.slides.charts/ipiesplitcustompointcollection). |
| [`doughnut_hole_size`](/slides/python-net/aspose.slides.charts/ichartseriesgroup/doughnut_hole_size/) | Specifies the size of the hole in a doughnut chart (can be between 10 and 90 percents <br/>            of the size of the plot area.).<br/>            Read/write **int**. |
| [`bubble_size_scale`](/slides/python-net/aspose.slides.charts/ichartseriesgroup/bubble_size_scale/) | Specifies the scale factor for the bubble chart (can be <br/>            between 0 and 300 percents of the default size).<br/>            Read/write **int**. |
| [`hi_low_lines_format`](/slides/python-net/aspose.slides.charts/ichartseriesgroup/hi_low_lines_format/) | Specifies HiLowLines format. <br/>            HiLowLines applied with HiLowClose, OpenHiLowClose, VolumeHiLowClose and VolumeOpenHiLowClose chart types. |
| [`bubble_size_representation`](/slides/python-net/aspose.slides.charts/ichartseriesgroup/bubble_size_representation/) | Specifies how the bubble size values are represented on the bubble chart.<br/>            Read/write [`BubbleSizeRepresentationType`](/slides/python-net/aspose.slides.charts/bubblesizerepresentationtype). |
| [`chart`](/slides/python-net/aspose.slides.charts/ichartseriesgroup/chart/) |  |
| [`slide`](/slides/python-net/aspose.slides.charts/ichartseriesgroup/slide/) |  |
| [`presentation`](/slides/python-net/aspose.slides.charts/ichartseriesgroup/presentation/) |  |

Gets the element at the specified index.

## Indexer

| Name | Description |
| :- | :- |
| [`[index]`](/slides/python-net/aspose.slides.charts/ichartseriesgroup/__getitem__/) |  |


### Remarks

1) See summary and remarks for ChartSeriesGroupCollection class and CombinableSeriesTypesGroup enum.
            2) Group of series contains some series properies whitch is common for 
            each series in group ("series group properties").
            "Series group properties" in ChartSeriesGroup class is read/write.
            Each of "series group properties" can have a read-only projection in ChartSeries class.


### See Also
* module [`aspose.slides.charts`](/slides/python-net/aspose.slides.charts)
* library [`Aspose.Slides`](/slides/python-net)

