---
title: ChartSeriesGroup class
second_title: Aspose.Slides 用於 Python via .NET API 參考
description: 
type: docs
url: /zh-hant/aspose.slides.charts/chartseriesgroup/
---
## ChartSeriesGroup 類別

表示系列的群組。

ChartSeriesGroup 類型公開以下成員：

## 屬性

| Property | Description |
| :- | :- |
| [`type`](/slides/python-net/zh-hant/aspose.slides.charts/chartseriesgroup/type/) | 傳回此系列群組的類型。<br/>            唯讀 [`CombinableSeriesTypesGroup`](/slides/python-net/zh-hant/aspose.slides.charts/combinableseriestypesgroup)。 |
| [`plot_on_second_axis`](/slides/python-net/zh-hant/aspose.slides.charts/chartseriesgroup/plot_on_second_axis/) | 指示此群組的系列是否繪製在第二軸上。<br/>            唯讀 **bool**。 |
| [`series`](/slides/python-net/zh-hant/aspose.slides.charts/chartseriesgroup/series/) | 傳回系列的集合。<br/>            唯讀 [`IChartSeriesReadonlyCollection`](/slides/python-net/zh-hant/aspose.slides.charts/ichartseriesreadonlycollection)。 |
| [`up_down_bars`](/slides/python-net/zh-hant/aspose.slides.charts/chartseriesgroup/up_down_bars/) | 提供對折線圖或股票圖的上/下棒的存取。<br/>            唯讀 [`IUpDownBarsManager`](/slides/python-net/zh-hant/aspose.slides.charts/iupdownbarsmanager)。 |
| [`gap_width`](/slides/python-net/zh-hant/aspose.slides.charts/chartseriesgroup/gap_width/) | 指定條形或柱狀叢之間的間距，以條形或柱狀寬度的百分比表示。<br/>            可讀寫 **int**。 |
| [`gap_depth`](/slides/python-net/zh-hant/aspose.slides.charts/chartseriesgroup/gap_depth/) | 傳回或設定資料系列在 3D 圖表中，標記寬度的百分比之間的距離。<br/>            可讀寫 **int**。 |
| [`first_slice_angle`](/slides/python-net/zh-hant/aspose.slides.charts/chartseriesgroup/first_slice_angle/) | 取得或設定第一個圓餅或甜甜圈圖切片的角度，<br/>            以度為單位（從上方順時針，0 到 360 度）。<br/>            可讀寫 **int**。 |
| [`doughnut_hole_size`](/slides/python-net/zh-hant/aspose.slides.charts/chartseriesgroup/doughnut_hole_size/) | 指定甜甜圈圖中洞的大小（可介於繪圖區大小的 0% 到 90% 之間）。<br/>            可讀寫 **int**。 |
| [`overlap`](/slides/python-net/zh-hant/aspose.slides.charts/chartseriesgroup/overlap/) | 指定條形和柱狀圖在 2-D 圖表上重疊的程度，以百分比表示（從 -100% 到 100%）。<br/>             - -100%：最大間距（條形完全分開）。<br/>             - 0%：條形並排放置，沒有重疊或間距。<br/>             - 100%：最大重疊（條形完全互相重疊）。<br/>             此屬性為可讀寫 **int**。 |
| [`second_pie_size`](/slides/python-net/zh-hant/aspose.slides.charts/chartseriesgroup/second_pie_size/) | 指定二次圓餅或條形於 pie-of-pie 圖或 bar-of-pie 圖中的大小，以第一個圓餅大小的百分比表示（可介於 5% 到 200% 之間）。<br/>            可讀寫 **int**。 |
| [`bubble_size_representation`](/slides/python-net/zh-hant/aspose.slides.charts/chartseriesgroup/bubble_size_representation/) | 指定氣泡圖上氣泡大小值的表示方式。<br/>            可讀寫 [`BubbleSizeRepresentationType`](/slides/python-net/zh-hant/aspose.slides.charts/bubblesizerepresentationtype)。 |
| [`pie_split_position`](/slides/python-net/zh-hant/aspose.slides.charts/chartseriesgroup/pie_split_position/) | 指定用於決定哪個資料點位於 pie-of-pie 或 bar-of-pie 圖的第二個圓餅或條形的值。<br/>            與 PieSplitBy 屬性一起使用。<br/>            可讀寫 **float**。 |
| [`pie_split_by`](/slides/python-net/zh-hant/aspose.slides.charts/chartseriesgroup/pie_split_by/) | 指定如何決定哪個資料點位於 pie-of-pie 或 bar-of-pie 圖的第二個圓餅或條形。<br/>            可讀寫 [`PieSplitType`](/slides/python-net/zh-hant/aspose.slides.charts/piesplittype)。 |
| [`is_color_varied`](/slides/python-net/zh-hant/aspose.slides.charts/chartseriesgroup/is_color_varied/) | 指定系列中的每個資料標記具有不同的顏色。<br/>            可讀寫 **bool**。 |
| [`has_series_lines`](/slides/python-net/zh-hant/aspose.slides.charts/chartseriesgroup/has_series_lines/) | 若圖表具有系列線則為 true。適用於堆疊條形圖和 OfPie 圖表。<br/>            可讀寫 **bool**。 |
| [`hi_low_lines_format`](/slides/python-net/zh-hant/aspose.slides.charts/chartseriesgroup/hi_low_lines_format/) | 指定 HiLowLines 格式。<br/>            HiLowLines 適用於 HiLowClose、OpenHiLowClose、VolumeHiLowClose 與 VolumeOpenHiLowClose 圖表類型。 |
| [`bubble_size_scale`](/slides/python-net/zh-hant/aspose.slides.charts/chartseriesgroup/bubble_size_scale/) | 指定氣泡圖的縮放係數（可介於預設大小的 0% 到 300% 之間）。<br/>            可讀寫 **int**。 |
| [`pie_split_custom_points`](/slides/python-net/zh-hant/aspose.slides.charts/chartseriesgroup/pie_split_custom_points/) | 具有自訂切分之 pie-of-pie 或 bar-of-pie 圖表的自訂切分資訊。<br/>            包含應在第二個圓餅或條形中繪製的資料點，於 pie-of-pie 或 <br/>            bar-of-pie 圖表中。<br/>            唯讀 [`PieSplitCustomPointCollection`](/slides/python-net/zh-hant/aspose.slides.charts/piesplitcustompointcollection)。 |
| [`chart`](/slides/python-net/zh-hant/aspose.slides.charts/chartseriesgroup/chart/) | 傳回父圖表。<br/>            唯讀 [`IChart`](/slides/python-net/zh-hant/aspose.slides.charts/ichart)。 |
| [`slide`](/slides/python-net/zh-hant/aspose.slides.charts/chartseriesgroup/slide/) |  |
| [`presentation`](/slides/python-net/zh-hant/aspose.slides.charts/chartseriesgroup/presentation/) |  |

取得指定索引處的元素。

## 索引子

| Name | Description |
| :- | :- |
| [`[index]`](/slides/python-net/zh-hant/aspose.slides.charts/chartseriesgroup/__getitem__/) |  |


### 備註

1）請參閱 ChartSeriesGroupCollection 類別與 CombinableSeriesTypesGroup 列舉的摘要與備註。  
2）系列群組包含一些對該群組中每個系列皆通用的系列屬性（「系列群組屬性」）。  
「系列群組屬性」在 ChartSeriesGroup 類別中為可讀寫。  
每個「系列群組屬性」在 ChartSeries 類別中可以有唯讀的投影。

### 另見
* 模組 [`aspose.slides.charts`](/slides/python-net/zh-hant/aspose.slides.charts)
* 函式庫 [`Aspose.Slides`](/slides/python-net)