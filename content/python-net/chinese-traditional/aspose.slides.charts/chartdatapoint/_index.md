---
title: ChartDataPoint class
second_title: Aspose.Slides for Python 透過 .NET API 參考
description: 
type: docs
url: /zh-hant/aspose.slides.charts/chartdatapoint/
---
## ChartDataPoint 類別

表示系列資料點。

ChartDataPoint 類型公開以下成員：

## 屬性

| 屬性 | 說明 |
| :- | :- |
| [`x_value`](/slides/python-net/zh-hant/aspose.slides.charts/chartdatapoint/x_value/) | XValue.<br/>            唯讀 [`IStringOrDoubleChartValue`](/slides/python-net/zh-hant/aspose.slides.charts/istringordoublechartvalue). |
| [`y_value`](/slides/python-net/zh-hant/aspose.slides.charts/chartdatapoint/y_value/) | YValue.<br/>            唯讀 [`IDoubleChartValue`](/slides/python-net/zh-hant/aspose.slides.charts/idoublechartvalue). |
| [`bubble_size`](/slides/python-net/zh-hant/aspose.slides.charts/chartdatapoint/bubble_size/) | BubbleSize.<br/>            唯讀 [`IDoubleChartValue`](/slides/python-net/zh-hant/aspose.slides.charts/idoublechartvalue). |
| [`value`](/slides/python-net/zh-hant/aspose.slides.charts/chartdatapoint/value/) | Value.<br/>            唯讀 [`IDoubleChartValue`](/slides/python-net/zh-hant/aspose.slides.charts/idoublechartvalue). |
| [`size_value`](/slides/python-net/zh-hant/aspose.slides.charts/chartdatapoint/size_value/) | 返回圖表資料點的大小值。<br/>            用於 Treemap 與 Sunburst 圖表。 <br/>            唯讀 [`IDoubleChartValue`](/slides/python-net/zh-hant/aspose.slides.charts/idoublechartvalue). |
| [`color_value`](/slides/python-net/zh-hant/aspose.slides.charts/chartdatapoint/color_value/) | 返回圖表資料點的顏色值。<br/>            用於 Map 圖表。 <br/>            唯讀 [`IDoubleChartValue`](/slides/python-net/zh-hant/aspose.slides.charts/idoublechartvalue). |
| [`error_bars_custom_values`](/slides/python-net/zh-hant/aspose.slides.charts/chartdatapoint/error_bars_custom_values/) | 在 Custom 值類型的情況下，表示系列誤差棒值。<br/>            唯讀 [`IErrorBarsCustomValues`](/slides/python-net/zh-hant/aspose.slides.charts/ierrorbarscustomvalues). |
| [`label`](/slides/python-net/zh-hant/aspose.slides.charts/chartdatapoint/label/) | Label.<br/>            唯讀 [`IDataLabel`](/slides/python-net/zh-hant/aspose.slides.charts/idatalabel). |
| [`is_bubble_3d`](/slides/python-net/zh-hant/aspose.slides.charts/chartdatapoint/is_bubble_3d/) | 指定氣泡套用 3-D 效果。<br/>            可讀寫 **bool**. |
| [`explosion`](/slides/python-net/zh-hant/aspose.slides.charts/chartdatapoint/explosion/) | 指定資料點從圓餅中心移動的距離。<br/>            可讀寫 **int**. |
| [`format`](/slides/python-net/zh-hant/aspose.slides.charts/chartdatapoint/format/) | 表示格式化屬性。<br/>            可讀寫 [`IFormat`](/slides/python-net/zh-hant/aspose.slides.charts/iformat). |
| [`marker`](/slides/python-net/zh-hant/aspose.slides.charts/chartdatapoint/marker/) | 指定資料標記。<br/>            唯讀 [`IMarker`](/slides/python-net/zh-hant/aspose.slides.charts/imarker). |
| [`set_as_total`](/slides/python-net/zh-hant/aspose.slides.charts/chartdatapoint/set_as_total/) | 將資料點設為總計。僅適用於 Waterfall 系列類型。 |
| [`related_legend_entry`](/slides/python-net/zh-hant/aspose.slides.charts/chartdatapoint/related_legend_entry/) | 對應圖例項目的屬性，當圖表類型為以下清單中的項目時：<br/>            ChartType.BarOfPie,<br/>            ChartType.ExplodedPie,<br/>            ChartType.ExplodedPie3D,<br/>            ChartType.Pie,<br/>            ChartType.Pie3D,<br/>            ChartType.PieOfPie.<br/>            唯讀 [`ILegendEntryProperties`](/slides/python-net/zh-hant/aspose.slides.charts/ilegendentryproperties). |
| [`data_point_levels`](/slides/python-net/zh-hant/aspose.slides.charts/chartdatapoint/data_point_levels/) | 返回資料點層級的容器。適用於 Treeamp 和 Sunburst 系列。<br/>            資料點層級索引從零開始. |
| [`index`](/slides/python-net/zh-hant/aspose.slides.charts/chartdatapoint/index/) |  |
| [`invert_if_negative`](/slides/python-net/zh-hant/aspose.slides.charts/chartdatapoint/invert_if_negative/) | 指定若值為負數，資料點應反轉其顏色。<br/>            可讀寫 **bool**. |
| [`actual_x`](/slides/python-net/zh-hant/aspose.slides.charts/chartdatapoint/actual_x/) | 指定圖表元素相對於圖表左上角的實際 x 位置（左）。<br/>            在取得實際值之前，先呼叫方法 IChart.ValidateChartLayout()。 <br/>            唯讀 **float**. |
| [`actual_y`](/slides/python-net/zh-hant/aspose.slides.charts/chartdatapoint/actual_y/) | 指定圖表元素相對於圖表左上角的實際上部位置。<br/>            在取得實際值之前，先呼叫方法 IChart.ValidateChartLayout()。 <br/>            唯讀 **float**. |
| [`actual_width`](/slides/python-net/zh-hant/aspose.slides.charts/chartdatapoint/actual_width/) | 指定圖表元素的實際寬度。先呼叫方法 IChart.ValidateChartLayout() 以取得實際值。 <br/>            唯讀 **float**. |
| [`actual_height`](/slides/python-net/zh-hant/aspose.slides.charts/chartdatapoint/actual_height/) | 指定圖表元素的實際高度。先呼叫方法 IChart.ValidateChartLayout() 以取得實際值。 <br/>            唯讀 **float**. |

## 方法

| 方法 | 說明 |
| :- | :- |
| [`remove(self)`](/slides/python-net/zh-hant/aspose.slides.charts/chartdatapoint/remove/#) | 從圖表系列中移除 DataPoint。 |
| [`get_automatic_data_point_color(self)`](/slides/python-net/zh-hant/aspose.slides.charts/chartdatapoint/get_automatic_data_point_color/#) | 根據系列索引、DataPoint 索引、ParentSeriesGroup.IsColorVaried 屬性和圖表樣式，返回資料點的自動顏色。<br/>            若 FillType 等於 NotDefined，則預設使用此顏色。 |

### 參見
* 模組 [`aspose.slides.charts`](/slides/python-net/zh-hant/aspose.slides.charts)
* library [`Aspose.Slides`](/slides/python-net)