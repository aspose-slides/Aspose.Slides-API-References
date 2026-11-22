---
title: ChartSeriesGroup class
second_title: مرجع API لـ Aspose.Slides للغة بايثون عبر .NET
description: 
type: docs
url: /ar/aspose.slides.charts/chartseriesgroup/
---
## ChartSeriesGroup فئة

يمثل مجموعة من السلاسل.

نوع ChartSeriesGroup يكشف عن الأعضاء التالية:

## الخصائص

| الخاصية | الوصف |
| :- | :- |
| [`type`](/slides/python-net/ar/aspose.slides.charts/chartseriesgroup/type/) | Returns a type of this series group.<br/>            للقراءة فقط [`CombinableSeriesTypesGroup`](/slides/python-net/ar/aspose.slides.charts/combinableseriestypesgroup). |
| [`plot_on_second_axis`](/slides/python-net/ar/aspose.slides.charts/chartseriesgroup/plot_on_second_axis/) | Indicates if series of this group is plotted on secondary axis.<br/>            للقراءة فقط **bool**. |
| [`series`](/slides/python-net/ar/aspose.slides.charts/chartseriesgroup/series/) | Returns a collection of series.<br/>            للقراءة فقط [`IChartSeriesReadonlyCollection`](/slides/python-net/ar/aspose.slides.charts/ichartseriesreadonlycollection). |
| [`up_down_bars`](/slides/python-net/ar/aspose.slides.charts/chartseriesgroup/up_down_bars/) | Provede access to up/down bars of Line- or Stock-chart.<br/>            للقراءة فقط [`IUpDownBarsManager`](/slides/python-net/ar/aspose.slides.charts/iupdownbarsmanager). |
| [`gap_width`](/slides/python-net/ar/aspose.slides.charts/chartseriesgroup/gap_width/) | Gets or sets the space between bar or column clusters, as a percentage of the bar or column width.<br/>            The value must be between 0 and 500.<br/>            قراءة/كتابة **int**. |
| [`gap_depth`](/slides/python-net/ar/aspose.slides.charts/chartseriesgroup/gap_depth/) | Gets or sets the distance between data series in a 3D chart, as a percentage of the marker width.<br/>            The value must be between 0 and 500.<br/>            قراءة/كتابة **int**. |
| [`first_slice_angle`](/slides/python-net/ar/aspose.slides.charts/chartseriesgroup/first_slice_angle/) | Gets or sets the angle of the first pie or doughnut chart slice, <br/>            in degrees (clockwise from up, from 0 to 360 degrees).<br/>            قراءة/كتابة **int**. |
| [`doughnut_hole_size`](/slides/python-net/ar/aspose.slides.charts/chartseriesgroup/doughnut_hole_size/) | Specifies the size of the hole in a doughnut chart (can be between 0 and 90 percents <br/>            of the size of the plot area.).<br/>            قراءة/كتابة **int**. |
| [`overlap`](/slides/python-net/ar/aspose.slides.charts/chartseriesgroup/overlap/) | Specifies how much bars and columns shall overlap on 2-D charts, as a percentage (from -100% to 100%).<br/>             - -100%: Maximum spacing (bars are completely separated).<br/>             - 0%: Bars are placed side by side without overlap or spacing.<br/>             - 100%: Maximum overlap (bars completely overlap each other).<br/>             هذه الخاصية قراءة/كتابة **int**. |
| [`second_pie_size`](/slides/python-net/ar/aspose.slides.charts/chartseriesgroup/second_pie_size/) | Specifies the size of the second pie or bar of a pie-of-pie chart or <br/>            a bar-of-pie chart, as a percentage of the size of the first pie (can <br/>            be between 5 and 200 percents).<br/>            قراءة/كتابة **int**. |
| [`bubble_size_representation`](/slides/python-net/ar/aspose.slides.charts/chartseriesgroup/bubble_size_representation/) | Specifies how the bubble size values are represented on the bubble chart.<br/>            قراءة/كتابة [`BubbleSizeRepresentationType`](/slides/python-net/ar/aspose.slides.charts/bubblesizerepresentationtype). |
| [`pie_split_position`](/slides/python-net/ar/aspose.slides.charts/chartseriesgroup/pie_split_position/) | Specifies a value that shall be used to determine which data points <br/>            are in the second pie or bar on a pie-of-pie or bar-of-pie chart. <br/>            Is used together with PieSplitBy property.<br/>            قراءة/كتابة **float**. |
| [`pie_split_by`](/slides/python-net/ar/aspose.slides.charts/chartseriesgroup/pie_split_by/) | Specifies how to determine which data points are in the second pie or bar <br/>            on a pie-of-pie or bar-of-pie chart.<br/>            قراءة/كتابة [`PieSplitType`](/slides/python-net/ar/aspose.slides.charts/piesplittype). |
| [`is_color_varied`](/slides/python-net/ar/aspose.slides.charts/chartseriesgroup/is_color_varied/) | Specifies that each data marker in the series has a different color.<br/>            قراءة/كتابة **bool**. |
| [`has_series_lines`](/slides/python-net/ar/aspose.slides.charts/chartseriesgroup/has_series_lines/) | True if chart has series lines. Applied to stacked bar and OfPie charts.<br/>            قراءة/كتابة **bool**. |
| [`hi_low_lines_format`](/slides/python-net/ar/aspose.slides.charts/chartseriesgroup/hi_low_lines_format/) | Specifies HiLowLines format. <br/>            HiLowLines applied with HiLowClose, OpenHiLowClose, VolumeHiLowClose and VolumeOpenHiLowClose chart types. |
| [`bubble_size_scale`](/slides/python-net/ar/aspose.slides.charts/chartseriesgroup/bubble_size_scale/) | Specifies the scale factor for the bubble chart (can be <br/>            between 0 and 300 percents of the default size).<br/>            قراءة/كتابة **int**. |
| [`pie_split_custom_points`](/slides/python-net/ar/aspose.slides.charts/chartseriesgroup/pie_split_custom_points/) | The custom split information for a pie-of-pie or bar-of-pie chart with a custom split.<br/>            Contains data points that shall be drawn in the second pie or bar in a pie-of-pie or <br/>            bar-of-pie chart.<br/>            للقراءة فقط [`PieSplitCustomPointCollection`](/slides/python-net/ar/aspose.slides.charts/piesplitcustompointcollection). |
| [`chart`](/slides/python-net/ar/aspose.slides.charts/chartseriesgroup/chart/) | Returns the parent chart.<br/>            للقراءة فقط [`IChart`](/slides/python-net/ar/aspose.slides.charts/ichart). |
| [`slide`](/slides/python-net/ar/aspose.slides.charts/chartseriesgroup/slide/) |  |
| [`presentation`](/slides/python-net/ar/aspose.slides.charts/chartseriesgroup/presentation/) |  |

يحصل على العنصر عند الفهرس المحدد.

## الفهرس

| الاسم | الوصف |
| :- | :- |
| [`[index]`](/slides/python-net/ar/aspose.slides.charts/chartseriesgroup/__getitem__/) |  |

### ملاحظات

1) راجع الملخص والملاحظات لفئة ChartSeriesGroupCollection و CombinableSeriesTypesGroup enum.  
2) مجموعة السلاسل تحتوي على بعض خصائص السلاسل التي تكون مشتركة لكل سلسلة في المجموعة ("خصائص مجموعة السلاسل"). "خصائص مجموعة السلاسل" في فئة ChartSeriesGroup هي قراءة/كتابة. كل من "خصائص مجموعة السلاسل" يمكن أن يكون له إسقاط للقراءة فقط في فئة ChartSeries.

### انظر أيضا
* وحدة [`aspose.slides.charts`](/slides/python-net/ar/aspose.slides.charts)
* مكتبة [`Aspose.Slides`](/slides/python-net)