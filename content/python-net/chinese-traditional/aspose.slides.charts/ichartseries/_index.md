---
title: IChartSeries class
second_title: Aspose.Slides for Python via .NET API 參考
description: 
type: docs
url: /zh-hant/aspose.slides.charts/ichartseries/
---
## IChartSeries 類別

表示圖表系列。

IChartSeries 類型公開以下成員：

## 屬性

| Property | Description |
| :- | :- |
| [`explosion`](/slides/python-net/zh-hant/aspose.slides.charts/ichartseries/explosion/) | 以餅圖直徑的百分比表示開口餅片距離餅圖中心的距離。<br/>             讀/寫 **int**。 |
| [`smooth`](/slides/python-net/zh-hant/aspose.slides.charts/ichartseries/smooth/) | 表示曲線平滑。若對折線圖或散點圖開啟曲線平滑則為 True。僅適用於折線圖與以線相連的散點圖。<br/>            讀/寫 **bool**。 |
| [`marker`](/slides/python-net/zh-hant/aspose.slides.charts/ichartseries/marker/) | 回傳系列標記。<br/>            唯讀 [`IMarker`](/slides/python-net/zh-hant/aspose.slides.charts/imarker)。 |
| [`bar_3d_shape`](/slides/python-net/zh-hant/aspose.slides.charts/ichartseries/bar_3d_shape/) | 指定 3-D 長條圖系列的形狀。<br/>            更改此屬性的值可能會自動變更系列的 Type。<br/>            讀/寫 [`ChartShapeType`](/slides/python-net/zh-hant/aspose.slides.charts/chartshapetype)。 |
| [`name`](/slides/python-net/zh-hant/aspose.slides.charts/ichartseries/name/) | 回傳系列名稱。<br/>            唯讀 [`IStringChartValue`](/slides/python-net/zh-hant/aspose.slides.charts/istringchartvalue)。 |
| [`data_points`](/slides/python-net/zh-hant/aspose.slides.charts/ichartseries/data_points/) | 回傳此系列的資料點集合。<br/>            唯讀 [`IChartDataPointCollection`](/slides/python-net/zh-hant/aspose.slides.charts/ichartdatapointcollection)。 |
| [`type`](/slides/python-net/zh-hant/aspose.slides.charts/ichartseries/type/) | 回傳此系列的類型。<br/>            讀/寫 [`ChartType`](/slides/python-net/zh-hant/aspose.slides.charts/charttype)。 |
| [`parent_series_group`](/slides/python-net/zh-hant/aspose.slides.charts/ichartseries/parent_series_group/) | 回傳父系列群組。<br/>            唯讀 [`IChartSeriesGroup`](/slides/python-net/zh-hant/aspose.slides.charts/ichartseriesgroup)。 |
| [`format`](/slides/python-net/zh-hant/aspose.slides.charts/ichartseries/format/) | 回傳系列的格式。<br/>            唯讀 [`IFormat`](/slides/python-net/zh-hant/aspose.slides.charts/iformat)。 |
| [`order`](/slides/python-net/zh-hant/aspose.slides.charts/ichartseries/order/) | 回傳系列的順序。<br/>            讀/寫 **int**。 |
| [`labels`](/slides/python-net/zh-hant/aspose.slides.charts/ichartseries/labels/) | 回傳系列的標籤。<br/>            唯讀 [`IDataLabelCollection`](/slides/python-net/zh-hant/aspose.slides.charts/idatalabelcollection)。 |
| [`trend_lines`](/slides/python-net/zh-hant/aspose.slides.charts/ichartseries/trend_lines/) | 系列趨勢線集合<br/>            唯讀 [`ITrendlineCollection`](/slides/python-net/zh-hant/aspose.slides.charts/itrendlinecollection)。 |
| [`error_bars_x_format`](/slides/python-net/zh-hant/aspose.slides.charts/ichartseries/error_bars_x_format/) | 代表方向為 X 的系列誤差棒。<br/>            <br/>            方向為 X 的誤差棒適用於 area、bar、scatter 及 bubble 類型的系列。<br/>            其他圖表類型（包括 3D 圖表）此屬性回傳 None。<br/>            若使用自訂值，請使用 DataPoints 集合並搭配 [`IChartDataPoint.error_bars_custom_values`](/slides/python-net/zh-hant/aspose.slides.charts/ichartdatapoint/error_bars_custom_values) 屬性指定值。<br/>            <br/>            唯讀 [`IErrorBarsFormat`](/slides/python-net/zh-hant/aspose.slides.charts/ierrorbarsformat)。 |
| [`error_bars_y_format`](/slides/python-net/zh-hant/aspose.slides.charts/ichartseries/error_bars_y_format/) | 代表方向為 Y 的系列誤差棒。<br/>            <br/>            方向為 Y 的誤差棒適用於 area、bar、line、scatter 及 bubble 類型的系列。<br/>            其他圖表類型（包括 3D 圖表）此屬性回傳 None。<br/>            若使用自訂值，請使用 DataPoints 集合並搭配 [`IChartDataPoint.error_bars_custom_values`](/slides/python-net/zh-hant/aspose.slides.charts/ichartdatapoint/error_bars_custom_values) 屬性指定值。<br/>            <br/>            唯讀 [`IErrorBarsFormat`](/slides/python-net/zh-hant/aspose.slides.charts/ierrorbarsformat)。 |
| [`plot_on_second_axis`](/slides/python-net/zh-hant/aspose.slides.charts/ichartseries/plot_on_second_axis/) | 指示此系列是否繪製於第二值軸上。<br/>            讀/寫 **bool**。 |
| [`number_format_of_values`](/slides/python-net/zh-hant/aspose.slides.charts/ichartseries/number_format_of_values/) | 取得或設定系列值的數字格式。<br/>            讀/寫 **str**。 |
| [`number_format_of_x_values`](/slides/python-net/zh-hant/aspose.slides.charts/ichartseries/number_format_of_x_values/) | 取得或設定系列 X 值的數字格式。<br/>            讀/寫 **str**。 |
| [`number_format_of_y_values`](/slides/python-net/zh-hant/aspose.slides.charts/ichartseries/number_format_of_y_values/) | 取得或設定系列 Y 值的數字格式。<br/>            讀/寫 **str**。 |
| [`number_format_of_bubble_sizes`](/slides/python-net/zh-hant/aspose.slides.charts/ichartseries/number_format_of_bubble_sizes/) | 取得或設定系列氣泡大小的數字格式。<br/>            讀/寫 **str**。 |
| [`invert_if_negative`](/slides/python-net/zh-hant/aspose.slides.charts/ichartseries/invert_if_negative/) | 指定若值為負，條形、柱形或氣泡系列是否反轉其顏色。<br/>            讀/寫 **bool**。 |
| [`inverted_solid_fill_color`](/slides/python-net/zh-hant/aspose.slides.charts/ichartseries/inverted_solid_fill_color/) | 指定系列的倒轉實色。要套用顏色設定，請將系列格式 FillType 設為 FillType.Solid。<br/>            讀/寫 [`IColorFormat`](/slides/python-net/zh-hant/aspose.slides/icolorformat)。 |
| [`related_legend_entry`](/slides/python-net/zh-hant/aspose.slides.charts/ichartseries/related_legend_entry/) | 代表與此系列相關的圖例項目<br/>            唯讀 [`ILegendEntryProperties`](/slides/python-net/zh-hant/aspose.slides.charts/ilegendentryproperties)。 |
| [`show_inner_points`](/slides/python-net/zh-hant/aspose.slides.charts/ichartseries/show_inner_points/) | 代表內部點。若在 BoxAndWhisker 圖表上顯示內部點則為 True。僅適用於 BoxAndWhisker 圖表。<br/>            讀/寫 **bool**。 |
| [`show_outlier_points`](/slides/python-net/zh-hant/aspose.slides.charts/ichartseries/show_outlier_points/) | 代表異常值點。若在 BoxAndWhisker 圖表上顯示異常值點則為 True。僅適用於 BoxAndWhisker 圖表。<br/>            讀/寫 **bool**。 |
| [`show_mean_markers`](/slides/python-net/zh-hant/aspose.slides.charts/ichartseries/show_mean_markers/) | 代表平均值標記。若在 BoxAndWhisker 圖表上顯示平均值標記則為 True。僅適用於 BoxAndWhisker 圖表。<br/>            讀/寫 **bool**。 |
| [`show_mean_line`](/slides/python-net/zh-hant/aspose.slides.charts/ichartseries/show_mean_line/) | 代表平均線。若在 BoxAndWhisker 圖表上顯示平均線則為 True。僅適用於 BoxAndWhisker 圖表。<br/>            讀/寫 **bool**。 |
| [`quartile_method`](/slides/python-net/zh-hant/aspose.slides.charts/ichartseries/quartile_method/) | 代表四分位方法。僅適用於 BoxAndWhisker 圖表。 |
| [`show_connector_lines`](/slides/python-net/zh-hant/aspose.slides.charts/ichartseries/show_connector_lines/) | 代表連接線。僅適用於 Waterfall 圖表。 |
| [`parent_label_layout`](/slides/python-net/zh-hant/aspose.slides.charts/ichartseries/parent_label_layout/) | 代表父類別標籤的版面配置。僅適用於 Treemap 圖表。 |
| [`bubble_size_scale`](/slides/python-net/zh-hant/aspose.slides.charts/ichartseries/bubble_size_scale/) | 指定氣泡圖的比例因子（可在 0% 到 300% 預設大小之間）。<br/>            此屬性不僅屬於本系列，也屬於父系列群組的所有系列 —— 為相應群組屬性的投射。因此此屬性為唯讀。<br/>            使用 ParentSeriesGroup 屬性存取父系列群組。<br/>            使用 ParentSeriesGroup.BubbleSizeScale 讀/寫屬性變更值。 |
| [`has_up_down_bars`](/slides/python-net/zh-hant/aspose.slides.charts/ichartseries/has_up_down_bars/) | 判斷折線圖或股票圖是否具有上下棒。<br/>            此屬性不僅屬於本系列，也屬於父系列群組的所有系列 —— 為相應群組屬性的投射。因此此屬性為唯讀。<br/>            使用 ParentSeriesGroup 屬性存取父系列群組。<br/>            使用 ParentSeriesGroup.UpDownBars.HasUpDownBars 讀/寫屬性變更值。<br/>            使用 ParentSeriesGroup.UpDownBars 屬性設定上下棒的格式。<br/>            唯讀 **bool**。 |
| [`gap_width`](/slides/python-net/zh-hant/aspose.slides.charts/ichartseries/gap_width/) | 指定條形或柱形叢集之間的間距，作為條形或柱形寬度的百分比。<br/>            此屬性不僅屬於本系列，也屬於父系列群組的所有系列 —— 為相應群組屬性的投射。因此此屬性為唯讀。<br/>            使用 ParentSeriesGroup 屬性存取父系列群組。<br/>            使用 ParentSeriesGroup.GapWidth 讀/寫屬性變更值。<br/>            唯讀 **int**。 |
| [`gap_depth`](/slides/python-net/zh-hant/aspose.slides.charts/ichartseries/gap_depth/) | 以資料標記寬度的百分比回傳 3D 圖表中資料系列之間的距離。<br/>            此屬性不僅屬於本系列，也屬於父系列群組的所有系列 —— 為相應群組屬性的投射。因此此屬性為唯讀。<br/>            使用 ParentSeriesGroup 屬性存取父系列群組。<br/>            使用 ParentSeriesGroup.GapDepth 讀/寫屬性變更值。<br/>            唯讀 **int**。 |
| [`is_color_varied`](/slides/python-net/zh-hant/aspose.slides.charts/ichartseries/is_color_varied/) | 指定系列中的每個資料標記具有不同的顏色。<br/>            此屬性不僅屬於本系列，也屬於父系列群組的所有系列 —— 為相應群組屬性的投射。因此此屬性為唯讀。<br/>            使用 ParentSeriesGroup 屬性存取父系列群組。<br/>            使用 ParentSeriesGroup.IsColorVaried 讀/寫屬性變更值。<br/>            唯讀 **bool**。 |
| [`has_series_lines`](/slides/python-net/zh-hant/aspose.slides.charts/ichartseries/has_series_lines/) | 判斷此系列及相關系列是否具有系列線。<br/>            此屬性不僅屬於本系列，也屬於父系列群組的所有系列 —— 為相應群組屬性的投射。因此此屬性為唯讀。<br/>            使用 ParentSeriesGroup 屬性存取父系列群組。<br/>            使用 ParentSeriesGroup.HasSeriesLines 讀/寫屬性變更值。<br/>            使用 ParentSeriesGroup.SeriesLinesFormat 屬性設定系列線的格式。<br/>            唯讀 **bool**。 |
| [`overlap`](/slides/python-net/zh-hant/aspose.slides.charts/ichartseries/overlap/) | 指定 2-D 圖表上條形與柱形的重疊程度，百分比範圍為 -100% 到 100%。<br/>            此屬性不僅屬於本系列，也屬於父系列群組的所有系列 —— 為相應群組屬性的投射。因此此屬性為唯讀。<br/>            若要變更值，請使用 ParentSeriesGroup.Overlap 讀/寫屬性。<br/>            唯讀 **int**。 |
| [`second_pie_size`](/slides/python-net/zh-hant/aspose.slides.charts/ichartseries/second_pie_size/) | 指定 “pie-of-pie” 或 “bar-of-pie” 圖表中第二個餅或條的大小，作為第一個餅大小的百分比（可介於 5% 到 200% 之間）。<br/>            此屬性不僅屬於本系列，也屬於父系列群組的所有系列 —— 為相應群組屬性的投射。因此此屬性為唯讀。<br/>            使用 ParentSeriesGroup 屬性存取父系列群組。<br/>            使用 ParentSeriesGroup.SecondPieSize 讀/寫屬性變更值。<br/>            唯讀 **int**。 |
| [`pie_split_position`](/slides/python-net/zh-hant/aspose.slides.charts/ichartseries/pie_split_position/) | 指定用於決定哪些資料點位於 “pie-of-pie” 或 “bar-of-pie” 圖表的第二個餅或條的值。<br/>            與 PieSplitBy 屬性一起使用。<br/>            此屬性不僅屬於本系列，也屬於父系列群組的所有系列 —— 為相應群組屬性的投射。因此此屬性為唯讀。<br/>            使用 ParentSeriesGroup 屬性存取父系列群組。<br/>            使用 ParentSeriesGroup.PieSplitPosition 讀/寫屬性變更值。<br/>            唯讀 **float**。 |
| [`pie_split_by`](/slides/python-net/zh-hant/aspose.slides.charts/ichartseries/pie_split_by/) | 指定如何決定哪些資料點位於 “pie-of-pie” 或 “bar-of-pie” 圖表的第二個餅或條。<br/>            此屬性不僅屬於本系列，也屬於父系列群組的所有系列 —— 為相應群組屬性的投射。因此此屬性為唯讀。<br/>            使用 ParentSeriesGroup 屬性存取父系列群組。<br/>            使用 ParentSeriesGroup.PieSplitBy 讀/寫屬性變更值。<br/>            唯讀 [`PieSplitType`](/slides/python-net/zh-hant/aspose.slides.charts/piesplittype)。 |
| [`doughnut_hole_size`](/slides/python-net/zh-hant/aspose.slides.charts/ichartseries/doughnut_hole_size/) | 指定環形圖中孔的大小（可介於繪圖區大小的 10% 到 90% 之間）。<br/>            此屬性不僅屬於本系列，也屬於父系列群組的所有系列 —— 為相應群組屬性的投射。因此此屬性為唯讀。<br/>            使用 ParentSeriesGroup 屬性存取父系列群組。<br/>            使用 ParentSeriesGroup.DoughnutHoleSize 讀/寫屬性變更值。<br/>            唯讀 **int**。 |
| [`first_slice_angle`](/slides/python-net/zh-hant/aspose.slides.charts/ichartseries/first_slice_angle/) | 指定第一個餅或環形圖切片的角度（以度為單位，順時針從上方 0 度到 360 度）。<br/>            此屬性不僅屬於本系列，也屬於父系列群組的所有系列 —— 為相應群組屬性的投射。因此此屬性為唯讀。<br/>            使用 ParentSeriesGroup 屬性存取父系列群組。<br/>            使用 ParentSeriesGroup.FirstSliceAngle 讀/寫屬性變更值。<br/>            唯讀 **int**。 |
| [`pie_split_custom_points`](/slides/python-net/zh-hant/aspose.slides.charts/ichartseries/pie_split_custom_points/) | 具有自訂分割的 “pie-of-pie” 或 “bar-of-pie” 圖表的自訂分割資訊。<br/>            包含應在第二個餅或條中繪製的資料點。<br/>            此屬性不僅屬於本系列，也屬於父系列群組的所有系列 —— 為相應群組屬性投射。<br/>            唯讀 [`IPieSplitCustomPointCollection`](/slides/python-net/zh-hant/aspose.slides.charts/ipiesplitcustompointcollection)。 |
| [`bubble_size_representation`](/slides/python-net/zh-hant/aspose.slides.charts/ichartseries/bubble_size_representation/) | 指定氣泡圖上氣泡大小值的表示方式。<br/>            此屬性不僅屬於本系列，也屬於父系列群組的所有系列 —— 為相應群組屬性的投射。因此此屬性為唯讀。<br/>            使用 ParentSeriesGroup 屬性存取父系列群組。<br/>            使用 ParentSeriesGroup.BubbleSizeRepresentation 讀/寫屬性變更值。 |
| [`chart`](/slides/python-net/zh-hant/aspose.slides.charts/ichartseries/chart/) |  |
| [`slide`](/slides/python-net/zh-hant/aspose.slides.charts/ichartseries/slide/) |  |
| [`presentation`](/slides/python-net/zh-hant/aspose.slides.charts/ichartseries/presentation/) |  |

## 方法

| Method | Description |
| :- | :- |
| [`get_automatic_series_color(self)`](/slides/python-net/zh-hant/aspose.slides.charts/ichartseries/get_automatic_series_color/#) | 回傳基於系列索引與圖表樣式的自動系列顏色。<br/>            若 FillType 為 NotDefined，則預設使用此顏色。 |

### 另見
* 模組 [`aspose.slides.charts`](/slides/python-net/zh-hant/aspose.slides.charts)
* 程式庫 [`Aspose.Slides`](/slides/python-net)