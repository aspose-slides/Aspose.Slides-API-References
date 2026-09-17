---
title: IChartDataPoint class
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides.charts/ichartdatapoint/
---
## IChartDataPoint 类

表示系列数据点。

The IChartDataPoint type exposes the following members:

## 属性

| Property | Description |
| :- | :- |
| [`x_value`](/slides/python-net/zh/aspose.slides.charts/ichartdatapoint/x_value/) | 返回图表数据点的 x 值。<br/>            只读 [`IStringOrDoubleChartValue`](/slides/python-net/zh/aspose.slides.charts/istringordoublechartvalue). |
| [`y_value`](/slides/python-net/zh/aspose.slides.charts/ichartdatapoint/y_value/) | 返回图表数据点的 y 值。<br/>            只读 [`IDoubleChartValue`](/slides/python-net/zh/aspose.slides.charts/idoublechartvalue). |
| [`bubble_size`](/slides/python-net/zh/aspose.slides.charts/ichartdatapoint/bubble_size/) | 返回图表数据点的气泡大小。<br/>            只读 [`IDoubleChartValue`](/slides/python-net/zh/aspose.slides.charts/idoublechartvalue). |
| [`value`](/slides/python-net/zh/aspose.slides.charts/ichartdatapoint/value/) | 返回图表数据点的值。<br/>            只读 [`IDoubleChartValue`](/slides/python-net/zh/aspose.slides.charts/idoublechartvalue). |
| [`size_value`](/slides/python-net/zh/aspose.slides.charts/ichartdatapoint/size_value/) | 返回图表数据点的大小值。<br/>            用于树图和旭日图。<br/>            只读 [`IDoubleChartValue`](/slides/python-net/zh/aspose.slides.charts/idoublechartvalue). |
| [`color_value`](/slides/python-net/zh/aspose.slides.charts/ichartdatapoint/color_value/) | 返回图表数据点的颜色值。<br/>            用于地图图表。<br/>            只读 [`IDoubleChartValue`](/slides/python-net/zh/aspose.slides.charts/idoublechartvalue). |
| [`error_bars_custom_values`](/slides/python-net/zh/aspose.slides.charts/ichartdatapoint/error_bars_custom_values/) | 表示自定义值类型情况下系列误差线的值。<br/>            只读 [`IErrorBarsCustomValues`](/slides/python-net/zh/aspose.slides.charts/ierrorbarscustomvalues). |
| [`label`](/slides/python-net/zh/aspose.slides.charts/ichartdatapoint/label/) | 表示图表数据点的标签。<br/>            只读 [`IDataLabel`](/slides/python-net/zh/aspose.slides.charts/idatalabel). |
| [`is_bubble_3d`](/slides/python-net/zh/aspose.slides.charts/ichartdatapoint/is_bubble_3d/) | 指定气泡应用了 3-D 效果。<br/>            读写 **bool**. |
| [`explosion`](/slides/python-net/zh/aspose.slides.charts/ichartdatapoint/explosion/) | 指定数据点相对于饼图中心的移动量。<br/>            读写 **int**. |
| [`format`](/slides/python-net/zh/aspose.slides.charts/ichartdatapoint/format/) | 表示格式属性。<br/>            读写 [`IFormat`](/slides/python-net/zh/aspose.slides.charts/iformat). |
| [`marker`](/slides/python-net/zh/aspose.slides.charts/ichartdatapoint/marker/) | 指定数据标记。<br/>            只读 [`IMarker`](/slides/python-net/zh/aspose.slides.charts/imarker). |
| [`related_legend_entry`](/slides/python-net/zh/aspose.slides.charts/ichartdatapoint/related_legend_entry/) | 对应图例条目的属性，适用于以下图表类型：<br/>            ChartType.BarOfPie,<br/>            ChartType.ExplodedPie,<br/>            ChartType.ExplodedPie3D,<br/>            ChartType.Pie,<br/>            ChartType.Pie3D,<br/>            ChartType.PieOfPie.<br/>            只读 [`ILegendEntryProperties`](/slides/python-net/zh/aspose.slides.charts/ilegendentryproperties). |
| [`set_as_total`](/slides/python-net/zh/aspose.slides.charts/ichartdatapoint/set_as_total/) | 将数据点设置为总计。仅适用于瀑布系列类型。 |
| [`invert_if_negative`](/slides/python-net/zh/aspose.slides.charts/ichartdatapoint/invert_if_negative/) | 指定如果值为负，则数据点应反转其颜色。<br/>            读写 **bool**. |
| [`data_point_levels`](/slides/python-net/zh/aspose.slides.charts/ichartdatapoint/data_point_levels/) | 返回数据点级别的容器。适用于 Treeamp 和 Sunburst 系列。<br/>            数据点级别索引从零开始。 |
| [`index`](/slides/python-net/zh/aspose.slides.charts/ichartdatapoint/index/) | 确定此数据点适用于父级子集合中的哪个。<br/>            只读 **int**. |
| [`actual_x`](/slides/python-net/zh/aspose.slides.charts/ichartdatapoint/actual_x/) |  |
| [`actual_y`](/slides/python-net/zh/aspose.slides.charts/ichartdatapoint/actual_y/) |  |
| [`actual_width`](/slides/python-net/zh/aspose.slides.charts/ichartdatapoint/actual_width/) |  |
| [`actual_height`](/slides/python-net/zh/aspose.slides.charts/ichartdatapoint/actual_height/) |  |

## 方法

| Method | Description |
| :- | :- |
| [`remove(self)`](/slides/python-net/zh/aspose.slides.charts/ichartdatapoint/remove/#) | 从图表系列中移除数据点。 |
| [`get_automatic_data_point_color(self)`](/slides/python-net/zh/aspose.slides.charts/ichartdatapoint/get_automatic_data_point_color/#) | 返回基于系列索引、数据点索引、ParentSeriesGroup.IsColorVaried 属性和图表样式的自动颜色。<br/>            如果 FillType 等于 NotDefined，则默认使用此颜色。 |


### 另请参阅
* 模块 [`aspose.slides.charts`](/slides/python-net/zh/aspose.slides.charts)
* 库 [`Aspose.Slides`](/slides/python-net)