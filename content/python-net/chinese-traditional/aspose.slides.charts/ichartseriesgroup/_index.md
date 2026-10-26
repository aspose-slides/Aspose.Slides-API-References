---
title: IChartSeriesGroup class
second_title: Aspose.Slides for Python via .NET API 參考
description: 
type: docs
url: /zh-hant/aspose.slides.charts/ichartseriesgroup/
---
## IChartSeriesGroup 類別

表示系列的群組。

IChartSeriesGroup 類型公開以下成員：

## 屬性

| Property | Description |
| :- | :- |
| [`type`](/slides/python-net/zh-hant/aspose.slides.charts/ichartseriesgroup/type/) | 傳回此系列群組的類型。<br/>            唯讀 [`CombinableSeriesTypesGroup`](/slides/python-net/zh-hant/aspose.slides.charts/combinableseriestypesgroup)。 |
| [`plot_on_second_axis`](/slides/python-net/zh-hant/aspose.slides.charts/ichartseriesgroup/plot_on_second_axis/) | 指示此群組的系列是否繪製於次要座標軸上。<br/>            唯讀 **bool**。 |
| [`series`](/slides/python-net/zh-hant/aspose.slides.charts/ichartseriesgroup/series/) | 傳回圖表系列的唯讀集合。<br/>            唯讀 [`IChartSeriesReadonlyCollection`](/slides/python-net/zh-hant/aspose.slides.charts/ichartseriesreadonlycollection)。 |
| [`up_down_bars`](/slides/python-net/zh-hant/aspose.slides.charts/ichartseriesgroup/up_down_bars/) | 提供對折線圖或股票圖的上/下棒的存取。<br/>            唯讀 [`IUpDownBarsManager`](/slides/python-net/zh-hant/aspose.slides.charts/iupdownbarsmanager)。 |
| [`gap_width`](/slides/python-net/zh-hant/aspose.slides.charts/ichartseriesgroup/gap_width/) | 指定條形或柱形叢集之間的間距，以條形或柱形寬度的百分比表示。<br/>            讀寫 **int**。 |
| [`gap_depth`](/slides/python-net/zh-hant/aspose.slides.charts/ichartseriesgroup/gap_depth/) | 傳回或設定在 3D 圖表中資料系列之間，以標記寬度的百分比表示的距離。<br/>            讀寫 **int**。 |
| [`first_slice_angle`](/slides/python-net/zh-hant/aspose.slides.charts/ichartseriesgroup/first_slice_angle/) | 取得或設定第一個圓餅圖或甜甜圈圖切片的角度，<br/>            單位為度 (從上方順時針，0 至 360 度)。<br/>            讀寫 **int**。 |
| [`is_color_varied`](/slides/python-net/zh-hant/aspose.slides.charts/ichartseriesgroup/is_color_varied/) | 指定系列中的每個資料標記具有不同的顏色。<br/>            讀寫 **bool**。 |
| [`has_series_lines`](/slides/python-net/zh-hant/aspose.slides.charts/ichartseriesgroup/has_series_lines/) | 若圖表具有系列線則為 True。適用於堆疊條形圖和 OfPie 圖表。<br/>            讀寫 **bool**。 |
| [`overlap`](/slides/python-net/zh-hant/aspose.slides.charts/ichartseriesgroup/overlap/) | 指定 2-D 圖表中條形與柱形的重疊比例，以百分比表示（從 -100% 到 100%）。<br/>             - -100%：最大間距（條形完全分開）。<br/>             - 0%：條形並排放置，無重疊或間距。<br/>             - 100%：最大重疊（條形完全彼此重疊）。<br/>             此屬性為讀寫 **int**。 |
| [`second_pie_size`](/slides/python-net/zh-hant/aspose.slides.charts/ichartseriesgroup/second_pie_size/) | 指定 pie-of-pie 圖或 bar-of-pie 圖中第二個圓餅或條形的大小，以第一個圓餅的大小百分比表示（可介於 5% 到 200% 之間）。<br/>            讀寫 **int**。 |
| [`pie_split_position`](/slides/python-net/zh-hant/aspose.slides.charts/ichartseriesgroup/pie_split_position/) | 指定用於判斷哪些資料點位於 pie-of-pie 或 bar-of-pie 圖的第二個圓餅或條形的值。<br/>            與 PieSplitBy 屬性一起使用。<br/>            讀寫 **float**。 |
| [`pie_split_by`](/slides/python-net/zh-hant/aspose.slides.charts/ichartseriesgroup/pie_split_by/) | 指定如何判斷哪些資料點位於 pie-of-pie 或 bar-of-pie 圖的第二個圓餅或條形。<br/>            讀寫 [`PieSplitType`](/slides/python-net/zh-hant/aspose.slides.charts/piesplittype)。 |
| [`pie_split_custom_points`](/slides/python-net/zh-hant/aspose.slides.charts/ichartseriesgroup/pie_split_custom_points/) | 具有自訂分割的 pie-of-pie 或 bar-of-pie 圖的自訂分割資訊。<br/>            包含應在 pie-of-pie 或 <br/>            bar-of-pie 圖中繪製於第二個圓餅或條形的資料點。<br/>            唯讀 [`IPieSplitCustomPointCollection`](/slides/python-net/zh-hant/aspose.slides.charts/ipiesplitcustompointcollection)。 |
| [`doughnut_hole_size`](/slides/python-net/zh-hant/aspose.slides.charts/ichartseriesgroup/doughnut_hole_size/) | 指定甜甜圈圖中孔的大小（可介於繪圖區大小的 10% 到 90% 之間）。<br/>            讀寫 **int**。 |
| [`bubble_size_scale`](/slides/python-net/zh-hant/aspose.slides.charts/ichartseriesgroup/bubble_size_scale/) | 指定氣泡圖的比例因子（可介於預設大小的 0% 到 300% 之間）。<br/>            讀寫 **int**。 |
| [`hi_low_lines_format`](/slides/python-net/zh-hant/aspose.slides.charts/ichartseriesgroup/hi_low_lines_format/) | 指定 HiLowLines 格式。<br/>            HiLowLines 套用於 HiLowClose、OpenHiLowClose、VolumeHiLowClose 與 VolumeOpenHiLowClose 圖表類型。 |
| [`bubble_size_representation`](/slides/python-net/zh-hant/aspose.slides.charts/ichartseriesgroup/bubble_size_representation/) | 指定氣泡圖上氣泡大小值的表示方式。<br/>            讀寫 [`BubbleSizeRepresentationType`](/slides/python-net/zh-hant/aspose.slides.charts/bubblesizerepresentationtype)。 |
| [`chart`](/slides/python-net/zh-hant/aspose.slides.charts/ichartseriesgroup/chart/) |  |
| [`slide`](/slides/python-net/zh-hant/aspose.slides.charts/ichartseriesgroup/slide/) |  |
| [`presentation`](/slides/python-net/zh-hant/aspose.slides.charts/ichartseriesgroup/presentation/) |  |

取得指定索引處的元素。

## 索引子

| Name | Description |
| :- | :- |
| [`[index]`](/slides/python-net/zh-hant/aspose.slides.charts/ichartseriesgroup/__getitem__/) |  |


### 備註

1) 請參閱 ChartSeriesGroupCollection 類別與 CombinableSeriesTypesGroup enum 的摘要與備註。  
2) 系列群組包含某些對每個群組內系列共通的系列屬性（「series group properties」）。「Series group properties」在 ChartSeriesGroup 類別中為讀寫。每個「series group properties」在 ChartSeries 類別中可以有唯讀的投影。

### 另請參閱
* 模組 [`aspose.slides.charts`](/slides/python-net/zh-hant/aspose.slides.charts)
* 函式庫 [`Aspose.Slides`](/slides/python-net)