---
title: ChartSeries class
second_title: Aspose.Slides for Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides.charts/chartseries/
---
## ChartSeries 類別

代表圖表系列。

ChartSeries 類型公開以下成員：

## 屬性

| Property | Description |
| :- | :- |
| [`chart`](/slides/python-net/zh-hant/aspose.slides.charts/chartseries/chart/) | 傳回父圖表。<br/>            唯讀 [`IChart`](/slides/python-net/zh-hant/aspose.slides.charts/ichart)。 |
| [`explosion`](/slides/python-net/zh-hant/aspose.slides.charts/chartseries/explosion/) | 開啟的餅圖切片與餅圖中心的距離以餅圖直徑的百分比表示。<br/>            讀/寫 **int**。 |
| [`smooth`](/slides/python-net/zh-hant/aspose.slides.charts/chartseries/smooth/) | 代表曲線平滑。若線圖或散佈圖啟用曲線平滑則為 True。<br/>            僅適用於線圖和以線連接的散佈圖。<br/>            讀/寫 **bool**。 |
| [`name`](/slides/python-net/zh-hant/aspose.slides.charts/chartseries/name/) | 傳回系列名稱。<br/>            唯讀 [`IStringChartValue`](/slides/python-net/zh-hant/aspose.slides.charts/istringchartvalue)。 |
| [`data_points`](/slides/python-net/zh-hant/aspose.slides.charts/chartseries/data_points/) | 傳回此系列的資料點集合。<br/>            唯讀 [`IChartDataPointCollection`](/slides/python-net/zh-hant/aspose.slides.charts/ichartdatapointcollection)。 |
| [`type`](/slides/python-net/zh-hant/aspose.slides.charts/chartseries/type/) | 傳回此系列的類型。<br/>            讀/寫 [`ChartType`](/slides/python-net/zh-hant/aspose.slides.charts/charttype)。 |
| [`plot_on_second_axis`](/slides/python-net/zh-hant/aspose.slides.charts/chartseries/plot_on_second_axis/) | 指出此系列是否繪製於次要軸上。<br/>            讀/寫 **bool**。 |
| [`parent_series_group`](/slides/python-net/zh-hant/aspose.slides.charts/chartseries/parent_series_group/) | ParentSeriesGroup.<br/>            唯讀 [`IChartSeriesGroup`](/slides/python-net/zh-hant/aspose.slides.charts/ichartseriesgroup)。 |
| [`format`](/slides/python-net/zh-hant/aspose.slides.charts/chartseries/format/) | 傳回系列的格式。<br/>            唯讀 [`IFormat`](/slides/python-net/zh-hant/aspose.slides.charts/iformat)。 |
| [`order`](/slides/python-net/zh-hant/aspose.slides.charts/chartseries/order/) | 傳回系列的順序。<br/>            讀/寫 **int**。 |
| [`labels`](/slides/python-net/zh-hant/aspose.slides.charts/chartseries/labels/) | 傳回系列的標籤。<br/>            唯讀 [`IDataLabelCollection`](/slides/python-net/zh-hant/aspose.slides.charts/idatalabelcollection)。 |
| [`trend_lines`](/slides/python-net/zh-hant/aspose.slides.charts/chartseries/trend_lines/) | 系列趨勢線的集合。<br/>            唯讀 [`ITrendlineCollection`](/slides/python-net/zh-hant/aspose.slides.charts/itrendlinecollection)。 |
| [`error_bars_x_format`](/slides/python-net/zh-hant/aspose.slides.charts/chartseries/error_bars_x_format/) | 代表方向為 X 的系列誤差棒。 <br/>            <br/>            X 方向的誤差棒適用於 area、bar、scatter 與 bubble 類型的系列。 <br/>            對於其他類型的圖表，此屬性傳回 None（包括 3D 圖表）。<br/>            若使用自訂值，請使用 DataPoints 集合指定值<br/>            （使用 [`IChartDataPoint.error_bars_custom_values`](/slides/python-net/zh-hant/aspose.slides.charts/ichartdatapoint/error_bars_custom_values) 屬性）。<br/>            <br/>            唯讀 [`IErrorBarsFormat`](/slides/python-net/zh-hant/aspose.slides.charts/ierrorbarsformat)。 |
| [`error_bars_y_format`](/slides/python-net/zh-hant/aspose.slides.charts/chartseries/error_bars_y_format/) | 代表方向為 Y 的系列誤差棒。<br/>            <br/>            Y 方向的誤差棒適用於 area、bar、line、scatter 與 bubble 類型的系列。 <br/>            對於其他類型的圖表，此屬性傳回 None（包括 3D 圖表）。 <br/>            若使用自訂值，請使用 DataPoints 集合指定值<br/>            （使用 [`IChartDataPoint.error_bars_custom_values`](/slides/python-net/zh-hant/aspose.slides.charts/ichartdatapoint/error_bars_custom_values) 屬性）。<br/>            <br/>            唯讀 [`IErrorBarsFormat`](/slides/python-net/zh-hant/aspose.slides.charts/ierrorbarsformat)。 |
| [`related_legend_entry`](/slides/python-net/zh-hant/aspose.slides.charts/chartseries/related_legend_entry/) | 代表與此系列相關的圖例項目<br/>            唯讀 [`ILegendEntryProperties`](/slides/python-net/zh-hant/aspose.slides.charts/ilegendentryproperties)。 |
| [`number_format_of_values`](/slides/python-net/zh-hant/aspose.slides.charts/chartseries/number_format_of_values/) | NumberFormatOfValues.<br/>            讀/寫 **str**。 |
| [`number_format_of_x_values`](/slides/python-net/zh-hant/aspose.slides.charts/chartseries/number_format_of_x_values/) | NumberFormatOfXValues.<br/>            讀/寫 **str**。 |
| [`number_format_of_y_values`](/slides/python-net/zh-hant/aspose.slides.charts/chartseries/number_format_of_y_values/) | NumberFormatOfYValues.<br/>            讀/寫 **str**。 |
| [`number_format_of_bubble_sizes`](/slides/python-net/zh-hant/aspose.slides.charts/chartseries/number_format_of_bubble_sizes/) | NumberFormatOfBubbleSizes.<br/>            讀/寫 **str**。 |
| [`marker`](/slides/python-net/zh-hant/aspose.slides.charts/chartseries/marker/) | Marker.<br/>            唯讀 [`IMarker`](/slides/python-net/zh-hant/aspose.slides.charts/imarker)。 |
| [`bar_3d_shape`](/slides/python-net/zh-hant/aspose.slides.charts/chartseries/bar_3d_shape/) | 指定 3-D 條形圖系列的形狀。<br/>            變更此屬性的值可能會自動變更系列的 Type。<br/>            讀/寫 [`ChartShapeType`](/slides/python-net/zh-hant/aspose.slides.charts/chartshapetype)。 |
| [`invert_if_negative`](/slides/python-net/zh-hant/aspose.slides.charts/chartseries/invert_if_negative/) | 指定若數值為負，條形、柱形或氣泡系列應反轉其顏色。<br/>            讀/寫 **bool**。 |
| [`inverted_solid_fill_color`](/slides/python-net/zh-hant/aspose.slides.charts/chartseries/inverted_solid_fill_color/) | 指定為系列反轉實心顏色。若要套用顏色設定，請將系列格式的 FillType 設為 FillType.Solid。<br/>            讀/寫 [`ColorFormat`](/slides/python-net/zh-hant/aspose.slides/colorformat)。 |
| [`show_inner_points`](/slides/python-net/zh-hant/aspose.slides.charts/chartseries/show_inner_points/) | 代表內部點。若在 BoxAndWhisker 圖表上顯示內部點則為 True。僅適用於 BoxAndWhisker 圖表。<br/>            讀/寫 **bool**。 |
| [`show_outlier_points`](/slides/python-net/zh-hant/aspose.slides.charts/chartseries/show_outlier_points/) | 代表異常值點。若在 BoxAndWhisker 圖表上顯示異常值點則為 True。僅適用於 BoxAndWhisker 圖表。<br/>            讀/寫 **bool**。 |
| [`show_mean_markers`](/slides/python-net/zh-hant/aspose.slides.charts/chartseries/show_mean_markers/) | 代表平均值標記。若在 BoxAndWhisker 圖表上顯示平均值標記則為 True。僅適用於 BoxAndWhisker 圖表。<br/>            讀/寫 **bool**。 |
| [`show_mean_line`](/slides/python-net/zh-hant/aspose.slides.charts/chartseries/show_mean_line/) | 代表平均線。若在 BoxAndWhisker 圖表上顯示平均線則為 True。僅適用於 BoxAndWhisker 圖表。<br/>            讀/寫 **bool**。 |
| [`quartile_method`](/slides/python-net/zh-hant/aspose.slides.charts/chartseries/quartile_method/) | 代表四分位方法。僅適用於 BoxAndWhisker 圖表。 |
| [`show_connector_lines`](/slides/python-net/zh-hant/aspose.slides.charts/chartseries/show_connector_lines/) | 代表連接線。僅適用於 Waterfall 圖表。 |
| [`parent_label_layout`](/slides/python-net/zh-hant/aspose.slides.charts/chartseries/parent_label_layout/) | 代表父類別標籤的版面配置。   僅適用於 Treemap 圖表。 |
| [`has_up_down_bars`](/slides/python-net/zh-hant/aspose.slides.charts/chartseries/has_up_down_bars/) | 決定折線圖或股票圖是否具有上下棒。<br/>            此屬性不僅屬於此系列，同時屬於父系列群組的所有系列 - 為相應群組屬性的投射。因此此屬性<br/>            為唯讀。<br/>            使用 ParentSeriesGroup 屬性存取父系列群組。<br/>            使用 ParentSeriesGroup.UpDownBars.HasUpDownBars 讀/寫 屬性變更值。<br/>            使用 ParentSeriesGroup.UpDownBars 屬性設定上下棒的格式。<br/>            唯讀 **bool**。 |
| [`gap_width`](/slides/python-net/zh-hant/aspose.slides.charts/chartseries/gap_width/) | 指定條形或柱形叢之間的間距，以條形或柱形寬度的百分比表示。<br/>            此屬性不僅屬於此系列，同時屬於父系列群組的所有系列 - 為相應群組屬性的投射。因此此屬性<br/>            為唯讀。<br/>            使用 ParentSeriesGroup 屬性存取父系列群組。<br/>            使用 ParentSeriesGroup.GapWidth 讀/寫 屬性變更值。<br/>            唯讀 **int**。 |
| [`gap_depth`](/slides/python-net/zh-hant/aspose.slides.charts/chartseries/gap_depth/) | 傳回或設定在 3D 圖表中資料系列之間的距離，以標記寬度的百分比表示。<br/>            此屬性不僅屬於此系列，同時屬於父系列群組的所有系列 - 為相應群組屬性的投射。因此此屬性<br/>            為唯讀。<br/>            使用 ParentSeriesGroup 屬性存取父系列群組。<br/>            使用 ParentSeriesGroup.GapDepth 讀/寫 屬性變更值。<br/>            唯讀 **int**。 |
| [`first_slice_angle`](/slides/python-net/zh-hant/aspose.slides.charts/chartseries/first_slice_angle/) | 指定第一個餅圖或環形圖切片的角度，<br/>            以度數表示（從上方順時針，0 至 360 度）。<br/>            此屬性不僅屬於此系列，同時屬於父系列群組的所有系列 - 為相應群組屬性的投射。因此此屬性<br/>            為唯讀。<br/>            使用 ParentSeriesGroup 屬性存取父系列群組。<br/>            使用 ParentSeriesGroup.FirstSliceAngle 讀/寫 屬性變更值。<br/>            唯讀 **int**。 |
| [`doughnut_hole_size`](/slides/python-net/zh-hant/aspose.slides.charts/chartseries/doughnut_hole_size/) | 指定環形圖中孔洞的大小（可介於繪圖區大小的 10% 到 90% 之間）。<br/>            此屬性不僅屬於此系列，同時屬於父系列群組的所有系列 - 為相應群組屬性的投射。因此此屬性<br/>            為唯讀。<br/>            使用 ParentSeriesGroup 屬性存取父系列群組。<br/>            使用 ParentSeriesGroup.DoughnutHoleSize 讀/寫 屬性變更值。<br/>            唯讀 **int**。 |
| [`overlap`](/slides/python-net/zh-hant/aspose.slides.charts/chartseries/overlap/) | 指定 2-D 圖表中條形與柱形的重疊程度，以百分比表示（-100% 到 100%）。<br/>            此屬性不僅屬於此系列，同時屬於父系列群組的所有系列。<br/>            它是父系列群組中相應屬性的投射，因此此屬性為唯讀。<br/>            若要變更數值，請使用 **ParentSeriesGroup.Overlap** 讀/寫 屬性。<br/>            唯讀 **int**。 |
| [`second_pie_size`](/slides/python-net/zh-hant/aspose.slides.charts/chartseries/second_pie_size/) | 指定餅中餅或條中條圖的第二個餅或條的大小，以第一個餅的大小百分比表示（可介於 5% 到 200% 之間）。<br/>            此屬性不僅屬於此系列，同時屬於父系列群組的所有系列 - 為相應群組屬性的投射。因此此屬性<br/>            為唯讀。<br/>            使用 ParentSeriesGroup 屬性存取父系列群組。<br/>            使用 ParentSeriesGroup.SecondPieSize 讀/寫 屬性變更值。<br/>            唯讀 **int**。 |
| [`has_series_lines`](/slides/python-net/zh-hant/aspose.slides.charts/chartseries/has_series_lines/) | 決定此系列及相關系列是否有系列線。<br/>            此屬性不僅屬於此系列，同時屬於父系列群組的所有系列 - 為相應群組屬性的投射。因此此屬性<br/>            為唯讀。<br/>            使用 ParentSeriesGroup 屬性存取父系列群組。<br/>            使用 ParentSeriesGroup.HasSeriesLines 讀/寫 屬性變更值。<br/>            使用 ParentSeriesGroup.SeriesLinesFormat 屬性設定系列線格式。<br/>            唯讀 **bool**。 |
| [`bubble_size_representation`](/slides/python-net/zh-hant/aspose.slides.charts/chartseries/bubble_size_representation/) | 指定氣泡圖上氣泡大小值的表示方式。<br/>            此屬性不僅屬於此系列，同時屬於父系列群組的所有系列 - 為相應群組屬性的投射。因此此屬性<br/>            為唯讀。<br/>            使用 ParentSeriesGroup 屬性存取父系列群組。<br/>            使用 ParentSeriesGroup.BubbleSizeRepresentation 讀/寫 屬性變更值。 |
| [`pie_split_position`](/slides/python-net/zh-hant/aspose.slides.charts/chartseries/pie_split_position/) | 指定用於判斷哪些資料點屬於餅中餅或條中條圖第二個餅或條的值。<br/>            與 PieSplitBy 屬性共同使用。<br/>            此屬性不僅屬於此系列，同時屬於父系列群組的所有系列 - 為相應群組屬性的投射。因此此屬性<br/>            為唯讀。<br/>            使用 ParentSeriesGroup 屬性存取父系列群組。<br/>            使用 ParentSeriesGroup.PieSplitPosition 讀/寫 屬性變更值。<br/>            唯讀 **float**。 |
| [`pie_split_by`](/slides/python-net/zh-hant/aspose.slides.charts/chartseries/pie_split_by/) | 指定如何判斷哪些資料點屬於餅中餅或條中條圖的第二個餅或條。<br/>            此屬性不僅屬於此系列，同時屬於父系列群組的所有系列 - 為相應群組屬性的投射。因此此屬性<br/>            為唯讀。<br/>            使用 ParentSeriesGroup 屬性存取父系列群組。<br/>            使用 ParentSeriesGroup.PieSplitBy 讀/寫 屬性變更值。<br/>            唯讀 [`PieSplitType`](/slides/python-net/zh-hant/aspose.slides.charts/piesplittype)。 |
| [`pie_split_custom_points`](/slides/python-net/zh-hant/aspose.slides.charts/chartseries/pie_split_custom_points/) | 自訂分割資訊，用於具有自訂分割的餅中餅或條中條圖。<br/>            包含應繪製於第二個餅或條的資料點。<br/>            此屬性不僅屬於此系列，同時屬於父系列群組的所有系列 - 為相應群組屬性的投射<br/>            唯讀 [`PieSplitCustomPointCollection`](/slides/python-net/zh-hant/aspose.slides.charts/piesplitcustompointcollection)。 |
| [`is_color_varied`](/slides/python-net/zh-hant/aspose.slides.charts/chartseries/is_color_varied/) | 指定系列中的每個資料標記具有不同的顏色。<br/>            此屬性不僅屬於此系列，同時屬於父系列群組的所有系列 - 為相應群組屬性的投射。因此此屬性<br/>            為唯讀。<br/>            使用 ParentSeriesGroup 屬性存取父系列群組。<br/>            使用 ParentSeriesGroup.IsColorVaried 讀/寫 屬性變更值。<br/>            唯讀 **bool**。 |
| [`bubble_size_scale`](/slides/python-net/zh-hant/aspose.slides.charts/chartseries/bubble_size_scale/) | 指定氣泡圖的比例因子（可為預設大小的 0 到 300%）。<br/>            此屬性不僅屬於此系列，同時屬於父系列群組的所有系列 - 為相應群組屬性的投射。因此此屬性<br/>            為唯讀。<br/>            使用 ParentSeriesGroup 屬性存取父系列群組。<br/>            使用 ParentSeriesGroup.BubbleSizeScale 讀/寫 屬性變更值。 |
| [`slide`](/slides/python-net/zh-hant/aspose.slides.charts/chartseries/slide/) |  |
| [`presentation`](/slides/python-net/zh-hant/aspose.slides.charts/chartseries/presentation/) |  |

## 方法

| Method | Description |
| :- | :- |
| [`get_automatic_series_color(self)`](/slides/python-net/zh-hant/aspose.slides.charts/chartseries/get_automatic_series_color/#) | 傳回根據系列索引和圖表樣式自動產生的系列顏色。若 FillType 等於 NotDefined，則預設使用此顏色。 |

### 另請參閱
* 模組 [`aspose.slides.charts`](/slides/python-net/zh-hant/aspose.slides.charts)
* 程式庫 [`Aspose.Slides`](/slides/python-net)