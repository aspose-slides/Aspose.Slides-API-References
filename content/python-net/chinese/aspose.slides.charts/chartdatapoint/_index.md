---
title: ChartDataPoint class
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides.charts/chartdatapoint/
---
## ChartDataPoint 类

表示系列数据点。

ChartDataPoint 类型公开以下成员：

## 属性

| Property | Description |
| :- | :- |
| [`x_value`](/slides/python-net/zh/aspose.slides.charts/chartdatapoint/x_value/) | XValue.<br/>            只读 [`IStringOrDoubleChartValue`](/slides/python-net/zh/aspose.slides.charts/istringordoublechartvalue). |
| [`y_value`](/slides/python-net/zh/aspose.slides.charts/chartdatapoint/y_value/) | YValue.<br/>            只读 [`IDoubleChartValue`](/slides/python-net/zh/aspose.slides.charts/idoublechartvalue). |
| [`bubble_size`](/slides/python-net/zh/aspose.slides.charts/chartdatapoint/bubble_size/) | BubbleSize.<br/>            只读 [`IDoubleChartValue`](/slides/python-net/zh/aspose.slides.charts/idoublechartvalue). |
| [`value`](/slides/python-net/zh/aspose.slides.charts/chartdatapoint/value/) | Value.<br/>            只读 [`IDoubleChartValue`](/slides/python-net/zh/aspose.slides.charts/idoublechartvalue). |
| [`size_value`](/slides/python-net/zh/aspose.slides.charts/chartdatapoint/size_value/) | 返回图表数据点的大小值。<br/>            用于 Treemap 和 Sunburst 图表。 <br/>            只读 [`IDoubleChartValue`](/slides/python-net/zh/aspose.slides.charts/idoublechartvalue). |
| [`color_value`](/slides/python-net/zh/aspose.slides.charts/chartdatapoint/color_value/) | 返回图表数据点的颜色值。<br/>            用于 Map 图表。 <br/>            只读 [`IDoubleChartValue`](/slides/python-net/zh/aspose.slides.charts/idoublechartvalue). |
| [`error_bars_custom_values`](/slides/python-net/zh/aspose.slides.charts/chartdatapoint/error_bars_custom_values/) | 表示自定义值类型情况下的系列误差棒值。<br/>            只读 [`IErrorBarsCustomValues`](/slides/python-net/zh/aspose.slides.charts/ierrorbarscustomvalues). |
| [`label`](/slides/python-net/zh/aspose.slides.charts/chartdatapoint/label/) | Label。<br/>            只读 [`IDataLabel`](/slides/python-net/zh/aspose.slides.charts/idatalabel). |
| [`is_bubble_3d`](/slides/python-net/zh/aspose.slides.charts/chartdatapoint/is_bubble_3d/) | 指定气泡是否具有 3D 效果。<br/>            可读写 **bool**. |
| [`explosion`](/slides/python-net/zh/aspose.slides.charts/chartdatapoint/explosion/) | 指定数据点相对于饼图中心的移动量。<br/>            可读写 **int**. |
| [`format`](/slides/python-net/zh/aspose.slides.charts/chartdatapoint/format/) | 表示格式属性。<br/>            可读写 [`IFormat`](/slides/python-net/zh/aspose.slides.charts/iformat). |
| [`marker`](/slides/python-net/zh/aspose.slides.charts/chartdatapoint/marker/) | 指定数据标记。<br/>            只读 [`IMarker`](/slides/python-net/zh/aspose.slides.charts/imarker). |
| [`set_as_total`](/slides/python-net/zh/aspose.slides.charts/chartdatapoint/set_as_total/) | 将数据点设为总计。仅适用于 Waterfall 系列类型。 |
| [`related_legend_entry`](/slides/python-net/zh/aspose.slides.charts/chartdatapoint/related_legend_entry/) | 对于以下图表类型对应的图例项属性：<br/>            ChartType.BarOfPie,<br/>            ChartType.ExplodedPie,<br/>            ChartType.ExplodedPie3D,<br/>            ChartType.Pie,<br/>            ChartType.Pie3D,<br/>            ChartType.PieOfPie.<br/>            只读 [`ILegendEntryProperties`](/slides/python-net/zh/aspose.slides.charts/ilegendentryproperties). |
| [`data_point_levels`](/slides/python-net/zh/aspose.slides.charts/chartdatapoint/data_point_levels/) | 返回数据点级别的容器。仅适用于 Treeamp 和 Sunburst 系列。<br/>            数据点级别索引从零开始。 |
| [`index`](/slides/python-net/zh/aspose.slides.charts/chartdatapoint/index/) |  |
| [`invert_if_negative`](/slides/python-net/zh/aspose.slides.charts/chartdatapoint/invert_if_negative/) | 当值为负时，指定数据点应反转其颜色。<br/>            可读写 **bool**. |
| [`actual_x`](/slides/python-net/zh/aspose.slides.charts/chartdatapoint/actual_x/) | 指定图表元素相对于图表左上角的实际 X 位置（左）。<br/>            在调用 IChart.ValidateChartLayout() 之后获取实际值。 <br/>            只读 **float**. |
| [`actual_y`](/slides/python-net/zh/aspose.slides.charts/chartdatapoint/actual_y/) | 指定图表元素相对于图表左上角的实际顶部位置。<br/>            在调用 IChart.ValidateChartLayout() 之后获取实际值。 <br/>            只读 **float**. |
| [`actual_width`](/slides/python-net/zh/aspose.slides.charts/chartdatapoint/actual_width/) | 指定图表元素的实际宽度。调用 IChart.ValidateChartLayout() 之后获取实际值。 <br/>            只读 **float**. |
| [`actual_height`](/slides/python-net/zh/aspose.slides.charts/chartdatapoint/actual_height/) | 指定图表元素的实际高度。调用 IChart.ValidateChartLayout() 之后获取实际值。 <br/>            只读 **float**. |

## 方法

| Method | Description |
| :- | :- |
| [`remove(self)`](/slides/python-net/zh/aspose.slides.charts/chartdatapoint/remove/#) | 从图表系列中移除 DataPoint。 |
| [`get_automatic_data_point_color(self)`](/slides/python-net/zh/aspose.slides.charts/chartdatapoint/get_automatic_data_point_color/#) | 返回基于系列索引、数据点索引、ParentSeriesGroup.IsColorVaried 属性和图表样式的自动颜色。<br/>            如果 FillType 等于 NotDefined，则默认使用此颜色。 |

### 另请参见
* 模块 [`aspose.slides.charts`](/slides/python-net/zh/aspose.slides.charts)
* 库 [`Aspose.Slides`](/slides/python-net)