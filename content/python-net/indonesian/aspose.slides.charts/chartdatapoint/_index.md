---
title: ChartDataPoint class
second_title: Referensi API Aspose.Slides untuk Python via .NET
description: 
type: docs
url: /id/aspose.slides.charts/chartdatapoint/
---
## ChartDataPoint kelas

Mewakili titik data seri.

Tipe ChartDataPoint menampilkan anggota-anggota berikut:

## Properti

| Property | Description |
| :- | :- |
| [`x_value`](/slides/python-net/id/aspose.slides.charts/chartdatapoint/x_value/) | XValue.<br/>            Hanya-baca [`IStringOrDoubleChartValue`](/slides/python-net/id/aspose.slides.charts/istringordoublechartvalue). |
| [`y_value`](/slides/python-net/id/aspose.slides.charts/chartdatapoint/y_value/) | YValue.<br/>            Hanya-baca [`IDoubleChartValue`](/slides/python-net/id/aspose.slides.charts/idoublechartvalue). |
| [`bubble_size`](/slides/python-net/id/aspose.slides.charts/chartdatapoint/bubble_size/) | BubbleSize.<br/>            Hanya-baca [`IDoubleChartValue`](/slides/python-net/id/aspose.slides.charts/idoublechartvalue). |
| [`value`](/slides/python-net/id/aspose.slides.charts/chartdatapoint/value/) | Value.<br/>            Hanya-baca [`IDoubleChartValue`](/slides/python-net/id/aspose.slides.charts/idoublechartvalue). |
| [`size_value`](/slides/python-net/id/aspose.slides.charts/chartdatapoint/size_value/) | Returns the size value of chart data point.<br/>            Used with Treemap and Sunburst charts. <br/>            Hanya-baca [`IDoubleChartValue`](/slides/python-net/id/aspose.slides.charts/idoublechartvalue). |
| [`color_value`](/slides/python-net/id/aspose.slides.charts/chartdatapoint/color_value/) | Returns the color value of chart data point.<br/>            Used with Map charts. <br/>            Hanya-baca [`IDoubleChartValue`](/slides/python-net/id/aspose.slides.charts/idoublechartvalue). |
| [`error_bars_custom_values`](/slides/python-net/id/aspose.slides.charts/chartdatapoint/error_bars_custom_values/) | Represents series error bars values in case of Custom value type.<br/>            Hanya-baca [`IErrorBarsCustomValues`](/slides/python-net/id/aspose.slides.charts/ierrorbarscustomvalues). |
| [`label`](/slides/python-net/id/aspose.slides.charts/chartdatapoint/label/) | Label.<br/>            Hanya-baca [`IDataLabel`](/slides/python-net/id/aspose.slides.charts/idatalabel). |
| [`is_bubble_3d`](/slides/python-net/id/aspose.slides.charts/chartdatapoint/is_bubble_3d/) | Specifies that the bubbles have a 3-D effect applied to them.<br/>            Baca/tulis **bool**. |
| [`explosion`](/slides/python-net/id/aspose.slides.charts/chartdatapoint/explosion/) | Specifies the amount the data point shall be moved from the center of the pie.<br/>            Baca/tulis **int**. |
| [`format`](/slides/python-net/id/aspose.slides.charts/chartdatapoint/format/) | Represents the formatting properties.<br/>            Baca/tulis [`IFormat`](/slides/python-net/id/aspose.slides.charts/iformat). |
| [`marker`](/slides/python-net/id/aspose.slides.charts/chartdatapoint/marker/) | Specifies a data marker.<br/>            Hanya-baca [`IMarker`](/slides/python-net/id/aspose.slides.charts/imarker). |
| [`set_as_total`](/slides/python-net/id/aspose.slides.charts/chartdatapoint/set_as_total/) | Sets data point as total. Applied for Waterfall series type only. |
| [`related_legend_entry`](/slides/python-net/id/aspose.slides.charts/chartdatapoint/related_legend_entry/) | Properties of corresponding legend entry in case of chart type from this list:<br/>            ChartType.BarOfPie,<br/>            ChartType.ExplodedPie,<br/>            ChartType.ExplodedPie3D,<br/>            ChartType.Pie,<br/>            ChartType.Pie3D,<br/>            ChartType.PieOfPie.<br/>            Hanya-baca [`ILegendEntryProperties`](/slides/python-net/id/aspose.slides.charts/ilegendentryproperties). |
| [`data_point_levels`](/slides/python-net/id/aspose.slides.charts/chartdatapoint/data_point_levels/) | Returns container of  data point levels. Applied for Treeamp and Sunburst series.<br/>            Data point levels indexing is zero-based. |
| [`index`](/slides/python-net/id/aspose.slides.charts/chartdatapoint/index/) |  |
| [`invert_if_negative`](/slides/python-net/id/aspose.slides.charts/chartdatapoint/invert_if_negative/) | Specifies the data point shall invert its colors if the value is negative.<br/>            Baca/tulis **bool**. |
| [`cached_value`](/slides/python-net/id/aspose.slides.charts/chartdatapoint/cached_value/) | Gets the cached value of a chart data point.<br/>            Hanya-baca [`ICachedChartValue`](/slides/python-net/id/aspose.slides.charts/icachedchartvalue). |
| [`cached_x_value`](/slides/python-net/id/aspose.slides.charts/chartdatapoint/cached_x_value/) | Gets the cached X value of a chart data point.<br/>            Hanya-baca [`ICachedChartValue`](/slides/python-net/id/aspose.slides.charts/icachedchartvalue). |
| [`cached_y_value`](/slides/python-net/id/aspose.slides.charts/chartdatapoint/cached_y_value/) | Gets the cached Y value of a chart data point.<br/>            Hanya-baca [`ICachedChartValue`](/slides/python-net/id/aspose.slides.charts/icachedchartvalue). |
| [`cached_bubble_size`](/slides/python-net/id/aspose.slides.charts/chartdatapoint/cached_bubble_size/) | Gets the cached bubble size of a chart data point.<br/>            Hanya-baca [`ICachedChartValue`](/slides/python-net/id/aspose.slides.charts/icachedchartvalue). |
| [`actual_x`](/slides/python-net/id/aspose.slides.charts/chartdatapoint/actual_x/) | Specifies actual x location (left) of the chart element relative to the left top corner of the chart.<br/>            Call method IChart.ValidateChartLayout() before to get actual values. <br/>            Baca **float**. |
| [`actual_y`](/slides/python-net/id/aspose.slides.charts/chartdatapoint/actual_y/) | Specifies actual top of the chart element relative to the left top corner of the chart.<br/>            Call method IChart.ValidateChartLayout() before to get actual values. <br/>            Baca **float**. |
| [`actual_width`](/slides/python-net/id/aspose.slides.charts/chartdatapoint/actual_width/) | Specifies actual width of the chart element. Call method IChart.ValidateChartLayout() before to get actual values. <br/>            Baca **float**. |
| [`actual_height`](/slides/python-net/id/aspose.slides.charts/chartdatapoint/actual_height/) | Specifies actual height of the chart element. Call method IChart.ValidateChartLayout() before to get actual values. <br/>            Baca **float**. |

## Metode

| Method | Description |
| :- | :- |
| [`remove(self)`](/slides/python-net/id/aspose.slides.charts/chartdatapoint/remove/#) | Removes DataPoint from chart series. |
| [`get_automatic_data_point_color(self)`](/slides/python-net/id/aspose.slides.charts/chartdatapoint/get_automatic_data_point_color/#) | Returns an automatic color of data point based on series index, data point index, ParentSeriesGroup.IsColorVaried property and chart style.<br/>            This color is used by default if FillType equals NotDefined. |

### Lihat Juga
* modul [`aspose.slides.charts`](/slides/python-net/id/aspose.slides.charts)
* perpustakaan [`Aspose.Slides`](/slides/python-net)