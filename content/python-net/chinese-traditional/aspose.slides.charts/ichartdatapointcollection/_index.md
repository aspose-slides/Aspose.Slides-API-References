---
title: IChartDataPointCollection class
second_title: Aspose.Slides for Python via .NET API 參考
description: 
type: docs
url: /zh-hant/aspose.slides.charts/ichartdatapointcollection/
---
## IChartDataPointCollection 類別

表示系列資料點的集合。

IChartDataPointCollection 類型公開以下成員：

## 屬性

| 屬性 | 說明 |
| :- | :- |
| [`data_source_type_for_x_values`](/slides/python-net/zh-hant/aspose.slides.charts/ichartdatapointcollection/data_source_type_for_x_values/) | 指定在資料點 XValue 屬性物件中實際使用的為 AsCell、AsLiteralString 或 AsLiteralDouble 屬性。<br/>            換句話說，它指定 ChartDataPointEx.XValue.Data 屬性的值類型。<br/>            讀寫 [`DataSourceType`](/slides/python-net/zh-hant/aspose.slides.charts/datasourcetype). |
| [`data_source_type_for_y_values`](/slides/python-net/zh-hant/aspose.slides.charts/ichartdatapointcollection/data_source_type_for_y_values/) | 指定在資料點 YValue 屬性物件中實際使用的為 AsCell、AsLiteralString 或 AsLiteralDouble 屬性。<br/>            換句話說，它指定 ChartDataPointEx.YValue.Data 屬性的值類型。<br/>            讀寫 [`DataSourceType`](/slides/python-net/zh-hant/aspose.slides.charts/datasourcetype). |
| [`data_source_type_for_bubble_sizes`](/slides/python-net/zh-hant/aspose.slides.charts/ichartdatapointcollection/data_source_type_for_bubble_sizes/) | 指定在資料點 BubbleSize 屬性物件中實際使用的為 AsCell、AsLiteralString 或 AsLiteralDouble 屬性。<br/>            換句話說，它指定 ChartDataPointEx.BubbleSize.Data 屬性的值類型。<br/>            讀寫 [`DataSourceType`](/slides/python-net/zh-hant/aspose.slides.charts/datasourcetype). |
| [`data_source_type_for_values`](/slides/python-net/zh-hant/aspose.slides.charts/ichartdatapointcollection/data_source_type_for_values/) | 指定在資料點 Value 屬性物件中實際使用的為 AsCell、AsLiteralString 或 AsLiteralDouble 屬性。<br/>            換句話說，它指定 ChartDataPoint.Value.Data 屬性的值類型。<br/>            讀寫 [`DataSourceType`](/slides/python-net/zh-hant/aspose.slides.charts/datasourcetype). |
| [`data_source_type_for_error_bars_custom_values`](/slides/python-net/zh-hant/aspose.slides.charts/ichartdatapointcollection/data_source_type_for_error_bars_custom_values/) | 指定 ChartDataPoint.ErrorBarsCustomValues 屬性清單中值的類型。<br/>            唯讀 [`IDataSourceTypeForErrorBarsCustomValues`](/slides/python-net/zh-hant/aspose.slides.charts/idatasourcetypeforerrorbarscustomvalues). |

依索引 (此集合中的序號) 返回系列資料點。

## 索引子

| 名稱 | 說明 |
| :- | :- |
| [`[index]`](/slides/python-net/zh-hant/aspose.slides.charts/ichartdatapointcollection/__getitem__/) |  |

## 方法

