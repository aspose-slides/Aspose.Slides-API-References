---
title: IAxis class
second_title: Aspose.Slides for Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides.charts/iaxis/
---
## IAxis 類別

Encapsulates the object that represents a chart's axis.

The IAxis type exposes the following members:

## 屬性

| Property | Description |
| :- | :- |
| [`axis_between_categories`](/slides/python-net/zh-hant/aspose.slides.charts/iaxis/axis_between_categories/) | 表示數值軸是否在類別之間穿過類別軸。<br/>            此屬性僅適用於類別軸，且不適用於 3-D 圖表。<br/>            讀寫 **bool**. |
| [`cross_at`](/slides/python-net/zh-hant/aspose.slides.charts/iaxis/cross_at/) | 表示軸上垂直軸相交的點。<br/>            讀寫 **float**. |
| [`display_unit`](/slides/python-net/zh-hant/aspose.slides.charts/iaxis/display_unit/) | 指定數值軸顯示單位的縮放值。<br/>            讀寫 [`DisplayUnitType`](/slides/python-net/zh-hant/aspose.slides.charts/displayunittype). |
| [`actual_max_value`](/slides/python-net/zh-hant/aspose.slides.charts/iaxis/actual_max_value/) | 指定軸上的實際最大值。請先呼叫方法 IChart.ValidateChartLayout() 以獲取實際值。 |
| [`actual_min_value`](/slides/python-net/zh-hant/aspose.slides.charts/iaxis/actual_min_value/) | 指定軸上的實際最小值。請先呼叫方法 IChart.ValidateChartLayout() 以獲取實際值。 |
| [`actual_major_unit`](/slides/python-net/zh-hant/aspose.slides.charts/iaxis/actual_major_unit/) | 指定軸的實際主單位。請先呼叫方法 IChart.ValidateChartLayout() 以獲取實際值。 |
| [`actual_minor_unit`](/slides/python-net/zh-hant/aspose.slides.charts/iaxis/actual_minor_unit/) | 指定軸的實際次單位。請先呼叫方法 IChart.ValidateChartLayout() 以獲取實際值。 |
| [`actual_major_unit_scale`](/slides/python-net/zh-hant/aspose.slides.charts/iaxis/actual_major_unit_scale/) | 指定軸的實際主單位比例。請先呼叫方法 IChart.ValidateChartLayout() 以獲取實際值。 |
| [`actual_minor_unit_scale`](/slides/python-net/zh-hant/aspose.slides.charts/iaxis/actual_minor_unit_scale/) | 指定軸的實際次單位比例。請先呼叫方法 IChart.ValidateChartLayout() 以獲取實際值。 |
| [`is_automatic_max_value`](/slides/python-net/zh-hant/aspose.slides.charts/iaxis/is_automatic_max_value/) | 指示是否自動指定最大值。<br/>             讀寫 **bool**. |
| [`max_value`](/slides/python-net/zh-hant/aspose.slides.charts/iaxis/max_value/) | 表示數值軸上的最大值。<br/>             讀寫 **float**. |
| [`minor_unit`](/slides/python-net/zh-hant/aspose.slides.charts/iaxis/minor_unit/) | 表示日期或數值軸的次單位。<br/>             讀寫 **float**. |
| [`is_automatic_minor_unit`](/slides/python-net/zh-hant/aspose.slides.charts/iaxis/is_automatic_minor_unit/) | 指示是否自動指定軸的次單位。<br/>             讀寫 **bool**. |
| [`major_unit`](/slides/python-net/zh-hant/aspose.slides.charts/iaxis/major_unit/) | 表示日期或數值軸的主單位。<br/>             讀寫 **float**. |
| [`is_automatic_major_unit`](/slides/python-net/zh-hant/aspose.slides.charts/iaxis/is_automatic_major_unit/) | 指示是否自動指定軸的主單位。<br/>            讀寫 **bool**. |
| [`is_automatic_min_value`](/slides/python-net/zh-hant/aspose.slides.charts/iaxis/is_automatic_min_value/) | 指示是否自動指定最小值。<br/>             讀寫 **bool**. |
| [`min_value`](/slides/python-net/zh-hant/aspose.slides.charts/iaxis/min_value/) | 表示數值軸上的最小值。<br/>             讀寫 **float**. |
| [`is_logarithmic`](/slides/python-net/zh-hant/aspose.slides.charts/iaxis/is_logarithmic/) | 表示數值軸的比例類型是否為對數。<br/>             讀寫 **bool**. |
| [`log_base`](/slides/python-net/zh-hant/aspose.slides.charts/iaxis/log_base/) | 表示對數基底。預設值為 10。<br/>             讀寫 **float**. |
| [`is_plot_order_reversed`](/slides/python-net/zh-hant/aspose.slides.charts/iaxis/is_plot_order_reversed/) | 表示 Microsoft PowerPoint 是否從最後到第一個繪製資料點。<br/>             讀寫 **bool**. |
| [`is_visible`](/slides/python-net/zh-hant/aspose.slides.charts/iaxis/is_visible/) | 表示軸是否可見。<br/>             讀寫 **bool**. |
| [`major_tick_mark`](/slides/python-net/zh-hant/aspose.slides.charts/iaxis/major_tick_mark/) | 表示指定軸的主刻度線類型。<br/>             讀寫 [`TickMarkType`](/slides/python-net/zh-hant/aspose.slides.charts/tickmarktype). |
| [`minor_tick_mark`](/slides/python-net/zh-hant/aspose.slides.charts/iaxis/minor_tick_mark/) | 表示指定軸的次刻度線類型。<br/>             讀寫 [`TickMarkType`](/slides/python-net/zh-hant/aspose.slides.charts/tickmarktype). |
| [`tick_label_position`](/slides/python-net/zh-hant/aspose.slides.charts/iaxis/tick_label_position/) | 表示指定軸上刻度標籤的位置。<br/>             讀寫 [`TickLabelPositionType`](/slides/python-net/zh-hant/aspose.slides.charts/ticklabelpositiontype). |
| [`major_unit_scale`](/slides/python-net/zh-hant/aspose.slides.charts/iaxis/major_unit_scale/) | 表示日期軸的主單位比例。<br/>             讀寫 [`TimeUnitType`](/slides/python-net/zh-hant/aspose.slides.charts/timeunittype). |
| [`minor_unit_scale`](/slides/python-net/zh-hant/aspose.slides.charts/iaxis/minor_unit_scale/) | 表示日期軸的主單位比例。<br/>             讀寫 [`TimeUnitType`](/slides/python-net/zh-hant/aspose.slides.charts/timeunittype). |
| [`base_unit_scale`](/slides/python-net/zh-hant/aspose.slides.charts/iaxis/base_unit_scale/) | 指定日期軸上所表示的最小時間單位。<br/>            讀寫 [`TimeUnitType`](/slides/python-net/zh-hant/aspose.slides.charts/timeunittype). |
| [`minor_grid_lines_format`](/slides/python-net/zh-hant/aspose.slides.charts/iaxis/minor_grid_lines_format/) | 表示圖表軸的次格線格式。<br/>             唯讀 [`IChartLinesFormat`](/slides/python-net/zh-hant/aspose.slides.charts/ichartlinesformat). |
| [`major_grid_lines_format`](/slides/python-net/zh-hant/aspose.slides.charts/iaxis/major_grid_lines_format/) | 表示圖表軸的主格線格式。<br/>             唯讀 [`IChartLinesFormat`](/slides/python-net/zh-hant/aspose.slides.charts/ichartlinesformat). |
| [`show_minor_grid_lines`](/slides/python-net/zh-hant/aspose.slides.charts/iaxis/show_minor_grid_lines/) | 表示是否顯示次格線。<br/>             唯讀 **bool**. |
| [`show_major_grid_lines`](/slides/python-net/zh-hant/aspose.slides.charts/iaxis/show_major_grid_lines/) | 表示是否顯示主格線。<br/>             唯讀 **bool**. |
| [`format`](/slides/python-net/zh-hant/aspose.slides.charts/iaxis/format/) | 表示軸的格式。<br/>             唯讀 [`IAxisFormat`](/slides/python-net/zh-hant/aspose.slides.charts/iaxisformat). |
| [`title`](/slides/python-net/zh-hant/aspose.slides.charts/iaxis/title/) | 取得軸的標題。<br/>             唯讀 [`IChartTitle`](/slides/python-net/zh-hant/aspose.slides.charts/icharttitle). |
| [`cross_type`](/slides/python-net/zh-hant/aspose.slides.charts/iaxis/cross_type/) | 表示指定軸上另一軸相交的 CrossType。<br/>             讀寫 [`CrossesType`](/slides/python-net/zh-hant/aspose.slides.charts/crossestype). |
| [`position`](/slides/python-net/zh-hant/aspose.slides.charts/iaxis/position/) | 表示軸的位置。<br/>             讀寫 [`AxisPositionType`](/slides/python-net/zh-hant/aspose.slides.charts/axispositiontype). |
| [`has_title`](/slides/python-net/zh-hant/aspose.slides.charts/iaxis/has_title/) | 判斷軸是否具有可見的標題。<br/>            讀寫 **bool**. |
| [`number_format`](/slides/python-net/zh-hant/aspose.slides.charts/iaxis/number_format/) | 表示軸標籤的格式字串。<br/>            讀寫 **str**. |
| [`is_number_format_linked_to_source`](/slides/python-net/zh-hant/aspose.slides.charts/iaxis/is_number_format_linked_to_source/) | 指示格式是否連結至來源資料。<br/>            讀寫 **bool**. |
| [`tick_label_rotation_angle`](/slides/python-net/zh-hant/aspose.slides.charts/iaxis/tick_label_rotation_angle/) | 表示刻度標籤的旋轉角度<br/>            讀寫 **float**. |
| [`tick_label_spacing`](/slides/python-net/zh-hant/aspose.slides.charts/iaxis/tick_label_spacing/) | 指定在繪製的標籤之間要跳過多少個刻度標籤。<br/>            讀寫 **int**. |
| [`is_automatic_tick_label_spacing`](/slides/python-net/zh-hant/aspose.slides.charts/iaxis/is_automatic_tick_label_spacing/) | 指定自動刻度標籤間距值。若為 false，請使用 TickLabelSpacing 屬性。<br/>            讀寫 **bool**. |
| [`tick_marks_spacing`](/slides/python-net/zh-hant/aspose.slides.charts/iaxis/tick_marks_spacing/) | 指定在繪製下一個刻度標記前應跳過多少個刻度標記。適用於類別軸或系列軸。<br/>            讀寫 **int**. |
| [`is_automatic_tick_marks_spacing`](/slides/python-net/zh-hant/aspose.slides.charts/iaxis/is_automatic_tick_marks_spacing/) | 指定自動刻度標記間距值。若為 false，請使用 TickMarksSpacing 屬性。<br/>            讀寫 **bool**. |
| [`label_offset`](/slides/python-net/zh-hant/aspose.slides.charts/iaxis/label_offset/) | 指定標籤與軸的距離。適用於類別軸或日期軸。值必須介於 0% 到 1000% 之間。<br/>            讀寫 **int**. |
| [`category_axis_type`](/slides/python-net/zh-hant/aspose.slides.charts/iaxis/category_axis_type/) | 指定類別軸的類型。<br/>            讀寫 [`IAxis.category_axis_type`](/slides/python-net/zh-hant/aspose.slides.charts/iaxis/category_axis_type). |
| [`aggregation_type`](/slides/python-net/zh-hant/aspose.slides.charts/iaxis/aggregation_type/) | 表示類別軸的彙總類型（分箱）。適用於類別。僅與 Histogram 或 HistogramPareto 系列一起使用。 |
| [`bin_width`](/slides/python-net/zh-hant/aspose.slides.charts/iaxis/bin_width/) | 當 AggregationType 屬性值設為 AxisAggregationType.ByBinWidth 時，指定分箱寬度。<br/>            適用於類別軸。僅與 Histogram 或 HistogramPareto 系列一起使用。 |
| [`number_of_bins`](/slides/python-net/zh-hant/aspose.slides.charts/iaxis/number_of_bins/) | 當 AggregationType 屬性值設為 AxisAggregationType.ByNumberOfBins 時，指定分箱數量。<br/>            適用於類別軸。僅與 Histogram 或 HistogramPareto 系列一起使用。 |
| [`is_overflow_bin`](/slides/python-net/zh-hant/aspose.slides.charts/iaxis/is_overflow_bin/) | 指定是否套用溢位分箱。使用 IsAutomaticOverflowBin 和 OverflowBin 調整溢位分箱值。 |
| [`is_automatic_overflow_bin`](/slides/python-net/zh-hant/aspose.slides.charts/iaxis/is_automatic_overflow_bin/) | 指定自動溢位分箱值。若為 false，請使用 OverflowBin 屬性。 |
| [`overflow_bin`](/slides/python-net/zh-hant/aspose.slides.charts/iaxis/overflow_bin/) | 指定溢位分箱的自訂值。當 IsAutomaticOverflowBin 屬性設為 false 且 IsOverflowBin 屬性為 true 時套用。 |
| [`is_underflow_bin`](/slides/python-net/zh-hant/aspose.slides.charts/iaxis/is_underflow_bin/) | 指定是否套用不足位分箱。使用 IsAutomaticUnderflowBin 和 UnderflowBin 調整不足位分箱值。 |
| [`is_automatic_underflow_bin`](/slides/python-net/zh-hant/aspose.slides.charts/iaxis/is_automatic_underflow_bin/) | 指定自動不足位分箱值。若為 false，請使用 UnderflowBin 屬性。 |
| [`underflow_bin`](/slides/python-net/zh-hant/aspose.slides.charts/iaxis/underflow_bin/) | 指定不足位分箱的自訂值。當 IsAutomaticUnderflowBin 屬性設為 false 且 IsUnderflowBin 屬性為 true 時套用。 |
| [`text_format`](/slides/python-net/zh-hant/aspose.slides.charts/iaxis/text_format/) |  |
| [`chart`](/slides/python-net/zh-hant/aspose.slides.charts/iaxis/chart/) |  |
| [`slide`](/slides/python-net/zh-hant/aspose.slides.charts/iaxis/slide/) |  |
| [`presentation`](/slides/python-net/zh-hant/aspose.slides.charts/iaxis/presentation/) |  |

## 方法

| Method | Description |
| :- | :- |
| [`set_category_axis_type_automatically(self)`](/slides/python-net/zh-hant/aspose.slides.charts/iaxis/set_category_axis_type_automatically/#) | 根據軸資料自動決定的值，設定 IAxis.CategoryAxisType 屬性。 |

### 另見
* 模組 [`aspose.slides.charts`](/slides/python-net/zh-hant/aspose.slides.charts)
* 程式庫 [`Aspose.Slides`](/slides/python-net)