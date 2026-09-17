---
title: IAxis class
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides.charts/iaxis/
---
## IAxis 类

Encapsulates the object that represents a chart's axis.

The IAxis type exposes the following members:

## 属性

| Property | Description |
| :- | :- |
| [`axis_between_categories`](/slides/python-net/zh/aspose.slides.charts/iaxis/axis_between_categories/) | 表示值轴是否在类别之间穿过类别轴。<br/>            此属性仅适用于类别轴，不适用于 3-D 图表。<br/>            读/写 **bool**. |
| [`cross_at`](/slides/python-net/zh/aspose.slides.charts/iaxis/cross_at/) | 表示轴上垂直轴交叉的点。<br/>            读/写 **float**. |
| [`display_unit`](/slides/python-net/zh/aspose.slides.charts/iaxis/display_unit/) | 指定值轴显示单位的缩放值。<br/>            读/写 [`DisplayUnitType`](/slides/python-net/zh/aspose.slides.charts/displayunittype). |
| [`actual_max_value`](/slides/python-net/zh/aspose.slides.charts/iaxis/actual_max_value/) | 指定轴上的实际最大值。请先调用方法 IChart.ValidateChartLayout() 以获取实际值。 |
| [`actual_min_value`](/slides/python-net/zh/aspose.slides.charts/iaxis/actual_min_value/) | 指定轴上的实际最小值。请先调用方法 IChart.ValidateChartLayout() 以获取实际值。 |
| [`actual_major_unit`](/slides/python-net/zh/aspose.slides.charts/iaxis/actual_major_unit/) | 指定轴的实际主要单位。请先调用方法 IChart.ValidateChartLayout() 以获取实际值。 |
| [`actual_minor_unit`](/slides/python-net/zh/aspose.slides.charts/iaxis/actual_minor_unit/) | 指定轴的实际次要单位。请先调用方法 IChart.ValidateChartLayout() 以获取实际值。 |
| [`actual_major_unit_scale`](/slides/python-net/zh/aspose.slides.charts/iaxis/actual_major_unit_scale/) | 指定轴的实际主要单位比例。请先调用方法 IChart.ValidateChartLayout() 以获取实际值。 |
| [`actual_minor_unit_scale`](/slides/python-net/zh/aspose.slides.charts/iaxis/actual_minor_unit_scale/) | 指定轴的实际次要单位比例。请先调用方法 IChart.ValidateChartLayout() 以获取实际值。 |
| [`is_automatic_max_value`](/slides/python-net/zh/aspose.slides.charts/iaxis/is_automatic_max_value/) | 指示最大值是否自动分配。<br/>             读/写 **bool**. |
| [`max_value`](/slides/python-net/zh/aspose.slides.charts/iaxis/max_value/) | 表示值轴上的最大值。<br/>             读/写 **float**. |
| [`minor_unit`](/slides/python-net/zh/aspose.slides.charts/iaxis/minor_unit/) | 表示日期或值轴的次要单位。<br/>             读/写 **float**. |
| [`is_automatic_minor_unit`](/slides/python-net/zh/aspose.slides.charts/iaxis/is_automatic_minor_unit/) | 指示轴的次要单位是否自动分配。<br/>             读/写 **bool**. |
| [`major_unit`](/slides/python-net/zh/aspose.slides.charts/iaxis/major_unit/) | 表示日期或值轴的主要单位。<br/>             读/写 **float**. |
| [`is_automatic_major_unit`](/slides/python-net/zh/aspose.slides.charts/iaxis/is_automatic_major_unit/) | 指示轴的主要单位是否自动分配。<br/>            读/写 **bool**. |
| [`is_automatic_min_value`](/slides/python-net/zh/aspose.slides.charts/iaxis/is_automatic_min_value/) | 指示最小值是否自动分配。<br/>             读/写 **bool**. |
| [`min_value`](/slides/python-net/zh/aspose.slides.charts/iaxis/min_value/) | 表示值轴上的最小值。<br/>             读/写 **float**. |
| [`is_logarithmic`](/slides/python-net/zh/aspose.slides.charts/iaxis/is_logarithmic/) | 表示值轴的刻度类型是否为对数。<br/>             读/写 **bool**. |
| [`log_base`](/slides/python-net/zh/aspose.slides.charts/iaxis/log_base/) | 表示对数基数。默认值为 10。<br/>             读/写 **float**. |
| [`is_plot_order_reversed`](/slides/python-net/zh/aspose.slides.charts/iaxis/is_plot_order_reversed/) | 表示 MS PowerPoint 是否从最后到第一绘制数据点。<br/>             读/写 **bool**. |
| [`is_visible`](/slides/python-net/zh/aspose.slides.charts/iaxis/is_visible/) | 表示轴是否可见。<br/>             读/写 **bool**. |
| [`major_tick_mark`](/slides/python-net/zh/aspose.slides.charts/iaxis/major_tick_mark/) | 表示指定轴的主要刻度标记类型。<br/>             读/写 [`TickMarkType`](/slides/python-net/zh/aspose.slides.charts/tickmarktype). |
| [`minor_tick_mark`](/slides/python-net/zh/aspose.slides.charts/iaxis/minor_tick_mark/) | 表示指定轴的次要刻度标记类型。<br/>             读/写 [`TickMarkType`](/slides/python-net/zh/aspose.slides.charts/tickmarktype). |
| [`tick_label_position`](/slides/python-net/zh/aspose.slides.charts/iaxis/tick_label_position/) | 表示指定轴上刻度标签的位置。<br/>             读/写 [`TickLabelPositionType`](/slides/python-net/zh/aspose.slides.charts/ticklabelpositiontype). |
| [`major_unit_scale`](/slides/python-net/zh/aspose.slides.charts/iaxis/major_unit_scale/) | 表示日期轴的主要单位比例。<br/>             读/写 [`TimeUnitType`](/slides/python-net/zh/aspose.slides.charts/timeunittype). |
| [`minor_unit_scale`](/slides/python-net/zh/aspose.slides.charts/iaxis/minor_unit_scale/) | 表示日期轴的主要单位比例。<br/>             读/写 [`TimeUnitType`](/slides/python-net/zh/aspose.slides.charts/timeunittype). |
| [`base_unit_scale`](/slides/python-net/zh/aspose.slides.charts/iaxis/base_unit_scale/) | 指定日期轴上表示的最小时间单位。<br/>            读/写 [`TimeUnitType`](/slides/python-net/zh/aspose.slides.charts/timeunittype). |
| [`minor_grid_lines_format`](/slides/python-net/zh/aspose.slides.charts/iaxis/minor_grid_lines_format/) | 表示图表轴上的次要网格线格式。<br/>             只读 [`IChartLinesFormat`](/slides/python-net/zh/aspose.slides.charts/ichartlinesformat). |
| [`major_grid_lines_format`](/slides/python-net/zh/aspose.slides.charts/iaxis/major_grid_lines_format/) | 表示图表轴上的主要网格线格式。<br/>             只读 [`IChartLinesFormat`](/slides/python-net/zh/aspose.slides.charts/ichartlinesformat). |
| [`show_minor_grid_lines`](/slides/python-net/zh/aspose.slides.charts/iaxis/show_minor_grid_lines/) | 表示是否显示次要网格线。<br/>             只读 **bool**. |
| [`show_major_grid_lines`](/slides/python-net/zh/aspose.slides.charts/iaxis/show_major_grid_lines/) | 表示是否显示主要网格线。<br/>             只读 **bool**. |
| [`format`](/slides/python-net/zh/aspose.slides.charts/iaxis/format/) | 表示轴的格式。<br/>             只读 [`IAxisFormat`](/slides/python-net/zh/aspose.slides.charts/iaxisformat). |
| [`title`](/slides/python-net/zh/aspose.slides.charts/iaxis/title/) | 获取轴的标题。<br/>             只读 [`IChartTitle`](/slides/python-net/zh/aspose.slides.charts/icharttitle). |
| [`cross_type`](/slides/python-net/zh/aspose.slides.charts/iaxis/cross_type/) | 表示指定轴上另一轴交叉的 CrossType。<br/>             读/写 [`CrossesType`](/slides/python-net/zh/aspose.slides.charts/crossestype). |
| [`position`](/slides/python-net/zh/aspose.slides.charts/iaxis/position/) | 表示轴的位置。<br/>             读/写 [`AxisPositionType`](/slides/python-net/zh/aspose.slides.charts/axispositiontype). |
| [`has_title`](/slides/python-net/zh/aspose.slides.charts/iaxis/has_title/) | 确定轴是否具有可见标题。<br/>            读/写 **bool**. |
| [`number_format`](/slides/python-net/zh/aspose.slides.charts/iaxis/number_format/) | 表示轴标签的格式字符串。<br/>            读/写 **str**. |
| [`is_number_format_linked_to_source`](/slides/python-net/zh/aspose.slides.charts/iaxis/is_number_format_linked_to_source/) | 指示格式是否链接到源数据。<br/>            读/写 **bool**. |
| [`tick_label_rotation_angle`](/slides/python-net/zh/aspose.slides.charts/iaxis/tick_label_rotation_angle/) | 表示刻度标签的旋转角度<br/>            读/写 **float**. |
| [`tick_label_spacing`](/slides/python-net/zh/aspose.slides.charts/iaxis/tick_label_spacing/) | 指定在绘制的标签之间要跳过的刻度标签数量。<br/>            读/写 **int**. |
| [`is_automatic_tick_label_spacing`](/slides/python-net/zh/aspose.slides.charts/iaxis/is_automatic_tick_label_spacing/) | 指定自动刻度标签间距值。如果为 false：使用 TickLabelSpacing 属性。<br/>            读/写 **bool**. |
| [`tick_marks_spacing`](/slides/python-net/zh/aspose.slides.charts/iaxis/tick_marks_spacing/) | 指定在绘制下一个刻度标记前应跳过的刻度标记数量。<br/>            应用于类别或系列轴。<br/>            读/写 **int**. |
| [`is_automatic_tick_marks_spacing`](/slides/python-net/zh/aspose.slides.charts/iaxis/is_automatic_tick_marks_spacing/) | 指定自动刻度标记间距值。如果为 false：使用 TickMarksSpacing 属性。<br/>            读/写 **bool**. |
| [`label_offset`](/slides/python-net/zh/aspose.slides.charts/iaxis/label_offset/) | 指定标签距离轴的距离。适用于类别或日期轴。值必须在 0% 到 1000% 之间。<br/>            读/写 **int**. |
| [`category_axis_type`](/slides/python-net/zh/aspose.slides.charts/iaxis/category_axis_type/) | 指定类别轴的类型。<br/>            读/写 [`IAxis.category_axis_type`](/slides/python-net/zh/aspose.slides.charts/iaxis/category_axis_type). |
| [`aggregation_type`](/slides/python-net/zh/aspose.slides.charts/iaxis/aggregation_type/) | 表示类别轴的聚合类型（分箱）。适用于类别。仅与 Histogram 或 HistogramPareto 系列一起使用。 |
| [`bin_width`](/slides/python-net/zh/aspose.slides.charts/iaxis/bin_width/) | 当 AggregationType 属性值设置为 AxisAggregationType.ByBinWidth 时指定分箱宽度。<br/>            适用于类别轴。仅与 Histogram 或 HistogramPareto 系列一起使用。 |
| [`number_of_bins`](/slides/python-net/zh/aspose.slides.charts/iaxis/number_of_bins/) | 当 AggregationType 属性值设置为 AxisAggregationType.ByNumberOfBins 时指定分箱数量。<br/>            适用于类别轴。仅与 Histogram 或 HistogramPareto 系列一起使用。 |
| [`is_overflow_bin`](/slides/python-net/zh/aspose.slides.charts/iaxis/is_overflow_bin/) | 指定是否应用溢出分箱。使用 IsAutomaticOverflowBin 和 OverflowBin 调整溢出分箱值。 |
| [`is_automatic_overflow_bin`](/slides/python-net/zh/aspose.slides.charts/iaxis/is_automatic_overflow_bin/) | 指定自动溢出分箱值。如果为 false：使用 OverflowBin 属性。 |
| [`overflow_bin`](/slides/python-net/zh/aspose.slides.charts/iaxis/overflow_bin/) | 指定溢出分箱的自定义值。当 IsAutomaticOverflowBin 属性设置为 false 且 IsOverflowBin 属性为 true 时适用。 |
| [`is_underflow_bin`](/slides/python-net/zh/aspose.slides.charts/iaxis/is_underflow_bin/) | 指定是否应用下溢分箱。使用 IsAutomaticUnderflowBin 和 UnderflowBin 调整下溢分箱值。 |
| [`is_automatic_underflow_bin`](/slides/python-net/zh/aspose.slides.charts/iaxis/is_automatic_underflow_bin/) | 指定自动下溢分箱值。如果为 false：使用 UnderflowBin 属性。 |
| [`underflow_bin`](/slides/python-net/zh/aspose.slides.charts/iaxis/underflow_bin/) | 指定下溢分箱的自定义值。当 IsAutomaticUnderflowBin 属性设置为 false 且 IsUnderflowBin 属性为 true 时适用。 |
| [`text_format`](/slides/python-net/zh/aspose.slides.charts/iaxis/text_format/) |  |
| [`chart`](/slides/python-net/zh/aspose.slides.charts/iaxis/chart/) |  |
| [`slide`](/slides/python-net/zh/aspose.slides.charts/iaxis/slide/) |  |
| [`presentation`](/slides/python-net/zh/aspose.slides.charts/iaxis/presentation/) |  |

## 方法

| Method | Description |
| :- | :- |
| [`set_category_axis_type_automatically(self)`](/slides/python-net/zh/aspose.slides.charts/iaxis/set_category_axis_type_automatically/#) | 使用基于轴数据自动确定的值设置 IAxis.CategoryAxisType 属性。 |

### 另见
* 模块 [`aspose.slides.charts`](/slides/python-net/zh/aspose.slides.charts)
* 库 [`Aspose.Slides`](/slides/python-net)