| 方法 | 說明 |
| :- | :- |
| [`add_data_point_for_stock_series(self, value)`](/slides/python-net/zh-hant/aspose.slides.charts/ichartdatapointcollection/add_data_point_for_stock_series/#ichartdatacell) | 建立新的資料點並將其加入集合的末端。<br/>            適用於圖表類型 (chartType) 為 Stock 子類型之一的系列 (另請參閱 ChartTypeCharacterizer.IsChartTypeStock(ChartType) 方法)。 |
| [`add_data_point_for_stock_series(self, value)`](/slides/python-net/zh-hant/aspose.slides.charts/ichartdatapointcollection/add_data_point_for_stock_series/#float) | 建立新的資料點並將其加入集合的末端。<br/>            適用於圖表類型 (chartType) 為 Stock 子類型之一的系列 (另請參閱 ChartTypeCharacterizer.IsChartTypeStock(ChartType) 方法)。 |
| [`add_data_point_for_line_series(self, value)`](/slides/python-net/zh-hant/aspose.slides.charts/ichartdatapointcollection/add_data_point_for_line_series/#ichartdatacell) | 建立新的資料點並將其加入集合的末端。<br/>            適用於圖表類型為 Line 子類型之一的系列 (另請參閱 ChartTypeCharacterizer.IsChartTypeLine(ChartType) 方法)。 |
| [`add_data_point_for_line_series(self, value)`](/slides/python-net/zh-hant/aspose.slides.charts/ichartdatapointcollection/add_data_point_for_line_series/#float) | 建立新的資料點並將其加入集合的末端。<br/>            適用於圖表類型為 Line 子類型之一的系列 (另請參閱 ChartTypeCharacterizer.IsChartTypeLine(ChartType) 方法)。 |
| [`add_data_point_for_scatter_series(self, x_value, y_value)`](/slides/python-net/zh-hant/aspose.slides.charts/ichartdatapointcollection/add_data_point_for_scatter_series/#ichartdatacell-ichartdatacell) | 建立新的資料點並將其加入集合的末端。<br/>            適用於圖表類型為 Scatter 子類型之一的系列 (另請參閱 ChartTypeCharacterizer.IsChartTypeScatter(ChartType) 方法)。 |
| [`add_data_point_for_scatter_series(self, x_value, y_value)`](/slides/python-net/zh-hant/aspose.slides.charts/ichartdatapointcollection/add_data_point_for_scatter_series/#float-ichartdatacell) | 建立新的資料點並將其加入集合的末端。<br/>            適用於圖表類型為 Scatter 子類型之一的系列 (另請參閱 ChartTypeCharacterizer.IsChartTypeScatter(ChartType) 方法)。 |
| [`add_data_point_for_scatter_series(self, x_value, y_value)`](/slides/python-net/zh-hant/aspose.slides.charts/ichartdatapointcollection/add_data_point_for_scatter_series/#str-ichartdatacell) | 建立新的資料點並將其加入集合的末端。<br/>            適用於圖表類型為 Scatter 子類型之一的系列 (另請參閱 ChartTypeCharacterizer.IsChartTypeScatter(ChartType) 方法)。 |
| [`add_data_point_for_scatter_series(self, x_value, y_value)`](/slides/python-net/zh-hant/aspose.slides.charts/ichartdatapointcollection/add_data_point_for_scatter_series/#ichartdatacell-float) | 建立新的資料點並將其加入集合的末端。<br/>            適用於圖表類型為 Scatter 子類型之一的系列 (另請參閱 ChartTypeCharacterizer.IsChartTypeScatter(ChartType) 方法)。 |
| [`add_data_point_for_scatter_series(self, x_value, y_value)`](/slides/python-net/zh-hant/aspose.slides.charts/ichartdatapointcollection/add_data_point_for_scatter_series/#float-float) | 建立新的資料點並將其加入集合的末端。<br/>            適用於圖表類型為 Scatter 子類型之一的系列 (另請參閱 ChartTypeCharacterizer.IsChartTypeScatter(ChartType) 方法)。 |
| [`add_data_point_for_scatter_series(self, x_value, y_value)`](/slides/python-net/zh-hant/aspose.slides.charts/ichartdatapointcollection/add_data_point_for_scatter_series/#str-float) | 建立新的資料點並將其加入集合的末端。<br/>            適用於圖表類型為 Scatter 子類型之一的系列 (另請參閱 ChartTypeCharacterizer.IsChartTypeScatter(ChartType) 方法)。 |
| [`add_data_point_for_radar_series(self, value)`](/slides/python-net/zh-hant/aspose.slides.charts/ichartdatapointcollection/add_data_point_for_radar_series/#ichartdatacell) | 建立新的資料點並將其加入集合的末端。<br/>            適用於圖表類型為 Radar 子類型之一的系列 (另請參閱 ChartTypeCharacterizer.IsChartTypeRadar(ChartType) 方法)。 |
| [`add_data_point_for_radar_series(self, value)`](/slides/python-net/zh-hant/aspose.slides.charts/ichartdatapointcollection/add_data_point_for_radar_series/#float) | 建立新的資料點並將其加入集合的末端。<br/>            適用於圖表類型為 Radar 子類型之一的系列 (另請參閱 ChartTypeCharacterizer.IsChartTypeRadar(ChartType) 方法)。 |
| [`add_data_point_for_bar_series(self, value)`](/slides/python-net/zh-hant/aspose.slides.charts/ichartdatapointcollection/add_data_point_for_bar_series/#ichartdatacell) | 建立新的資料點並將其加入集合的末端。<br/>            適用於圖表類型為 Column 或 Bar 子類型之一的系列 (另請參閱 ChartTypeCharacterizer.IsChartTypeColumn(ChartType) 以及 ChartTypeCharacterizer.IsChartTypeBar(ChartType) 方法)。 |
| [`add_data_point_for_bar_series(self, value)`](/slides/python-net/zh-hant/aspose.slides.charts/ichartdatapointcollection/add_data_point_for_bar_series/#float) | 建立新的資料點並將其加入集合的末端。<br/>            適用於圖表類型為 Column 或 Bar 子類型之一的系列 (另請參閱 ChartTypeCharacterizer.IsChartTypeColumn(ChartType) 以及 ChartTypeCharacterizer.IsChartTypeBar(ChartType) 方法)。 |
| [`add_data_point_for_area_series(self, value)`](/slides/python-net/zh-hant/aspose.slides.charts/ichartdatapointcollection/add_data_point_for_area_series/#ichartdatacell) | 建立新的資料點並將其加入集合的末端。<br/>            適用於圖表類型為 Area 子類型之一的系列 (另請參閱 ChartTypeCharacterizer.IsChartTypeArea(ChartType) 方法)。 |
| [`add_data_point_for_area_series(self, value)`](/slides/python-net/zh-hant/aspose.slides.charts/ichartdatapointcollection/add_data_point_for_area_series/#float) | 建立新的資料點並將其加入集合的末端。<br/>            適用於圖表類型為 Area 子類型之一的系列 (另請參閱 ChartTypeCharacterizer.IsChartTypeArea(ChartType) 方法)。 |
| [`add_data_point_for_pie_series(self, value)`](/slides/python-net/zh-hant/aspose.slides.charts/ichartdatapointcollection/add_data_point_for_pie_series/#ichartdatacell) | 建立新的資料點並將其加入集合的末端。<br/>            適用於圖表類型為 Pie 子類型之一的系列 (另請參閱 ChartTypeCharacterizer.IsChartTypePie(ChartType) 方法)。 |
| [`add_data_point_for_pie_series(self, value)`](/slides/python-net/zh-hant/aspose.slides.charts/ichartdatapointcollection/add_data_point_for_pie_series/#float) | 建立新的資料點並將其加入集合的末端。<br/>            適用於圖表類型為 Pie 子類型之一的系列 (另請參閱 ChartTypeCharacterizer.IsChartTypePie(ChartType) 方法)。 |
| [`add_data_point_for_doughnut_series(self, value)`](/slides/python-net/zh-hant/aspose.slides.charts/ichartdatapointcollection/add_data_point_for_doughnut_series/#ichartdatacell) | 建立新的資料點並將其加入集合的末端。<br/>            適用於圖表類型為 Doughnut 子類型之一的系列 (另請參閱 ChartTypeCharacterizer.IsChartTypeDoughnut(ChartType) 方法)。 |
| [`add_data_point_for_doughnut_series(self, value)`](/slides/python-net/zh-hant/aspose.slides.charts/ichartdatapointcollection/add_data_point_for_doughnut_series/#float) | 建立新的資料點並將其加入集合的末端。<br/>            適用於圖表類型為 Doughnut 子類型之一的系列 (另請參閱 ChartTypeCharacterizer.IsChartTypeDoughnut(ChartType) 方法)。 |
| [`add_data_point_for_bubble_series(self, x_value, y_value, bubble_size)`](/slides/python-net/zh-hant/aspose.slides.charts/ichartdatapointcollection/add_data_point_for_bubble_series/#ichartdatacell-ichartdatacell-ichartdatacell) | 建立新的資料點並將其加入集合的末端。<br/>            適用於圖表類型為 Bubble 子類型之一的系列 (另請參閱 ChartTypeCharacterizer.IsChartTypeBubble(ChartType) 方法)。 |
| [`add_data_point_for_bubble_series(self, x_value, y_value, bubble_size)`](/slides/python-net/zh-hant/aspose.slides.charts/ichartdatapointcollection/add_data_point_for_bubble_series/#float-ichartdatacell-ichartdatacell) | 建立新的資料點並將其加入集合的末端。<br/>            適用於圖表類型為 Bubble 子類型之一的系列 (另請參閱 ChartTypeCharacterizer.IsChartTypeBubble(ChartType) 方法)。 |
| [`add_data_point_for_bubble_series(self, x_value, y_value, bubble_size)`](/slides/python-net/zh-hant/aspose.slides.charts/ichartdatapointcollection/add_data_point_for_bubble_series/#str-ichartdatacell-ichartdatacell) | 建立新的資料點並將其加入集合的末端。<br/>            適用於圖表類型為 Bubble 子類型之一的系列 (另請參閱 ChartTypeCharacterizer.IsChartTypeBubble(ChartType) 方法)。 |
| [`add_data_point_for_bubble_series(self, x_value, y_value, bubble_size)`](/slides/python-net/zh-hant/aspose.slides.charts/ichartdatapointcollection/add_data_point_for_bubble_series/#ichartdatacell-float-ichartdatacell) | 建立新的資料點並將其加入集合的末端。<br/>            適用於圖表類型為 Bubble 子類型之一的系列 (另請參閱 ChartTypeCharacterizer.IsChartTypeBubble(ChartType) 方法)。 |
| [`add_data_point_for_bubble_series(self, x_value, y_value, bubble_size)`](/slides/python-net/zh-hant/aspose.slides.charts/ichartdatapointcollection/add_data_point_for_bubble_series/#float-float-ichartdatacell) | 建立新的資料點並將其加入集合的末端。<br/>            適用於圖表類型為 Bubble 子類型之一的系列 (另請參閱 ChartTypeCharacterizer.IsChartTypeBubble(ChartType) 方法)。 |
| [`add_data_point_for_bubble_series(self, x_value, y_value, bubble_size)`](/slides/python-net/zh-hant/aspose.slides.charts/ichartdatapointcollection/add_data_point_for_bubble_series/#str-float-ichartdatacell) | 建立新的資料點並將其加入集合的末端。<br/>            適用於圖表類型為 Bubble 子類型之一的系列 (另請參閱 ChartTypeCharacterizer.IsChartTypeBubble(ChartType) 方法)。 |
| [`add_data_point_for_bubble_series(self, x_value, y_value, bubble_size)`](/slides/python-net/zh-hant/aspose.slides.charts/ichartdatapointcollection/add_data_point_for_bubble_series/#ichartdatacell-ichartdatacell-float) | 建立新的資料點並將其加入集合的末端。<br/>            適用於圖表類型為 Bubble 子類型之一的系列 (另請參閱 ChartTypeCharacterizer.IsChartTypeBubble(ChartType) 方法)。 |
| [`add_data_point_for_bubble_series(self, x_value, y_value, bubble_size)`](/slides/python-net/zh-hant/aspose.slides.charts/ichartdatapointcollection/add_data_point_for_bubble_series/#float-ichartdatacell-float) | 建立新的資料點並將其加入集合的末端。<br/>            適用於圖表類型為 Bubble 子類型之一的系列 (另請參閱 ChartTypeCharacterizer.IsChartTypeBubble(ChartType) 方法)。 |
| [`add_data_point_for_bubble_series(self, x_value, y_value, bubble_size)`](/slides/python-net/zh-hant/aspose.slides.charts/ichartdatapointcollection/add_data_point_for_bubble_series/#str-ichartdatacell-float) | 建立新的資料點並將其加入集合的末端。<br/>            適用於圖表類型為 Bubble 子類型之一的系列 (另請參閱 ChartTypeCharacterizer.IsChartTypeBubble(ChartType) 方法)。 |
| [`add_data_point_for_bubble_series(self, x_value, y_value, bubble_size)`](/slides/python-net/zh-hant/aspose.slides.charts/ichartdatapointcollection/add_data_point_for_bubble_series/#ichartdatacell-float-float) | 建立新的資料點並將其加入集合的末端。<br/>            適用於圖表類型為 Bubble 子類型之一的系列 (另請參閱 ChartTypeCharacterizer.IsChartTypeBubble(ChartType) 方法)。 |
| [`add_data_point_for_bubble_series(self, x_value, y_value, bubble_size)`](/slides/python-net/zh-hant/aspose.slides.charts/ichartdatapointcollection/add_data_point_for_bubble_series/#float-float-float) | 建立新的資料點並將其加入集合的末端。<br/>            適用於圖表類型為 Bubble 子類型之一的系列 (另請參閱 ChartTypeCharacterizer.IsChartTypeBubble(ChartType) 方法)。 |
| [`add_data_point_for_bubble_series(self, x_value, y_value, bubble_size)`](/slides/python-net/zh-hant/aspose.slides.charts/ichartdatapointcollection/add_data_point_for_bubble_series/#str-float-float) | 建立新的資料點並將其加入集合的末端。<br/>            適用於圖表類型為 Bubble 子類型之一的系列 (另請參閱 ChartTypeCharacterizer.IsChartTypeBubble(ChartType) 方法)。 |
| [`add_data_point_for_surface_series(self, value)`](/slides/python-net/zh-hant/aspose.slides.charts/ichartdatapointcollection/add_data_point_for_surface_series/#ichartdatacell) | 建立新的資料點並將其加入集合的末端。<br/>            適用於圖表類型為 Surface 子類型之一的系列 (另請參閱 ChartTypeCharacterizer.IsChartTypeSurface(ChartType) 方法)。 |
| [`add_data_point_for_surface_series(self, value)`](/slides/python-net/zh-hant/aspose.slides.charts/ichartdatapointcollection/add_data_point_for_surface_series/#float) | 建立新的資料點並將其加入集合的末端。<br/>            適用於圖表類型為 Surface 子類型之一的系列 (另請參閱 ChartTypeCharacterizer.IsChartTypeSurface(ChartType) 方法)。 |
| [`get_or_create_data_point_by_idx(self, index)`](/slides/python-net/zh-hant/aspose.slides.charts/ichartdatapointcollection/get_or_create_data_point_by_idx/#int) | 如果集合已經包含索引為 `index` 的資料點，則返回該資料點。<br/>            如果集合中不包含索引為 `index`==N 的資料點<br/>            (當此集合中的資料點數量小於或等於 N 時)<br/>            則會新增缺少的資料點並返回最後一個 (即請求的索引)。<br/>            例如，集合索引為 {0, 1, 2}，請求的索引為 5。<br/>            此時方法會新增缺少的資料點：{0, 1, 2, 3, 4, 5}，並返回索引為 5 的資料點。 |
| [`add_data_point_for_sunburst_series(self, size_value)`](/slides/python-net/zh-hant/aspose.slides.charts/ichartdatapointcollection/add_data_point_for_sunburst_series/#ichartdatacell) | 建立新的資料點並將其加入集合的末端。<br/>            適用於圖表類型為 Sunburst 的系列。 |
| [`add_data_point_for_waterfall_series(self, value)`](/slides/python-net/zh-hant/aspose.slides.charts/ichartdatapointcollection/add_data_point_for_waterfall_series/#ichartdatacell) | 建立新的資料點並將其加入集合的末端。<br/>            適用於圖表類型為 Waterfall 的系列。 |
| [`add_data_point_for_box_and_whisker_series(self, value)`](/slides/python-net/zh-hant/aspose.slides.charts/ichartdatapointcollection/add_data_point_for_box_and_whisker_series/#ichartdatacell) | 建立新的資料點並將其加入集合的末端。<br/>            適用於圖表類型為 BoxAndWhisker 的系列。 |
| [`add_data_point_for_treemap_series(self, size_value)`](/slides/python-net/zh-hant/aspose.slides.charts/ichartdatapointcollection/add_data_point_for_treemap_series/#ichartdatacell) | 建立新的資料點並將其加入集合的末端。<br/>            適用於圖表類型為 Treemap 的系列。 |
| [`add_data_point_for_histogram_series(self, value)`](/slides/python-net/zh-hant/aspose.slides.charts/ichartdatapointcollection/add_data_point_for_histogram_series/#ichartdatacell) | 建立新的資料點並將其加入集合的末端。<br/>            適用於圖表類型為 Histogram 的系列。 |
| [`add_data_point_for_funnel_series(self, value)`](/slides/python-net/zh-hant/aspose.slides.charts/ichartdatapointcollection/add_data_point_for_funnel_series/#ichartdatacell) | 建立新的資料點並將其加入集合的末端。<br/>            適用於圖表類型為 Funnel 的系列。 |
| [`add_data_point_for_map_series(self, value)`](/slides/python-net/zh-hant/aspose.slides.charts/ichartdatapointcollection/add_data_point_for_map_series/#ichartdatacell) | 建立新的資料點並將其加入集合的末端。<br/>             適用於圖表類型為 Map 的系列。 |
| [`clear(self)`](/slides/python-net/zh-hant/aspose.slides.charts/ichartdatapointcollection/clear/#) | 移除集合中的全部元素。 |
| [`remove(self, value)`](/slides/python-net/zh-hant/aspose.slides.charts/ichartdatapointcollection/remove/#ichartdatapoint) | 移除指定的值。 |
| [`remove_at(self, index)`](/slides/python-net/zh-hant/aspose.slides.charts/ichartdatapointcollection/remove_at/#int) | 移除指定索引處的元素。 |

### 另請參閱
* 模組 [`aspose.slides.charts`](/slides/python-net/zh-hant/aspose.slides.charts)
* 函式庫 [`Aspose.Slides`](/slides/python-net)