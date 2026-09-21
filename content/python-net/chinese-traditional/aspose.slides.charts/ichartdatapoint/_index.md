---
title: IChartDataPoint class
second_title: Aspose.Slides for Python via .NET API 參考
description: 
type: docs
url: /zh-hant/aspose.slides.charts/ichartdatapoint/
---
## IChartDataPoint 類別

表示系列資料點。

IChartDataPoint 類型公開以下成員：

## 屬性

| Property | Description |
| :- | :- |
| [`x_value`](/slides/python-net/zh-hant/aspose.slides.charts/ichartdatapoint/x_value/) | 傳回圖表資料點的 x 值。<br/>            只讀 [`IStringOrDoubleChartValue`](/slides/python-net/zh-hant/aspose.slides.charts/istringordoublechartvalue). |
| [`y_value`](/slides/python-net/zh-hant/aspose.slides.charts/ichartdatapoint/y_value/) | 傳回圖表資料點的 y 值。<br/>            只讀 [`IDoubleChartValue`](/slides/python-net/zh-hant/aspose.slides.charts/idoublechartvalue). |
| [`bubble_size`](/slides/python-net/zh-hant/aspose.slides.charts/ichartdatapoint/bubble_size/) | 傳回圖表資料點的氣泡大小。<br/>            只讀 [`IDoubleChartValue`](/slides/python-net/zh-hant/aspose.slides.charts/idoublechartvalue). |
| [`value`](/slides/python-net/zh-hant/aspose.slides.charts/ichartdatapoint/value/) | 傳回圖表資料點的值。<br/>            只讀 [`IDoubleChartValue`](/slides/python-net/zh-hant/aspose.slides.charts/idoublechartvalue). |
| [`size_value`](/slides/python-net/zh-hant/aspose.slides.charts/ichartdatapoint/size_value/) | 傳回圖表資料點的大小值。<br/>            用於 Treemap 和 Sunburst 圖表。 <br/>            只讀 [`IDoubleChartValue`](/slides/python-net/zh-hant/aspose.slides.charts/idoublechartvalue). |
| [`color_value`](/slides/python-net/zh-hant/aspose.slides.charts/ichartdatapoint/color_value/) | 傳回圖表資料點的顏色值。<br/>            用於 Map 圖表。 <br/>            只讀 [`IDoubleChartValue`](/slides/python-net/zh-hant/aspose.slides.charts/idoublechartvalue). |
| [`error_bars_custom_values`](/slides/python-net/zh-hant/aspose.slides.charts/ichartdatapoint/error_bars_custom_values/) | 代表自訂值類型的系列誤差棒值。<br/>            只讀 [`IErrorBarsCustomValues`](/slides/python-net/zh-hant/aspose.slides.charts/ierrorbarscustomvalues). |
| [`label`](/slides/python-net/zh-hant/aspose.slides.charts/ichartdatapoint/label/) | 代表圖表資料點的標籤。<br/>            只讀 [`IDataLabel`](/slides/python-net/zh-hant/aspose.slides.charts/idatalabel). |
| [`is_bubble_3d`](/slides/python-net/zh-hant/aspose.slides.charts/ichartdatapoint/is_bubble_3d/) | 指定氣泡是否套用 3-D 效果。<br/>            可讀寫 **bool**. |
| [`explosion`](/slides/python-net/zh-hant/aspose.slides.charts/ichartdatapoint/explosion/) | 指定資料點相對於餅圖中心的位移量。<br/>            可讀寫 **int**. |
| [`format`](/slides/python-net/zh-hant/aspose.slides.charts/ichartdatapoint/format/) | 代表格式設定屬性。<br/>            可讀寫 [`IFormat`](/slides/python-net/zh-hant/aspose.slides.charts/iformat). |
| [`marker`](/slides/python-net/zh-hant/aspose.slides.charts/ichartdatapoint/marker/) | 指定資料標記。<br/>            只讀 [`IMarker`](/slides/python-net/zh-hant/aspose.slides.charts/imarker). |
| [`related_legend_entry`](/slides/python-net/zh-hant/aspose.slides.charts/ichartdatapoint/related_legend_entry/) | 在以下圖表類型中對應圖例項目的屬性：<br/>            ChartType.BarOfPie,<br/>            ChartType.ExplodedPie,<br/>            ChartType.ExplodedPie3D,<br/>            ChartType.Pie,<br/>            ChartType.Pie3D,<br/>            ChartType.PieOfPie.<br/>            只讀 [`ILegendEntryProperties`](/slides/python-net/zh-hant/aspose.slides.charts/ilegendentryproperties). |
| [`set_as_total`](/slides/python-net/zh-hant/aspose.slides.charts/ichartdatapoint/set_as_total/) | 將資料點設為總計。僅適用於 Waterfall 系列類型。 |
| [`invert_if_negative`](/slides/python-net/zh-hant/aspose.slides.charts/ichartdatapoint/invert_if_negative/) | 指定資料點在值為負時是否反轉其顏色。<br/>            可讀寫 **bool**. |
| [`data_point_levels`](/slides/python-net/zh-hant/aspose.slides.charts/ichartdatapoint/data_point_levels/) | 傳回資料點層級的容器。適用於 Treeamp 和 Sunburst 系列。<br/>            資料點層級索引從零開始。 |
| [`index`](/slides/python-net/zh-hant/aspose.slides.charts/ichartdatapoint/index/) | 決定此資料點適用於父層子集合中的哪一個。<br/>            只讀 **int**. |
| [`actual_x`](/slides/python-net/zh-hant/aspose.slides.charts/ichartdatapoint/actual_x/) |  |
| [`actual_y`](/slides/python-net/zh-hant/aspose.slides.charts/ichartdatapoint/actual_y/) |  |
| [`actual_width`](/slides/python-net/zh-hant/aspose.slides.charts/ichartdatapoint/actual_width/) |  |
| [`actual_height`](/slides/python-net/zh-hant/aspose.slides.charts/ichartdatapoint/actual_height/) |  |

## 方法

| Method | Description |
| :- | :- |
| [`remove(self)`](/slides/python-net/zh-hant/aspose.slides.charts/ichartdatapoint/remove/#) | 從圖表系列中移除 DataPoint。 |
| [`get_automatic_data_point_color(self)`](/slides/python-net/zh-hant/aspose.slides.charts/ichartdatapoint/get_automatic_data_point_color/#) | 根據系列索引、資料點索引、ParentSeriesGroup.IsColorVaried 屬性和圖表樣式返回資料點的自動顏色。<br/>            若 FillType 等於 NotDefined，則預設使用此顏色。 |

### 另見
* 模組 [`aspose.slides.charts`](/slides/python-net/zh-hant/aspose.slides.charts)
* 函式庫 [`Aspose.Slides`](/slides/python-net)