---
title: ChartSeriesGroup
second_title: Aspose.Sildes for Python via .NET API Reference
description: 
type: docs
weight: 260
url: /python-net/aspose.slides.charts/chartseriesgroup/
---

## ChartSeriesGroup class

Represents group of series.

The ChartSeriesGroup type exposes the following members:
## Properties
| Name | Description |
| :- | :- |
|type|Returns a type of this series group.<br/>            Read-only [CombinableSeriesTypesGroup](/slides/python-net/aspose.slides.charts/combinableseriestypesgroup/).|
|plot_on_second_axis|Indicates if series of this group is plotted on secondary axis.<br/>            Read-only bool.|
|series|Returns a collection of series.<br/>            Read-only [IChartSeriesReadonlyCollection](/slides/python-net/aspose.slides.charts/ichartseriesreadonlycollection/).|
|up_down_bars|Provede access to up/down bars of Line- or Stock-chart.<br/>            Read-only [IUpDownBarsManager](/slides/python-net/aspose.slides.charts/iupdownbarsmanager/).|
|gap_width|Specifies the space between bar or column clusters, as a percentage of the bar or column width.<br/>            Read/write int.|
|gap_depth|Returns or sets the distance, as a percentage of the marker width, between the data series in a 3D chart.<br/>            Read/write int.|
|first_slice_angle|Gets or sets the angle of the first pie or doughnut chart slice, <br/>            in degrees (clockwise from up, from 0 to 360 degrees).<br/>            Read/write int.|
|doughnut_hole_size|Specifies the size of the hole in a doughnut chart (can be between 0 and 90 percents <br/>            of the size of the plot area.).<br/>            Read/write int.|
|overlap|Specifies how much bars and columns shall overlap on 2-D charts (from -100 to 100).<br/>            Read/write int.|
|second_pie_size|Specifies the size of the second pie or bar of a pie-of-pie chart or <br/>            a bar-of-pie chart, as a percentage of the size of the first pie (can <br/>            be between 5 and 200 percents).<br/>            Read/write int.|
|bubble_size_representation|Specifies how the bubble size values are represented on the bubble chart.<br/>            Read/write [BubbleSizeRepresentationType](/slides/python-net/aspose.slides.charts/bubblesizerepresentationtype/).|
|pie_split_position|Specifies a value that shall be used to determine which data points <br/>            are in the second pie or bar on a pie-of-pie or bar-of-pie chart. <br/>            Is used together with PieSplitBy property.<br/>            Read/write float.|
|pie_split_by|Specifies how to determine which data points are in the second pie or bar <br/>            on a pie-of-pie or bar-of-pie chart.<br/>            Read/write [PieSplitType](/slides/python-net/aspose.slides.charts/piesplittype/).|
|is_color_varied|Specifies that each data marker in the series has a different color.<br/>            Read/write bool.|
|has_series_lines|True if chart has series lines. Applied to stacked bar and OfPie charts.<br/>            Read/write bool.|
|hi_low_lines_format|Specifies HiLowLines format. <br/>            HiLowLines applied with HiLowClose, OpenHiLowClose, VolumeHiLowClose and VolumeOpenHiLowClose chart types.|
|bubble_size_scale|Specifies the scale factor for the bubble chart (can be <br/>            between 0 and 300 percents of the default size).<br/>            Read/write|
|pie_split_custom_points|The custom split information for a pie-of-pie or bar-of-pie chart with a custom split.<br/>            Contains data points that shall be drawn in the second pie or bar in a pie-of-pie or <br/>            bar-of-pie chart.<br/>            Read-only [PieSplitCustomPointCollection](/slides/python-net/aspose.slides.charts/piesplitcustompointcollection/).|
|chart|Returns the parent chart.<br/>            Read-only [IChart](/slides/python-net/aspose.slides.charts/ichart/).|
|as_i_chart_component|Allows to get base IChartComponent interface.<br/>            Read-only [IChartComponent](/slides/python-net/aspose.slides.charts/ichartcomponent/).|
|as_i_slide_component|Allows to get base ISlideComponent interface.<br/>            Read-only [ISlideComponent](/slides/python-net/aspose.slides/islidecomponent/).|
|slide|Returns the base slide.<br/>            Read-only [IBaseSlide](/slides/python-net/aspose.slides/ibaseslide/).|
|as_i_presentation_component|Allows to get base IPresentationComponent interface.<br/>            Read-only [IPresentationComponent](/slides/python-net/aspose.slides/ipresentationcomponent/).|
|presentation|Returns the presentation. <br/>            Read-only [IPresentation](/slides/python-net/aspose.slides/ipresentation/).|
## Indexer
| Name | Description |
| :- | :- |
|[index]|Gets the element at the specified index.|

### See Also

* namespace [aspose.slides.charts](/slides/python-net/aspose.slides.charts/)
* assembly [Aspose.Slides](/slides/python-net/)

