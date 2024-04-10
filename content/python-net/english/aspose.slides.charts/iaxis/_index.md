---
title: IAxis class
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides.charts/
---


## IAxis class

Encapsulates the object that represents a chart's axis.

The IAxis type exposes the following members:

## Properties

| Property | Description |
| :- | :- |
| [axis_between_categories](/slides/python-net/aspose.slides.charts/axis_between_categories) | Represents if the value axis crosses the category axis between categories.<br/>            This property applies only to category axes, and it doesn't apply to 3-D charts.<br/>            Read/write :py:class:`bool`. |
| [cross_at](/slides/python-net/aspose.slides.charts/cross_at) | Represents the point on the axis where the perpendicular axis crosses it.<br/>            Read/write :py:class:`float`. |
| [display_unit](/slides/python-net/aspose.slides.charts/display_unit) | Specifies the scaling value of the display units for the value axis.<br/>            Read/write :py:enum:`aspose.slides.charts.DisplayUnitType`. |
| [actual_max_value](/slides/python-net/aspose.slides.charts/actual_max_value) | Specifies actual maximum value on the axis. Call method IChart.ValidateChartLayout() previously to get actual value. |
| [actual_min_value](/slides/python-net/aspose.slides.charts/actual_min_value) | Specifies actual minimum value on the axis. Call method IChart.ValidateChartLayout() previously to get actual value. |
| [actual_major_unit](/slides/python-net/aspose.slides.charts/actual_major_unit) | Specifies actual major unit of the axis. Call method IChart.ValidateChartLayout() previously to get actual value. |
| [actual_minor_unit](/slides/python-net/aspose.slides.charts/actual_minor_unit) | Specifies actual minor unit of the axis. Call method IChart.ValidateChartLayout() previously to get actual value. |
| [actual_major_unit_scale](/slides/python-net/aspose.slides.charts/actual_major_unit_scale) | Specifies actual major unit scale of the axis. Call method IChart.ValidateChartLayout() previously to get actual value. |
| [actual_minor_unit_scale](/slides/python-net/aspose.slides.charts/actual_minor_unit_scale) | Specifies actual minor unit scale of the axis. Call method IChart.ValidateChartLayout() previously to get actual value. |
| [is_automatic_max_value](/slides/python-net/aspose.slides.charts/is_automatic_max_value) | Indicates whether the max value is automatically assigned.<br/>             Read/write :py:class:`bool`. |
| [max_value](/slides/python-net/aspose.slides.charts/max_value) | Represents the maximum value on the value axis.<br/>             Read/write :py:class:`float`. |
| [minor_unit](/slides/python-net/aspose.slides.charts/minor_unit) | Represents the minor units for the date or value axis.<br/>             Read/write :py:class:`float`. |
| [is_automatic_minor_unit](/slides/python-net/aspose.slides.charts/is_automatic_minor_unit) | Indicates whether the minor unit of the axis is automatically assigned.<br/>             Read/write :py:class:`bool`. |
| [major_unit](/slides/python-net/aspose.slides.charts/major_unit) | Represents the major units for the date or value axis.<br/>             Read/write :py:class:`float`. |
| [is_automatic_major_unit](/slides/python-net/aspose.slides.charts/is_automatic_major_unit) | Indicates whether the major unit of the axis is automatically assigned.<br/>            Read/write :py:class:`bool`. |
| [is_automatic_min_value](/slides/python-net/aspose.slides.charts/is_automatic_min_value) | Indicates whether the min value is automatically assigned.<br/>             Read/write :py:class:`bool`. |
| [min_value](/slides/python-net/aspose.slides.charts/min_value) | Represents the minimum value on the value axis.<br/>             Read/write :py:class:`float`. |
| [is_logarithmic](/slides/python-net/aspose.slides.charts/is_logarithmic) | Represents if the value axis scale type is logarithmic or not.<br/>             Read/write :py:class:`bool`. |
| [log_base](/slides/python-net/aspose.slides.charts/log_base) | Represents the logarithmic base. Default value is 10.<br/>             Read/write :py:class:`float`. |
| [is_plot_order_reversed](/slides/python-net/aspose.slides.charts/is_plot_order_reversed) | Represents if MS PowerPoint plots data points from last to first.<br/>             Read/write :py:class:`bool`. |
| [is_visible](/slides/python-net/aspose.slides.charts/is_visible) | Represents if the axis is visible.<br/>             Read/write :py:class:`bool`. |
| [major_tick_mark](/slides/python-net/aspose.slides.charts/major_tick_mark) | Represents the type of major tick mark for the specified axis.<br/>             Read/write :py:enum:`aspose.slides.charts.TickMarkType`. |
| [minor_tick_mark](/slides/python-net/aspose.slides.charts/minor_tick_mark) | Represents the type of minor tick mark for the specified axis.<br/>             Read/write :py:enum:`aspose.slides.charts.TickMarkType`. |
| [tick_label_position](/slides/python-net/aspose.slides.charts/tick_label_position) | Represents the position of tick-mark labels on the specified axis.<br/>             Read/write :py:enum:`aspose.slides.charts.TickLabelPositionType`. |
| [major_unit_scale](/slides/python-net/aspose.slides.charts/major_unit_scale) | Represents the major unit scale for the date axis.<br/>             Read/write :py:enum:`aspose.slides.charts.TimeUnitType`. |
| [minor_unit_scale](/slides/python-net/aspose.slides.charts/minor_unit_scale) | Represents the major unit scale for the date axis.<br/>             Read/write :py:enum:`aspose.slides.charts.TimeUnitType`. |
| [base_unit_scale](/slides/python-net/aspose.slides.charts/base_unit_scale) | Specifies the smallest time unit that is represented on the date axis.<br/>            Read/write :py:enum:`aspose.slides.charts.TimeUnitType`. |
| [minor_grid_lines_format](/slides/python-net/aspose.slides.charts/minor_grid_lines_format) | Represents minor gridlines format on a chart axis.<br/>             Read-only :py:class:`aspose.slides.charts.IChartLinesFormat`. |
| [major_grid_lines_format](/slides/python-net/aspose.slides.charts/major_grid_lines_format) | Represents major gridlines format on a chart axis.<br/>             Read-only :py:class:`aspose.slides.charts.IChartLinesFormat`. |
| [show_minor_grid_lines](/slides/python-net/aspose.slides.charts/show_minor_grid_lines) | Represents if the minor gridlines showed.<br/>             Read-only :py:class:`bool`. |
| [show_major_grid_lines](/slides/python-net/aspose.slides.charts/show_major_grid_lines) | Represents if the major gridlines showed.<br/>             Read-only :py:class:`bool`. |
| [format](/slides/python-net/aspose.slides.charts/format) | Represents format of axis.<br/>             Read-only :py:class:`aspose.slides.charts.IAxisFormat`. |
| [title](/slides/python-net/aspose.slides.charts/title) | Gets the axis' title.<br/>             Read-only :py:class:`aspose.slides.charts.IChartTitle`. |
| [cross_type](/slides/python-net/aspose.slides.charts/cross_type) | Represents the CrossType on the specified axis where the other axis crosses.<br/>             Read/write :py:enum:`aspose.slides.charts.CrossesType`. |
| [position](/slides/python-net/aspose.slides.charts/position) | Represents position of axis.<br/>             Read/write :py:enum:`aspose.slides.charts.AxisPositionType`. |
| [has_title](/slides/python-net/aspose.slides.charts/has_title) | Determines whether a axis has a visible title.<br/>            Read/write :py:class:`bool`. |
| [number_format](/slides/python-net/aspose.slides.charts/number_format) | Represents the format string for the Axis Labels.<br/>            Read/write :py:class:`System.String`. |
| [is_number_format_linked_to_source](/slides/python-net/aspose.slides.charts/is_number_format_linked_to_source) | Indicates whether the format is linked source data.<br/>            Read/write :py:class:`bool`. |
| [tick_label_rotation_angle](/slides/python-net/aspose.slides.charts/tick_label_rotation_angle) | Represents the rotation angle of tick labels<br/>            Read/write :py:class:`float`. |
| [tick_label_spacing](/slides/python-net/aspose.slides.charts/tick_label_spacing) | Specifies how many tick labels to skip between label that is drawn.<br/>            Read/write :py:class:`int`. |
| [is_automatic_tick_label_spacing](/slides/python-net/aspose.slides.charts/is_automatic_tick_label_spacing) | Specifies automatic tick label spacing value. If false: use TickLabelSpacing property.<br/>            Read/write :py:class:`bool`. |
| [tick_marks_spacing](/slides/python-net/aspose.slides.charts/tick_marks_spacing) | Specifies how many tick marks shall be skipped before the next one shall be <br/>            drawn. Applied to category or series axis.<br/>            Read/write :py:class:`int`. |
| [is_automatic_tick_marks_spacing](/slides/python-net/aspose.slides.charts/is_automatic_tick_marks_spacing) | Specifies automatic tick marks spacing value. If false: use TickMarksSpacing property.<br/>            Read/write :py:class:`bool`. |
| [label_offset](/slides/python-net/aspose.slides.charts/label_offset) | Specifies the distance of labels from the axis. Applied to category or date axis. Value must be between 0% and 1000%.<br/>            Read/write :py:class:`int`. |
| [category_axis_type](/slides/python-net/aspose.slides.charts/category_axis_type) | Specifies the type of the category axis.<br/>            Read/write :py:attr:`aspose.slides.charts.IAxis.category_axis_type`. |
| [aggregation_type](/slides/python-net/aspose.slides.charts/aggregation_type) | Represents aggregation type of category axis (binning). Applied to category. Used with Histogram or HistogramPareto series only. |
| [bin_width](/slides/python-net/aspose.slides.charts/bin_width) | Specifies bin width when AggregationType property value setted to AxisAggregationType.ByBinWidth. <br/>            Applied to category axes. Used with Histogram or HistogramPareto series only. |
| [number_of_bins](/slides/python-net/aspose.slides.charts/number_of_bins) | Specifies number of bins when AggregationType property value setted to AxisAggregationType.ByNumberOfBins. <br/>            Applied to category axes. Used with Histogram or HistogramPareto series only. |
| [is_overflow_bin](/slides/python-net/aspose.slides.charts/is_overflow_bin) | Specifies if overflow bin applied. Use IsAutomaticOverflowBin and OverflowBin to adjust overflow bin value. |
| [is_automatic_overflow_bin](/slides/python-net/aspose.slides.charts/is_automatic_overflow_bin) | Specifies automatic overflow bin value. If false: use OverflowBin property. |
| [overflow_bin](/slides/python-net/aspose.slides.charts/overflow_bin) | Specifies overflow bin custom value. Applied when IsAutomaticOverflowBin property setted to false and IsOverflowBin property equals true. |
| [is_underflow_bin](/slides/python-net/aspose.slides.charts/is_underflow_bin) | Specifies if underflow bin applied. Use IsAutomaticUnderflowBin and UnderflowBin to adjust underflow bin value. |
| [is_automatic_underflow_bin](/slides/python-net/aspose.slides.charts/is_automatic_underflow_bin) | Specifies automatic underflow bin value. If false: use UnderflowBin property. |
| [underflow_bin](/slides/python-net/aspose.slides.charts/underflow_bin) | Specifies underflow bin custom value. Applied when IsAutomaticUnderflowBin property setted to false and IsUnderflowBin property equals true. |
| [as_i_formatted_text_container](/slides/python-net/aspose.slides.charts/as_i_formatted_text_container) | Allows to get base IFormattedTextContainer interface.<br/>            Read-only :py:class:`aspose.slides.charts.IFormattedTextContainer`. |
| [text_format](/slides/python-net/aspose.slides.charts/text_format) |  |
| [as_i_chart_component](/slides/python-net/aspose.slides.charts/as_i_chart_component) |  |
| [chart](/slides/python-net/aspose.slides.charts/chart) |  |
| [as_i_slide_component](/slides/python-net/aspose.slides.charts/as_i_slide_component) |  |
| [slide](/slides/python-net/aspose.slides.charts/slide) |  |
| [as_i_presentation_component](/slides/python-net/aspose.slides.charts/as_i_presentation_component) |  |
| [presentation](/slides/python-net/aspose.slides.charts/presentation) |  |

## Methods

| Method | Description |
| :- | :- |
| [__init__](/slides/python-net/aspose.slides.charts/iaxis/#) | Sets IAxis.CategoryAxisType property with a value that is automatically determined based on axis data. |

