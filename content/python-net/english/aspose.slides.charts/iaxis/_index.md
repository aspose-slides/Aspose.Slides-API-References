---
title: IAxis
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides.charts/iaxis/
---


IAxis class

Encapsulates the object that represents a chart's axis.

The IAxis type exposes the following members:

## Properties

| Property | Description |
| :- | :- |
| [axis_between_categories](/slides/python-net/aspose.slides.charts/iaxis/axis_between_categories/) | Represents if the value axis crosses the category axis between categories.<br/>            This property applies only to category axes, and it doesn't apply to 3-D charts.<br/>            Read/write .NET type System.Boolean. |
| [cross_at](/slides/python-net/aspose.slides.charts/iaxis/cross_at/) | Represents the point on the axis where the perpendicular axis crosses it.<br/>            Read/write .NET type System.Single. |
| [display_unit](/slides/python-net/aspose.slides.charts/iaxis/display_unit/) | Specifies the scaling value of the display units for the value axis.<br/>            Read/write [`DisplayUnitType`](/slides/python-net/aspose.slides.charts/displayunittype). |
| [actual_max_value](/slides/python-net/aspose.slides.charts/iaxis/actual_max_value/) | Specifies actual maximum value on the axis. Call method IChart.ValidateChartLayout() previously to get actual value. |
| [actual_min_value](/slides/python-net/aspose.slides.charts/iaxis/actual_min_value/) | Specifies actual minimum value on the axis. Call method IChart.ValidateChartLayout() previously to get actual value. |
| [actual_major_unit](/slides/python-net/aspose.slides.charts/iaxis/actual_major_unit/) | Specifies actual major unit of the axis. Call method IChart.ValidateChartLayout() previously to get actual value. |
| [actual_minor_unit](/slides/python-net/aspose.slides.charts/iaxis/actual_minor_unit/) | Specifies actual minor unit of the axis. Call method IChart.ValidateChartLayout() previously to get actual value. |
| [actual_major_unit_scale](/slides/python-net/aspose.slides.charts/iaxis/actual_major_unit_scale/) | Specifies actual major unit scale of the axis. Call method IChart.ValidateChartLayout() previously to get actual value. |
| [actual_minor_unit_scale](/slides/python-net/aspose.slides.charts/iaxis/actual_minor_unit_scale/) | Specifies actual minor unit scale of the axis. Call method IChart.ValidateChartLayout() previously to get actual value. |
| [is_automatic_max_value](/slides/python-net/aspose.slides.charts/iaxis/is_automatic_max_value/) | Indicates whether the max value is automatically assigned.<br/>             Read/write .NET type System.Boolean. |
| [max_value](/slides/python-net/aspose.slides.charts/iaxis/max_value/) | Represents the maximum value on the value axis.<br/>             Read/write .NET type System.Double. |
| [minor_unit](/slides/python-net/aspose.slides.charts/iaxis/minor_unit/) | Represents the minor units for the date or value axis.<br/>             Read/write .NET type System.Double. |
| [is_automatic_minor_unit](/slides/python-net/aspose.slides.charts/iaxis/is_automatic_minor_unit/) | Indicates whether the minor unit of the axis is automatically assigned.<br/>             Read/write .NET type System.Boolean. |
| [major_unit](/slides/python-net/aspose.slides.charts/iaxis/major_unit/) | Represents the major units for the date or value axis.<br/>             Read/write .NET type System.Double. |
| [is_automatic_major_unit](/slides/python-net/aspose.slides.charts/iaxis/is_automatic_major_unit/) | Indicates whether the major unit of the axis is automatically assigned.<br/>            Read/write .NET type System.Boolean. |
| [is_automatic_min_value](/slides/python-net/aspose.slides.charts/iaxis/is_automatic_min_value/) | Indicates whether the min value is automatically assigned.<br/>             Read/write .NET type System.Boolean. |
| [min_value](/slides/python-net/aspose.slides.charts/iaxis/min_value/) | Represents the minimum value on the value axis.<br/>             Read/write .NET type System.Double. |
| [is_logarithmic](/slides/python-net/aspose.slides.charts/iaxis/is_logarithmic/) | Represents if the value axis scale type is logarithmic or not.<br/>             Read/write .NET type System.Boolean. |
| [log_base](/slides/python-net/aspose.slides.charts/iaxis/log_base/) | Represents the logarithmic base. Default value is 10.<br/>             Read/write .NET type System.Double. |
| [is_plot_order_reversed](/slides/python-net/aspose.slides.charts/iaxis/is_plot_order_reversed/) | Represents if MS PowerPoint plots data points from last to first.<br/>             Read/write .NET type System.Boolean. |
| [is_visible](/slides/python-net/aspose.slides.charts/iaxis/is_visible/) | Represents if the axis is visible.<br/>             Read/write .NET type System.Boolean. |
| [major_tick_mark](/slides/python-net/aspose.slides.charts/iaxis/major_tick_mark/) | Represents the type of major tick mark for the specified axis.<br/>             Read/write [`TickMarkType`](/slides/python-net/aspose.slides.charts/tickmarktype). |
| [minor_tick_mark](/slides/python-net/aspose.slides.charts/iaxis/minor_tick_mark/) | Represents the type of minor tick mark for the specified axis.<br/>             Read/write [`TickMarkType`](/slides/python-net/aspose.slides.charts/tickmarktype). |
| [tick_label_position](/slides/python-net/aspose.slides.charts/iaxis/tick_label_position/) | Represents the position of tick-mark labels on the specified axis.<br/>             Read/write [`TickLabelPositionType`](/slides/python-net/aspose.slides.charts/ticklabelpositiontype). |
| [major_unit_scale](/slides/python-net/aspose.slides.charts/iaxis/major_unit_scale/) | Represents the major unit scale for the date axis.<br/>             Read/write [`TimeUnitType`](/slides/python-net/aspose.slides.charts/timeunittype). |
| [minor_unit_scale](/slides/python-net/aspose.slides.charts/iaxis/minor_unit_scale/) | Represents the major unit scale for the date axis.<br/>             Read/write [`TimeUnitType`](/slides/python-net/aspose.slides.charts/timeunittype). |
| [base_unit_scale](/slides/python-net/aspose.slides.charts/iaxis/base_unit_scale/) | Specifies the smallest time unit that is represented on the date axis.<br/>            Read/write [`TimeUnitType`](/slides/python-net/aspose.slides.charts/timeunittype). |
| [minor_grid_lines_format](/slides/python-net/aspose.slides.charts/iaxis/minor_grid_lines_format/) | Represents minor gridlines format on a chart axis.<br/>             Read-only [`IChartLinesFormat`](/slides/python-net/aspose.slides.charts/ichartlinesformat). |
| [major_grid_lines_format](/slides/python-net/aspose.slides.charts/iaxis/major_grid_lines_format/) | Represents major gridlines format on a chart axis.<br/>             Read-only [`IChartLinesFormat`](/slides/python-net/aspose.slides.charts/ichartlinesformat). |
| [show_minor_grid_lines](/slides/python-net/aspose.slides.charts/iaxis/show_minor_grid_lines/) | Represents if the minor gridlines showed.<br/>             Read-only .NET type System.Boolean. |
| [show_major_grid_lines](/slides/python-net/aspose.slides.charts/iaxis/show_major_grid_lines/) | Represents if the major gridlines showed.<br/>             Read-only .NET type System.Boolean. |
| [format](/slides/python-net/aspose.slides.charts/iaxis/format/) | Represents format of axis.<br/>             Read-only [`IAxisFormat`](/slides/python-net/aspose.slides.charts/iaxisformat). |
| [title](/slides/python-net/aspose.slides.charts/iaxis/title/) | Gets the axis' title.<br/>             Read-only [`IChartTitle`](/slides/python-net/aspose.slides.charts/icharttitle). |
| [cross_type](/slides/python-net/aspose.slides.charts/iaxis/cross_type/) | Represents the CrossType on the specified axis where the other axis crosses.<br/>             Read/write [`CrossesType`](/slides/python-net/aspose.slides.charts/crossestype). |
| [position](/slides/python-net/aspose.slides.charts/iaxis/position/) | Represents position of axis.<br/>             Read/write [`AxisPositionType`](/slides/python-net/aspose.slides.charts/axispositiontype). |
| [has_title](/slides/python-net/aspose.slides.charts/iaxis/has_title/) | Determines whether a axis has a visible title.<br/>            Read/write .NET type System.Boolean. |
| [number_format](/slides/python-net/aspose.slides.charts/iaxis/number_format/) | Represents the format string for the Axis Labels.<br/>            Read/write .NET type System.String. |
| [is_number_format_linked_to_source](/slides/python-net/aspose.slides.charts/iaxis/is_number_format_linked_to_source/) | Indicates whether the format is linked source data.<br/>            Read/write .NET type System.Boolean. |
| [tick_label_rotation_angle](/slides/python-net/aspose.slides.charts/iaxis/tick_label_rotation_angle/) | Represents the rotation angle of tick labels<br/>            Read/write .NET type System.Single. |
| [tick_label_spacing](/slides/python-net/aspose.slides.charts/iaxis/tick_label_spacing/) | Specifies how many tick labels to skip between label that is drawn.<br/>            Read/write .NET type System.UInt32. |
| [is_automatic_tick_label_spacing](/slides/python-net/aspose.slides.charts/iaxis/is_automatic_tick_label_spacing/) | Specifies automatic tick label spacing value. If false: use TickLabelSpacing property.<br/>            Read/write .NET type System.Boolean. |
| [tick_marks_spacing](/slides/python-net/aspose.slides.charts/iaxis/tick_marks_spacing/) | Specifies how many tick marks shall be skipped before the next one shall be <br/>            drawn. Applied to category or series axis.<br/>            Read/write .NET type System.UInt16. |
| [is_automatic_tick_marks_spacing](/slides/python-net/aspose.slides.charts/iaxis/is_automatic_tick_marks_spacing/) | Specifies automatic tick marks spacing value. If false: use TickMarksSpacing property.<br/>            Read/write .NET type System.Boolean. |
| [label_offset](/slides/python-net/aspose.slides.charts/iaxis/label_offset/) | Specifies the distance of labels from the axis. Applied to category or date axis. Value must be between 0% and 1000%.<br/>            Read/write .NET type System.UInt16. |
| [category_axis_type](/slides/python-net/aspose.slides.charts/iaxis/category_axis_type/) | Specifies the type of the category axis.<br/>            Read/write [`IAxis.category_axis_type`](/slides/python-net/aspose.slides.charts/iaxis#category_axis_type). |
| [aggregation_type](/slides/python-net/aspose.slides.charts/iaxis/aggregation_type/) | Represents aggregation type of category axis (binning). Applied to category. Used with Histogram or HistogramPareto series only. |
| [bin_width](/slides/python-net/aspose.slides.charts/iaxis/bin_width/) | Specifies bin width when AggregationType property value setted to AxisAggregationType.ByBinWidth. <br/>            Applied to category axes. Used with Histogram or HistogramPareto series only. |
| [number_of_bins](/slides/python-net/aspose.slides.charts/iaxis/number_of_bins/) | Specifies number of bins when AggregationType property value setted to AxisAggregationType.ByNumberOfBins. <br/>            Applied to category axes. Used with Histogram or HistogramPareto series only. |
| [is_overflow_bin](/slides/python-net/aspose.slides.charts/iaxis/is_overflow_bin/) | Specifies if overflow bin applied. Use IsAutomaticOverflowBin and OverflowBin to adjust overflow bin value. |
| [is_automatic_overflow_bin](/slides/python-net/aspose.slides.charts/iaxis/is_automatic_overflow_bin/) | Specifies automatic overflow bin value. If false: use OverflowBin property. |
| [overflow_bin](/slides/python-net/aspose.slides.charts/iaxis/overflow_bin/) | Specifies overflow bin custom value. Applied when IsAutomaticOverflowBin property setted to false and IsOverflowBin property equals true. |
| [is_underflow_bin](/slides/python-net/aspose.slides.charts/iaxis/is_underflow_bin/) | Specifies if underflow bin applied. Use IsAutomaticUnderflowBin and UnderflowBin to adjust underflow bin value. |
| [is_automatic_underflow_bin](/slides/python-net/aspose.slides.charts/iaxis/is_automatic_underflow_bin/) | Specifies automatic underflow bin value. If false: use UnderflowBin property. |
| [underflow_bin](/slides/python-net/aspose.slides.charts/iaxis/underflow_bin/) | Specifies underflow bin custom value. Applied when IsAutomaticUnderflowBin property setted to false and IsUnderflowBin property equals true. |
| [as_i_formatted_text_container](/slides/python-net/aspose.slides.charts/iaxis/as_i_formatted_text_container/) | Allows to get base IFormattedTextContainer interface.<br/>            Read-only [`IFormattedTextContainer`](/slides/python-net/aspose.slides.charts/iformattedtextcontainer). |
| [text_format](/slides/python-net/aspose.slides.charts/iaxis/text_format/) |  |
| [as_i_chart_component](/slides/python-net/aspose.slides.charts/iaxis/as_i_chart_component/) |  |
| [chart](/slides/python-net/aspose.slides.charts/iaxis/chart/) |  |
| [as_i_slide_component](/slides/python-net/aspose.slides.charts/iaxis/as_i_slide_component/) |  |
| [slide](/slides/python-net/aspose.slides.charts/iaxis/slide/) |  |
| [as_i_presentation_component](/slides/python-net/aspose.slides.charts/iaxis/as_i_presentation_component/) |  |
| [presentation](/slides/python-net/aspose.slides.charts/iaxis/presentation/) |  |

## Methods

| Method | Description |
| :- | :- |
| [set_category_axis_type_automatically](/slides/python-net/aspose.slides.charts/iaxis/set_category_axis_type_automatically/#) | Sets IAxis.CategoryAxisType property with a value that is automatically determined based on axis data. |

