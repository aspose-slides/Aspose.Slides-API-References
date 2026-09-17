---
title: Axis class
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides.charts/axis/
---
## Axis 类

封装表示图表轴的对象。

Axis 类型公开以下成员：

## 属性

| Property | Description |
| :- | :- |
| [`chart`](/slides/python-net/zh/aspose.slides.charts/axis/chart/) | 返回父图表。<br/>            只读 [`IChart`](/slides/python-net/zh/aspose.slides.charts/ichart). |
| [`axis_between_categories`](/slides/python-net/zh/aspose.slides.charts/axis/axis_between_categories/) | 表示值轴是否在类别之间穿过类别轴。<br/>             此属性仅适用于类别轴，不适用于 3-D 图表。<br/>             可读写 **bool**. |
| [`category_axis_type`](/slides/python-net/zh/aspose.slides.charts/axis/category_axis_type/) | 指定类别轴的类型。<br/>            可读写 [`CategoryAxisType`](/slides/python-net/zh/aspose.slides.charts/categoryaxistype). |
| [`cross_at`](/slides/python-net/zh/aspose.slides.charts/axis/cross_at/) | 表示垂直轴穿过该轴的点位置。<br/>             可读写 **float**. |
| [`display_unit`](/slides/python-net/zh/aspose.slides.charts/axis/display_unit/) | 指定值轴显示单位的缩放值。<br/>             可读写 [`DisplayUnitType`](/slides/python-net/zh/aspose.slides.charts/displayunittype). |
| [`actual_max_value`](/slides/python-net/zh/aspose.slides.charts/axis/actual_max_value/) | 指定轴上的实际最大值。请先调用 IChart.ValidateChartLayout() 方法以获取实际值。 |
| [`actual_min_value`](/slides/python-net/zh/aspose.slides.charts/axis/actual_min_value/) | 指定轴上的实际最小值。请先调用 IChart.ValidateChartLayout() 方法以获取实际值。 |
| [`actual_major_unit`](/slides/python-net/zh/aspose.slides.charts/axis/actual_major_unit/) | 指定轴的实际主单位。请先调用 IChart.ValidateChartLayout() 方法以获取实际值。 |
| [`actual_minor_unit`](/slides/python-net/zh/aspose.slides.charts/axis/actual_minor_unit/) | 指定轴的实际次单位。请先调用 IChart.ValidateChartLayout() 方法以获取实际值。 |
| [`actual_major_unit_scale`](/slides/python-net/zh/aspose.slides.charts/axis/actual_major_unit_scale/) | 指定轴的实际主单位比例。请先调用 IChart.ValidateChartLayout() 方法以获取实际值。 |
| [`actual_minor_unit_scale`](/slides/python-net/zh/aspose.slides.charts/axis/actual_minor_unit_scale/) | 指定轴的实际次单位比例。请先调用 IChart.ValidateChartLayout() 方法以获取实际值。 |
| [`is_automatic_max_value`](/slides/python-net/zh/aspose.slides.charts/axis/is_automatic_max_value/) | 指示是否自动分配最大值。<br/>             可读写 **bool**. |
| [`max_value`](/slides/python-net/zh/aspose.slides.charts/axis/max_value/) | 表示值轴上的最大值。<br/>             可读写 **float**. |
| [`minor_unit`](/slides/python-net/zh/aspose.slides.charts/axis/minor_unit/) | 表示日期或数值轴的次单位。<br/>             可读写 **float**. |
| [`is_automatic_minor_unit`](/slides/python-net/zh/aspose.slides.charts/axis/is_automatic_minor_unit/) | 指示轴的次单位是否自动分配。<br/>             可读写 **bool**. |
| [`major_unit`](/slides/python-net/zh/aspose.slides.charts/axis/major_unit/) | 表示日期或数值轴的主单位。<br/>             可读写 **float**. |
| [`is_automatic_major_unit`](/slides/python-net/zh/aspose.slides.charts/axis/is_automatic_major_unit/) | 指示轴的主单位是否自动分配。 <br/>            可读写 **bool**. |
| [`is_automatic_min_value`](/slides/python-net/zh/aspose.slides.charts/axis/is_automatic_min_value/) | 指示是否自动分配最小值。<br/>             可读写 **bool**. |
| [`min_value`](/slides/python-net/zh/aspose.slides.charts/axis/min_value/) | 表示值轴上的最小值。<br/>             可读写 **float**. |
| [`is_logarithmic`](/slides/python-net/zh/aspose.slides.charts/axis/is_logarithmic/) | 表示值轴的刻度类型是否为对数。<br/>             可读写 **bool**. |
| [`log_base`](/slides/python-net/zh/aspose.slides.charts/axis/log_base/) | 表示对数基数。默认值为 10。<br/>             可读写 **float**. |
| [`is_plot_order_reversed`](/slides/python-net/zh/aspose.slides.charts/axis/is_plot_order_reversed/) | 表示 MS PowerPoint 是否从最后到第一个绘制数据点。<br/>             可读写 **bool**. |
| [`is_visible`](/slides/python-net/zh/aspose.slides.charts/axis/is_visible/) | 表示轴是否可见。<br/>             可读写 **bool**. |
| [`major_tick_mark`](/slides/python-net/zh/aspose.slides.charts/axis/major_tick_mark/) | 表示指定轴的主刻度线类型。<br/>             可读写 [`TickMarkType`](/slides/python-net/zh/aspose.slides.charts/tickmarktype). |
| [`minor_tick_mark`](/slides/python-net/zh/aspose.slides.charts/axis/minor_tick_mark/) | 表示指定轴的次刻度线类型。<br/>             可读写 [`TickMarkType`](/slides/python-net/zh/aspose.slides.charts/tickmarktype). |
| [`tick_label_position`](/slides/python-net/zh/aspose.slides.charts/axis/tick_label_position/) | 表示指定轴上刻度标签的位置。<br/>             可读写 [`TickLabelPositionType`](/slides/python-net/zh/aspose.slides.charts/ticklabelpositiontype). |
| [`major_unit_scale`](/slides/python-net/zh/aspose.slides.charts/axis/major_unit_scale/) | 表示日期轴的主单位比例。<br/>             可读写 [`TimeUnitType`](/slides/python-net/zh/aspose.slides.charts/timeunittype). |
| [`minor_unit_scale`](/slides/python-net/zh/aspose.slides.charts/axis/minor_unit_scale/) | 表示日期轴的主单位比例。<br/>             可读写 [`TimeUnitType`](/slides/python-net/zh/aspose.slides.charts/timeunittype). |
| [`base_unit_scale`](/slides/python-net/zh/aspose.slides.charts/axis/base_unit_scale/) | 指定日期轴上表示的最小时间单位。<br/>            可读写 [`TimeUnitType`](/slides/python-net/zh/aspose.slides.charts/timeunittype). |
| [`minor_grid_lines_format`](/slides/python-net/zh/aspose.slides.charts/axis/minor_grid_lines_format/) | 表示图表轴上的次网格线格式。<br/>             只读 [`IChartLinesFormat`](/slides/python-net/zh/aspose.slides.charts/ichartlinesformat). |
| [`major_grid_lines_format`](/slides/python-net/zh/aspose.slides.charts/axis/major_grid_lines_format/) | 表示图表轴上的主网格线格式。<br/>             只读 [`IChartLinesFormat`](/slides/python-net/zh/aspose.slides.charts/ichartlinesformat). |
| [`show_minor_grid_lines`](/slides/python-net/zh/aspose.slides.charts/axis/show_minor_grid_lines/) | 要隐藏次网格线，请将 MinorGridLinesFormat.Line.FillFormat.FillType 设置为 FillType.NoFill。<br/>            只读 **bool**. |
| [`show_major_grid_lines`](/slides/python-net/zh/aspose.slides.charts/axis/show_major_grid_lines/) | 要隐藏主网格线，请将 MajorGridLinesFormat.Line.FillFormat.FillType 设置为 FillType.NoFill。<br/>            只读 **bool**. |
| [`format`](/slides/python-net/zh/aspose.slides.charts/axis/format/) | 表示轴的格式。<br/>             只读 [`IAxisFormat`](/slides/python-net/zh/aspose.slides.charts/iaxisformat). |
| [`text_format`](/slides/python-net/zh/aspose.slides.charts/axis/text_format/) | 表示文本的格式。<br/>             只读 [`IChartTextFormat`](/slides/python-net/zh/aspose.slides.charts/icharttextformat). |
| [`title`](/slides/python-net/zh/aspose.slides.charts/axis/title/) | 获取轴的标题。<br/>             只读 [`IChartTitle`](/slides/python-net/zh/aspose.slides.charts/icharttitle). |
| [`cross_type`](/slides/python-net/zh/aspose.slides.charts/axis/cross_type/) | 表示在指定轴上另一轴交叉的 CrossType。<br/>             可读写 [`CrossesType`](/slides/python-net/zh/aspose.slides.charts/crossestype). |
| [`position`](/slides/python-net/zh/aspose.slides.charts/axis/position/) | 表示轴的位置。<br/>             可读写 [`AxisPositionType`](/slides/python-net/zh/aspose.slides.charts/axispositiontype). |
| [`has_title`](/slides/python-net/zh/aspose.slides.charts/axis/has_title/) | 确定轴是否具有可见标题。<br/>            可读写 **bool**. |
| [`number_format`](/slides/python-net/zh/aspose.slides.charts/axis/number_format/) | 表示轴标签的格式字符串。<br/>            可读写 **str**. |
| [`is_number_format_linked_to_source`](/slides/python-net/zh/aspose.slides.charts/axis/is_number_format_linked_to_source/) | 指示格式是否链接到源数据。<br/>            可读写 **bool**. |
| [`tick_label_rotation_angle`](/slides/python-net/zh/aspose.slides.charts/axis/tick_label_rotation_angle/) | 表示刻度标签的旋转角度。<br/>            可读写 **float**. |
| [`tick_label_spacing`](/slides/python-net/zh/aspose.slides.charts/axis/tick_label_spacing/) | 指定在绘制的标签之间要跳过的刻度标签数量。适用于类别或系列轴。<br/>            可读写 **int**. |
| [`is_automatic_tick_label_spacing`](/slides/python-net/zh/aspose.slides.charts/axis/is_automatic_tick_label_spacing/) | 指定自动刻度标签间距值。若为 false：使用 TickLabelSpacing 属性。<br/>            可读写 **bool**. |
| [`tick_marks_spacing`](/slides/python-net/zh/aspose.slides.charts/axis/tick_marks_spacing/) | 指定在绘制下一个刻度标记前应跳过的刻度标记数量。<br/>            适用于类别或系列轴。<br/>            可读写 **int**. |
| [`is_automatic_tick_marks_spacing`](/slides/python-net/zh/aspose.slides.charts/axis/is_automatic_tick_marks_spacing/) | 指定自动刻度标记间距值。若为 false：使用 TickMarksSpacing 属性。<br/>            可读写 **bool**. |
| [`label_offset`](/slides/python-net/zh/aspose.slides.charts/axis/label_offset/) | 指定标签距轴的距离。适用于类别或日期轴。值必须在 0% 到 1000% 之间。<br/>            可读写 **int**. |
| [`aggregation_type`](/slides/python-net/zh/aspose.slides.charts/axis/aggregation_type/) | 表示类别轴的聚合类型（分箱）。适用于类别。仅在直方图或 HistogramPareto 系列中使用。 |
| [`bin_width`](/slides/python-net/zh/aspose.slides.charts/axis/bin_width/) | 当 AggregationType 属性值设为 AxisAggregationType.ByBinWidth 时，指定分箱宽度。<br/>            适用于类别轴。仅在直方图或 HistogramPareto 系列中使用。 |
| [`number_of_bins`](/slides/python-net/zh/aspose.slides.charts/axis/number_of_bins/) | 当 AggregationType 属性值设为 AxisAggregationType.ByNumberOfBins 时，指定分箱数量。<br/>            适用于类别轴。仅在直方图或 HistogramPareto 系列中使用。 |
| [`is_overflow_bin`](/slides/python-net/zh/aspose.slides.charts/axis/is_overflow_bin/) | 指定是否使用溢出分箱。使用 IsAutomaticOverflowBin 和 OverflowBin 来调整溢出分箱值。 |
| [`is_automatic_overflow_bin`](/slides/python-net/zh/aspose.slides.charts/axis/is_automatic_overflow_bin/) | 指定自动溢出分箱值。若为 false：使用 OverflowBin 属性。 |
| [`overflow_bin`](/slides/python-net/zh/aspose.slides.charts/axis/overflow_bin/) | 指定溢出分箱的自定义值。适用于 IsAutomaticOverflowBin 属性设为 false 且 IsOverflowBin 属性为 true 的情况。 |
| [`is_underflow_bin`](/slides/python-net/zh/aspose.slides.charts/axis/is_underflow_bin/) | 指定是否使用下限分箱。使用 IsAutomaticUnderflowBin 和 UnderflowBin 来调整下限分箱值。 |
| [`is_automatic_underflow_bin`](/slides/python-net/zh/aspose.slides.charts/axis/is_automatic_underflow_bin/) | 指定自动下限分箱值。若为 false：使用 UnderflowBin 属性。 |
| [`underflow_bin`](/slides/python-net/zh/aspose.slides.charts/axis/underflow_bin/) | 指定下限分箱的自定义值。适用于 IsAutomaticUnderflowBin 属性设为 false 且 IsUnderflowBin 属性为 true 的情况。 |
| [`slide`](/slides/python-net/zh/aspose.slides.charts/axis/slide/) |  |
| [`presentation`](/slides/python-net/zh/aspose.slides.charts/axis/presentation/) |  |

## 方法

| Method | Description |
| :- | :- |
| [`set_category_axis_type_automatically(self)`](/slides/python-net/zh/aspose.slides.charts/axis/set_category_axis_type_automatically/#) | 根据轴数据自动确定值并设置 IAxis.CategoryAxisType 属性。 |

### 另见
* 模块 [`aspose.slides.charts`](/slides/python-net/zh/aspose.slides.charts)
* 库 [`Aspose.Slides`](/slides/python-net)