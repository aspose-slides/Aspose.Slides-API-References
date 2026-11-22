---
title: IChartDataPoint class
second_title: Aspose.Slides for Python via .NET API 參考
description: 
type: docs
url: /zh-hant/aspose.slides.charts/ichartdatapoint/
---
## IChartDataPoint 類別

Represents series data point.

The IChartDataPoint type exposes the following members:

## 屬性

| 屬性 | 描述 |
| :- | :- |
| [`x_value`](/slides/python-net/zh-hant/aspose.slides.charts/ichartdatapoint/x_value/) | Gets the x value of a chart data point.<br/>            唯讀 [`IStringOrDoubleChartValue`](/slides/python-net/zh-hant/aspose.slides.charts/istringordoublechartvalue)。 |
| [`y_value`](/slides/python-net/zh-hant/aspose.slides.charts/ichartdatapoint/y_value/) | Gets the y value of a chart data point.<br/>            唯讀 [`IDoubleChartValue`](/slides/python-net/zh-hant/aspose.slides.charts/idoublechartvalue)。 |
| [`bubble_size`](/slides/python-net/zh-hant/aspose.slides.charts/ichartdatapoint/bubble_size/) | Gets the bubble size of a chart data point.<br/>            唯讀 [`IDoubleChartValue`](/slides/python-net/zh-hant/aspose.slides.charts/idoublechartvalue)。 |
| [`value`](/slides/python-net/zh-hant/aspose.slides.charts/ichartdatapoint/value/) | Gets the value of a chart data point.<br/>            唯讀 [`IDoubleChartValue`](/slides/python-net/zh-hant/aspose.slides.charts/idoublechartvalue)。 |
| [`cached_x_value`](/slides/python-net/zh-hant/aspose.slides.charts/ichartdatapoint/cached_x_value/) | Gets the cached X value of a chart data point.<br/>            唯讀 [`ICachedChartValue`](/slides/python-net/zh-hant/aspose.slides.charts/icachedchartvalue)。 |
| [`cached_y_value`](/slides/python-net/zh-hant/aspose.slides.charts/ichartdatapoint/cached_y_value/) | Gets the cached Y value of a chart data point.<br/>            唯讀 [`ICachedChartValue`](/slides/python-net/zh-hant/aspose.slides.charts/icachedchartvalue)。 |
| [`cached_value`](/slides/python-net/zh-hant/aspose.slides.charts/ichartdatapoint/cached_value/) | Gets the cached value of a chart data point.<br/>            唯讀 [`ICachedChartValue`](/slides/python-net/zh-hant/aspose.slides.charts/icachedchartvalue)。 |
| [`cached_bubble_size`](/slides/python-net/zh-hant/aspose.slides.charts/ichartdatapoint/cached_bubble_size/) | Gets the cached bubble size of a chart data point.<br/>            唯讀 [`ICachedChartValue`](/slides/python-net/zh-hant/aspose.slides.charts/icachedchartvalue)。 |
| [`size_value`](/slides/python-net/zh-hant/aspose.slides.charts/ichartdatapoint/size_value/) | Gets the size value of a chart data point.<br/>            Used with Treemap and Sunburst charts. <br/>            唯讀 [`IDoubleChartValue`](/slides/python-net/zh-hant/aspose.slides.charts/idoublechartvalue)。 |
| [`color_value`](/slides/python-net/zh-hant/aspose.slides.charts/ichartdatapoint/color_value/) | Gets the color value of a chart data point.<br/>            Used with Map charts. <br/>            唯讀 [`IDoubleChartValue`](/slides/python-net/zh-hant/aspose.slides.charts/idoublechartvalue)。 |
| [`error_bars_custom_values`](/slides/python-net/zh-hant/aspose.slides.charts/ichartdatapoint/error_bars_custom_values/) | Represents series error bars values in case of Custom value type.<br/>            唯讀 [`IErrorBarsCustomValues`](/slides/python-net/zh-hant/aspose.slides.charts/ierrorbarscustomvalues)。 |
| [`label`](/slides/python-net/zh-hant/aspose.slides.charts/ichartdatapoint/label/) | Represents the lable of chart data point.<br/>            唯讀 [`IDataLabel`](/slides/python-net/zh-hant/aspose.slides.charts/idatalabel)。 |
| [`is_bubble_3d`](/slides/python-net/zh-hant/aspose.slides.charts/ichartdatapoint/is_bubble_3d/) | Specifies that the bubbles have a 3-D effect applied to them.<br/>            可讀寫 **bool**。 |
| [`explosion`](/slides/python-net/zh-hant/aspose.slides.charts/ichartdatapoint/explosion/) | Specifies the amount the data point shall be moved from the center of the pie.<br/>            可讀寫 **int**。 |
| [`format`](/slides/python-net/zh-hant/aspose.slides.charts/ichartdatapoint/format/) | Represents the formatting properties.<br/>            可讀寫 [`IFormat`](/slides/python-net/zh-hant/aspose.slides.charts/iformat)。 |
| [`marker`](/slides/python-net/zh-hant/aspose.slides.charts/ichartdatapoint/marker/) | Specifies a data marker.<br/>            唯讀 [`IMarker`](/slides/python-net/zh-hant/aspose.slides.charts/imarker)。 |
| [`related_legend_entry`](/slides/python-net/zh-hant/aspose.slides.charts/ichartdatapoint/related_legend_entry/) | Properties of corresponding legend entry in case of chart type from this list:<br/>            ChartType.BarOfPie,<br/>            ChartType.ExplodedPie,<br/>            ChartType.ExplodedPie3D,<br/>            ChartType.Pie,<br/>            ChartType.Pie3D,<br/>            ChartType.PieOfPie.<br/>            唯讀 [`ILegendEntryProperties`](/slides/python-net/zh-hant/aspose.slides.charts/ilegendentryproperties)。 |
| [`set_as_total`](/slides/python-net/zh-hant/aspose.slides.charts/ichartdatapoint/set_as_total/) | Sets data point as total. Applied for Waterfall series type only. |
| [`invert_if_negative`](/slides/python-net/zh-hant/aspose.slides.charts/ichartdatapoint/invert_if_negative/) | Specifies the data point shall invert its colors if the value is negative.<br/>            可讀寫 **bool**。 |
| [`data_point_levels`](/slides/python-net/zh-hant/aspose.slides.charts/ichartdatapoint/data_point_levels/) | Returns container of  data point levels. Applied for Treeamp and Sunburst series.<br/>            Data point levels indexing is zero-based. |
| [`index`](/slides/python-net/zh-hant/aspose.slides.charts/ichartdatapoint/index/) | Determines which of the parent's children collection this data point applies to.<br/>            唯讀 **int**。 |
| [`actual_x`](/slides/python-net/zh-hant/aspose.slides.charts/ichartdatapoint/actual_x/) |  |
| [`actual_y`](/slides/python-net/zh-hant/aspose.slides.charts/ichartdatapoint/actual_y/) |  |
| [`actual_width`](/slides/python-net/zh-hant/aspose.slides.charts/ichartdatapoint/actual_width/) |  |
| [`actual_height`](/slides/python-net/zh-hant/aspose.slides.charts/ichartdatapoint/actual_height/) |  |

## 方法

| 方法 | 描述 |
| :- | :- |
| [`remove(self)`](/slides/python-net/zh-hant/aspose.slides.charts/ichartdatapoint/remove/#) | Removes DataPoint from chart series. |
| [`get_automatic_data_point_color(self)`](/slides/python-net/zh-hant/aspose.slides.charts/ichartdatapoint/get_automatic_data_point_color/#) | Returns an automatic color of data point based on series index, data point index, ParentSeriesGroup.IsColorVaried propery and chart style. <br/>            若 FillType equals NotDefined，則預設使用此顏色。 |

### 另請參見
* 模組 [`aspose.slides.charts`](/slides/python-net/zh-hant/aspose.slides.charts)
* 函式庫 [`Aspose.Slides`](/slides/python-net)