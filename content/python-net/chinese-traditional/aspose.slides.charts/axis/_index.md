---
title: Axis class
second_title: Aspose.Slides for Python via .NET API 參考
description: 
type: docs
url: /zh-hant/aspose.slides.charts/axis/
---
## Axis 類

封裝表示圖表軸的物件。

Axis 類型公開以下成員：

## 屬性

| Property | Description |
| :- | :- |
| [`chart`](/slides/python-net/zh-hant/aspose.slides.charts/axis/chart/) | 傳回父圖表。<br/>            唯讀 [`IChart`](/slides/python-net/zh-hant/aspose.slides.charts/ichart)。 |
| [`axis_between_categories`](/slides/python-net/zh-hant/aspose.slides.charts/axis/axis_between_categories/) | 表示值軸是否在類別之間穿過類別軸。<br/>             此屬性僅適用於類別軸，且不適用於 3-D 圖表。<br/>             可讀寫 **bool**。 |
| [`category_axis_type`](/slides/python-net/zh-hant/aspose.slides.charts/axis/category_axis_type/) | 指定類別軸的類型。<br/>            可讀寫 [`CategoryAxisType`](/slides/python-net/zh-hant/aspose.slides.charts/categoryaxistype)。 |
| [`cross_at`](/slides/python-net/zh-hant/aspose.slides.charts/axis/cross_at/) | 表示垂直軸在此軸上交叉的點。<br/>             可讀寫 **float**。 |
| [`display_unit`](/slides/python-net/zh-hant/aspose.slides.charts/axis/display_unit/) | 指定值軸之顯示單位的縮放值。<br/>             可讀寫 [`DisplayUnitType`](/slides/python-net/zh-hant/aspose.slides.charts/displayunittype)。 |
| [`actual_max_value`](/slides/python-net/zh-hant/aspose.slides.charts/axis/actual_max_value/) | 指定軸上的實際最大值。請先呼叫方法 IChart.ValidateChartLayout() 以取得實際值。 |
| [`actual_min_value`](/slides/python-net/zh-hant/aspose.slides.charts/axis/actual_min_value/) | 指定軸上的實際最小值。請先呼叫方法 IChart.ValidateChartLayout() 以取得實際值。 |
| [`actual_major_unit`](/slides/python-net/zh-hant/aspose.slides.charts/axis/actual_major_unit/) | 指定軸的實際主要單位。請先呼叫方法 IChart.ValidateChartLayout() 以取得實際值。 |
| [`actual_minor_unit`](/slides/python-net/zh-hant/aspose.slides.charts/axis/actual_minor_unit/) | 指定軸的實際次要單位。請先呼叫方法 IChart.ValidateChartLayout() 以取得實際值。 |
| [`actual_major_unit_scale`](/slides/python-net/zh-hant/aspose.slides.charts/axis/actual_major_unit_scale/) | 指定軸的實際主要單位比例。請先呼叫方法 IChart.ValidateChartLayout() 以取得實際值。 |
| [`actual_minor_unit_scale`](/slides/python-net/zh-hant/aspose.slides.charts/axis/actual_minor_unit_scale/) | 指定軸的實際次要單位比例。請先呼叫方法 IChart.ValidateChartLayout() 以取得實際值。 |
| [`is_automatic_max_value`](/slides/python-net/zh-hant/aspose.slides.charts/axis/is_automatic_max_value/) | 指示最大值是否自動指派。<br/>             可讀寫 **bool**。 |
| [`max_value`](/slides/python-net/zh-hant/aspose.slides.charts/axis/max_value/) | 表示值軸的最大值。<br/>             可讀寫 **float**。 |
| [`minor_unit`](/slides/python-net/zh-hant/aspose.slides.charts/axis/minor_unit/) | 表示日期或值軸的次要單位。<br/>             可讀寫 **float**。 |
| [`is_automatic_minor_unit`](/slides/python-net/zh-hant/aspose.slides.charts/axis/is_automatic_minor_unit/) | 指示軸的次要單位是否自動指派。<br/>             可讀寫 **bool**。 |
| [`major_unit`](/slides/python-net/zh-hant/aspose.slides.charts/axis/major_unit/) | 表示日期或值軸的主要單位。<br/>             可讀寫 **float**。 |
| [`is_automatic_major_unit`](/slides/python-net/zh-hant/aspose.slides.charts/axis/is_automatic_major_unit/) | 指示軸的主要單位是否自動指派。 <br/>            可讀寫 **bool**。 |
| [`is_automatic_min_value`](/slides/python-net/zh-hant/aspose.slides.charts/axis/is_automatic_min_value/) | 指示最小值是否自動指派。<br/>             可讀寫 **bool**。 |
| [`min_value`](/slides/python-net/zh-hant/aspose.slides.charts/axis/min_value/) | 表示值軸的最小值。<br/>             可讀寫 **float**。 |
| [`is_logarithmic`](/slides/python-net/zh-hant/aspose.slides.charts/axis/is_logarithmic/) | 表示值軸的比例類型是否為對數。<br/>             可讀寫 **bool**。 |
| [`log_base`](/slides/python-net/zh-hant/aspose.slides.charts/axis/log_base/) | 表示對數基底。預設值為 10。<br/>             可讀寫 **float**。 |
| [`is_plot_order_reversed`](/slides/python-net/zh-hant/aspose.slides.charts/axis/is_plot_order_reversed/) | 表示 MS PowerPoint 是否從最後到第一繪製資料點。<br/>             可讀寫 **bool**。 |
| [`is_visible`](/slides/python-net/zh-hant/aspose.slides.charts/axis/is_visible/) | 表示軸是否可見。<br/>             可讀寫 **bool**。 |
| [`major_tick_mark`](/slides/python-net/zh-hant/aspose.slides.charts/axis/major_tick_mark/) | 表示指定軸的主要刻度標記類型。<br/>             可讀寫 [`TickMarkType`](/slides/python-net/zh-hant/aspose.slides.charts/tickmarktype)。 |
| [`minor_tick_mark`](/slides/python-net/zh-hant/aspose.slides.charts/axis/minor_tick_mark/) | 表示指定軸的次要刻度標記類型。<br/>             可讀寫 [`TickMarkType`](/slides/python-net/zh-hant/aspose.slides.charts/tickmarktype)。 |
| [`tick_label_position`](/slides/python-net/zh-hant/aspose.slides.charts/axis/tick_label_position/) | 表示指定軸上刻度標籤的位置。<br/>             可讀寫 [`TickLabelPositionType`](/slides/python-net/zh-hant/aspose.slides.charts/ticklabelpositiontype)。 |
| [`major_unit_scale`](/slides/python-net/zh-hant/aspose.slides.charts/axis/major_unit_scale/) | 表示日期軸的主要單位比例。<br/>             可讀寫 [`TimeUnitType`](/slides/python-net/zh-hant/aspose.slides.charts/timeunittype)。 |
| [`minor_unit_scale`](/slides/python-net/zh-hant/aspose.slides.charts/axis/minor_unit_scale/) | 表示日期軸的主要單位比例。<br/>             可讀寫 [`TimeUnitType`](/slides/python-net/zh-hant/aspose.slides.charts/timeunittype)。 |
| [`base_unit_scale`](/slides/python-net/zh-hant/aspose.slides.charts/axis/base_unit_scale/) | 指定日期軸上所呈現的最小時間單位。<br/>            可讀寫 [`TimeUnitType`](/slides/python-net/zh-hant/aspose.slides.charts/timeunittype)。 |
| [`minor_grid_lines_format`](/slides/python-net/zh-hant/aspose.slides.charts/axis/minor_grid_lines_format/) | 表示圖表軸上的次要格線格式。<br/>             唯讀 [`IChartLinesFormat`](/slides/python-net/zh-hant/aspose.slides.charts/ichartlinesformat)。 |
| [`major_grid_lines_format`](/slides/python-net/zh-hant/aspose.slides.charts/axis/major_grid_lines_format/) | 表示圖表軸上的主要格線格式。<br/>             唯讀 [`IChartLinesFormat`](/slides/python-net/zh-hant/aspose.slides.charts/ichartlinesformat)。 |
| [`show_minor_grid_lines`](/slides/python-net/zh-hant/aspose.slides.charts/axis/show_minor_grid_lines/) | 若要隱藏次要格線，將 MinorGridLinesFormat.Line.FillFormat.FillType 設為 FillType.NoFill。<br/>            唯讀 **bool**。 |
| [`show_major_grid_lines`](/slides/python-net/zh-hant/aspose.slides.charts/axis/show_major_grid_lines/) | 若要隱藏主要格線，將 MajorGridLinesFormat.Line.FillFormat.FillType 設為 FillType.NoFill。<br/>            唯讀 **bool**。 |
| [`format`](/slides/python-net/zh-hant/aspose.slides.charts/axis/format/) | 表示軸的格式。<br/>             唯讀 [`IAxisFormat`](/slides/python-net/zh-hant/aspose.slides.charts/iaxisformat)。 |
| [`text_format`](/slides/python-net/zh-hant/aspose.slides.charts/axis/text_format/) | 表示文字的格式。<br/>             唯讀 [`IChartTextFormat`](/slides/python-net/zh-hant/aspose.slides.charts/icharttextformat)。 |
| [`title`](/slides/python-net/zh-hant/aspose.slides.charts/axis/title/) | 取得軸的標題。<br/>             唯讀 [`IChartTitle`](/slides/python-net/zh-hant/aspose.slides.charts/icharttitle)。 |
| [`cross_type`](/slides/python-net/zh-hant/aspose.slides.charts/axis/cross_type/) | 表示指定軸上另一軸交叉的 CrossType。<br/>             可讀寫 [`CrossesType`](/slides/python-net/zh-hant/aspose.slides.charts/crossestype)。 |
| [`position`](/slides/python-net/zh-hant/aspose.slides.charts/axis/position/) | 表示軸的位置。<br/>             可讀寫 [`AxisPositionType`](/slides/python-net/zh-hant/aspose.slides.charts/axispositiontype)。 |
| [`has_title`](/slides/python-net/zh-hant/aspose.slides.charts/axis/has_title/) | 決定軸是否具有可見的標題。<br/>            可讀寫 **bool**。 |
| [`number_format`](/slides/python-net/zh-hant/aspose.slides.charts/axis/number_format/) | 表示軸標籤的格式字串。<br/>            可讀寫 **str**。 |
| [`is_number_format_linked_to_source`](/slides/python-net/zh-hant/aspose.slides.charts/axis/is_number_format_linked_to_source/) | 指示格式是否為連結的來源資料。<br/>            可讀寫 **bool**。 |
| [`tick_label_rotation_angle`](/slides/python-net/zh-hant/aspose.slides.charts/axis/tick_label_rotation_angle/) | 表示刻度標籤的旋轉角度。<br/>            可讀寫 **float**。 |
| [`tick_label_spacing`](/slides/python-net/zh-hant/aspose.slides.charts/axis/tick_label_spacing/) | 指定在已繪製的標籤之間要跳過的刻度標籤數量。適用於類別或資料系列軸。<br/>            可讀寫 **int**。 |
| [`is_automatic_tick_label_spacing`](/slides/python-net/zh-hant/aspose.slides.charts/axis/is_automatic_tick_label_spacing/) | 指定自動刻度標籤間距值。若為 false，使用 TickLabelSpacing 屬性。<br/>            可讀寫 **bool**。 |
| [`tick_marks_spacing`](/slides/python-net/zh-hant/aspose.slides.charts/axis/tick_marks_spacing/) | 指定在下一個刻度標記繪製前要跳過的刻度標記數量。<br/>            適用於類別或資料系列軸。<br/>            可讀寫 **int**。 |
| [`is_automatic_tick_marks_spacing`](/slides/python-net/zh-hant/aspose.slides.charts/axis/is_automatic_tick_marks_spacing/) | 指定自動刻度標記間距值。若為 false，使用 TickMarksSpacing 屬性。<br/>            可讀寫 **bool**。 |
| [`label_offset`](/slides/python-net/zh-hant/aspose.slides.charts/axis/label_offset/) | 指定標籤與軸的距離。適用於類別或日期軸。值必須在 0% 到 1000% 之間。<br/>            可讀寫 **int**。 |
| [`aggregation_type`](/slides/python-net/zh-hant/aspose.slides.charts/axis/aggregation_type/) | 表示類別軸的彙總類型（分箱）。適用於類別。僅與 Histogram 或 HistogramPareto 系列一起使用。 |
| [`bin_width`](/slides/python-net/zh-hant/aspose.slides.charts/axis/bin_width/) | 當 AggregationType 屬性值設為 AxisAggregationType.ByBinWidth 時，指定分箱寬度。<br/>            適用於類別軸。僅與 Histogram 或 HistogramPareto 系列一起使用。 |
| [`number_of_bins`](/slides/python-net/zh-hant/aspose.slides.charts/axis/number_of_bins/) | 當 AggregationType 屬性值設為 AxisAggregationType.ByNumberOfBins 時，指定分箱數量。<br/>            適用於類別軸。僅與 Histogram 或 HistogramPareto 系列一起使用。 |
| [`is_overflow_bin`](/slides/python-net/zh-hant/aspose.slides.charts/axis/is_overflow_bin/) | 指定是否套用溢位分箱。使用 IsAutomaticOverflowBin 與 OverflowBin 來調整溢位分箱值。 |
| [`is_automatic_overflow_bin`](/slides/python-net/zh-hant/aspose.slides.charts/axis/is_automatic_overflow_bin/) | 指定自動溢位分箱值。若為 false，使用 OverflowBin 屬性。 |
| [`overflow_bin`](/slides/python-net/zh-hant/aspose.slides.charts/axis/overflow_bin/) | 指定溢位分箱的自訂值。當 IsAutomaticOverflowBin 屬性設為 false 且 IsOverflowBin 屬性為 true 時套用。 |
| [`is_underflow_bin`](/slides/python-net/zh-hant/aspose.slides.charts/axis/is_underflow_bin/) | 指定是否套用欠位分箱。使用 IsAutomaticUnderflowBin 與 UnderflowBin 來調整欠位分箱值。 |
| [`is_automatic_underflow_bin`](/slides/python-net/zh-hant/aspose.slides.charts/axis/is_automatic_underflow_bin/) | 指定自動欠位分箱值。若為 false，使用 UnderflowBin 屬性。 |
| [`underflow_bin`](/slides/python-net/zh-hant/aspose.slides.charts/axis/underflow_bin/) | 指定欠位分箱的自訂值。當 IsAutomaticUnderflowBin 屬性設為 false 且 IsUnderflowBin 屬性為 true 時套用。 |
| [`slide`](/slides/python-net/zh-hant/aspose.slides.charts/axis/slide/) |  |
| [`presentation`](/slides/python-net/zh-hant/aspose.slides.charts/axis/presentation/) |  |

## 方法

| Method | Description |
| :- | :- |
| [`set_category_axis_type_automatically(self)`](/slides/python-net/zh-hant/aspose.slides.charts/axis/set_category_axis_type_automatically/#) | 設定 IAxis.CategoryAxisType 屬性，使用根據軸資料自動決定的值。 |

### 另見
* 模組 [`aspose.slides.charts`](/slides/python-net/zh-hant/aspose.slides.charts)
* 函式庫 [`Aspose.Slides`](/slides/python-net)