---
title: ChartSeriesGroup class
second_title: Referencia de API de Aspose.Slides para Python vía .NET
description: 
type: docs
url: /es/aspose.slides.charts/chartseriesgroup/
---
## ChartSeriesGroup clase

Representa un grupo de series.

El tipo ChartSeriesGroup expone los siguientes miembros:

## Propiedades

| Propiedad | Descripción |
| :- | :- |
| [`type`](/slides/python-net/es/aspose.slides.charts/chartseriesgroup/type/) | Returns a type of this series group.<br/>            Read-only [`CombinableSeriesTypesGroup`](/slides/python-net/es/aspose.slides.charts/combinableseriestypesgroup). |
| [`plot_on_second_axis`](/slides/python-net/es/aspose.slides.charts/chartseriesgroup/plot_on_second_axis/) | Indicates if series of this group is plotted on secondary axis.<br/>            Read-only **bool**. |
| [`series`](/slides/python-net/es/aspose.slides.charts/chartseriesgroup/series/) | Returns a collection of series.<br/>            Read-only [`IChartSeriesReadonlyCollection`](/slides/python-net/es/aspose.slides.charts/ichartseriesreadonlycollection). |
| [`up_down_bars`](/slides/python-net/es/aspose.slides.charts/chartseriesgroup/up_down_bars/) | Provede access to up/down bars of Line- or Stock-chart.<br/>            Read-only [`IUpDownBarsManager`](/slides/python-net/es/aspose.slides.charts/iupdownbarsmanager). |
| [`gap_width`](/slides/python-net/es/aspose.slides.charts/chartseriesgroup/gap_width/) | Specifies the space between bar or column clusters, as a percentage of the bar or column width.<br/>            Read/write **int**. |
| [`gap_depth`](/slides/python-net/es/aspose.slides.charts/chartseriesgroup/gap_depth/) | Returns or sets the distance, as a percentage of the marker width, between the data series in a 3D chart.<br/>            Read/write **int**. |
| [`first_slice_angle`](/slides/python-net/es/aspose.slides.charts/chartseriesgroup/first_slice_angle/) | Gets or sets the angle of the first pie or doughnut chart slice, <br/>            in degrees (clockwise from up, from 0 to 360 degrees).<br/>            Read/write **int**. |
| [`doughnut_hole_size`](/slides/python-net/es/aspose.slides.charts/chartseriesgroup/doughnut_hole_size/) | Specifies the size of the hole in a doughnut chart (can be between 0 and 90 percents <br/>            of the size of the plot area.).<br/>            Read/write **int**. |
| [`overlap`](/slides/python-net/es/aspose.slides.charts/chartseriesgroup/overlap/) | Specifies how much bars and columns shall overlap on 2-D charts, as a percentage (from -100% to 100%).<br/>             - -100%: Maximum spacing (bars are completely separated).<br/>             - 0%: Bars are placed side by side without overlap or spacing.<br/>             - 100%: Maximum overlap (bars completely overlap each other).<br/>             This property is read/write **int**. |
| [`second_pie_size`](/slides/python-net/es/aspose.slides.charts/chartseriesgroup/second_pie_size/) | Specifies the size of the second pie or bar of a pie-of-pie chart or <br/>            a bar-of-pie chart, as a percentage of the size of the first pie (can <br/>            be between 5 and 200 percents).<br/>            Read/write **int**. |
| [`bubble_size_representation`](/slides/python-net/es/aspose.slides.charts/chartseriesgroup/bubble_size_representation/) | Specifies how the bubble size values are represented on the bubble chart.<br/>            Read/write [`BubbleSizeRepresentationType`](/slides/python-net/es/aspose.slides.charts/bubblesizerepresentationtype). |
| [`pie_split_position`](/slides/python-net/es/aspose.slides.charts/chartseriesgroup/pie_split_position/) | Specifies a value that shall be used to determine which data points <br/>            are in the second pie or bar on a pie-of-pie or bar-of-pie chart. <br/>            Is used together with PieSplitBy property.<br/>            Read/write **float**. |
| [`pie_split_by`](/slides/python-net/es/aspose.slides.charts/chartseriesgroup/pie_split_by/) | Specifies how to determine which data points are in the second pie or bar <br/>            on a pie-of-pie or bar-of-pie chart.<br/>            Read/write [`PieSplitType`](/slides/python-net/es/aspose.slides.charts/piesplittype). |
| [`is_color_varied`](/slides/python-net/es/aspose.slides.charts/chartseriesgroup/is_color_varied/) | Specifies that each data marker in the series has a different color.<br/>            Read/write **bool**. |
| [`has_series_lines`](/slides/python-net/es/aspose.slides.charts/chartseriesgroup/has_series_lines/) | True if chart has series lines. Applied to stacked bar and OfPie charts.<br/>            Read/write **bool**. |
| [`hi_low_lines_format`](/slides/python-net/es/aspose.slides.charts/chartseriesgroup/hi_low_lines_format/) | Specifies HiLowLines format. <br/>            HiLowLines applied with HiLowClose, OpenHiLowClose, VolumeHiLowClose and VolumeOpenHiLowClose chart types. |
| [`bubble_size_scale`](/slides/python-net/es/aspose.slides.charts/chartseriesgroup/bubble_size_scale/) | Specifies the scale factor for the bubble chart (can be <br/>            between 0 and 300 percents of the default size).<br/>            Read/write **int**. |
| [`pie_split_custom_points`](/slides/python-net/es/aspose.slides.charts/chartseriesgroup/pie_split_custom_points/) | The custom split information for a pie-of-pie or bar-of-pie chart with a custom split.<br/>            Contains data points that shall be drawn in the second pie or bar in a pie-of-pie or <br/>            bar-of-pie chart.<br/>            Read-only [`PieSplitCustomPointCollection`](/slides/python-net/es/aspose.slides.charts/piesplitcustompointcollection). |
| [`chart`](/slides/python-net/es/aspose.slides.charts/chartseriesgroup/chart/) | Returns the parent chart.<br/>            Read-only [`IChart`](/slides/python-net/es/aspose.slides.charts/ichart). |
| [`slide`](/slides/python-net/es/aspose.slides.charts/chartseriesgroup/slide/) |  |
| [`presentation`](/slides/python-net/es/aspose.slides.charts/chartseriesgroup/presentation/) |  |

Gets the element at the specified index.

## Indexador

| Nombre | Descripción |
| :- | :- |
| [`[index]`](/slides/python-net/es/aspose.slides.charts/chartseriesgroup/__getitem__/) |  |


### Observaciones

1) See summary and remarks for ChartSeriesGroupCollection class and CombinableSeriesTypesGroup enum.
            2) Group of series contains some series properies whitch is common for 
            each series in group ("series group properties").
            "Series group properties" in ChartSeriesGroup class is read/write.
            Each of "series group properties" can have a read-only projection in ChartSeries class.


### Ver también
* módulo [`aspose.slides.charts`](/slides/python-net/es/aspose.slides.charts)
* biblioteca [`Aspose.Slides`](/slides/python-net)