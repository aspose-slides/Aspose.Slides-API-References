---
title: ChartSeriesGroup class
second_title: Aspose.Slides for Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides.charts/chartseriesgroup/
---
## ChartSeriesGroup 類別

代表一組系列。

ChartSeriesGroup 類型公開以下成員：

## 屬性

| 屬性 | 說明 |
| :- | :- |
| [`type`](/slides/python-net/zh-hant/aspose.slides.charts/chartseriesgroup/type/) | 返回此系列組的型別。<br/>            唯讀 [`CombinableSeriesTypesGroup`](/slides/python-net/zh-hant/aspose.slides.charts/combinableseriestypesgroup). |
| [`plot_on_second_axis`](/slides/python-net/zh-hant/aspose.slides.charts/chartseriesgroup/plot_on_second_axis/) | 指示此組的系列是否繪製在次要坐標軸上。<br/>            唯讀 **bool**. |
| [`series`](/slides/python-net/zh-hant/aspose.slides.charts/chartseriesgroup/series/) | 返回系列的集合。<br/>            唯讀 [`IChartSeriesReadonlyCollection`](/slides/python-net/zh-hant/aspose.slides.charts/ichartseriesreadonlycollection). |
| [`up_down_bars`](/slides/python-net/zh-hant/aspose.slides.charts/chartseriesgroup/up_down_bars/) | 提供對折線或股票圖的上/下棒的存取。<br/>            唯讀 [`IUpDownBarsManager`](/slides/python-net/zh-hant/aspose.slides.charts/iupdownbarsmanager). |
| [`gap_width`](/slides/python-net/zh-hant/aspose.slides.charts/chartseriesgroup/gap_width/) | 取得或設定長條或柱狀叢集之間的間距，作為長條或柱狀寬度的百分比。<br/>            值必須介於 0 到 500 之間。<br/>            可讀寫 **int**. |
| [`gap_depth`](/slides/python-net/zh-hant/aspose.slides.charts/chartseriesgroup/gap_depth/) | 取得或設定 3D 圖表中資料系列之間的距離，作為標記寬度的百分比。<br/>            值必須介於 0 到 500 之間。<br/>            可讀寫 **int**. |
| [`first_slice_angle`](/slides/python-net/zh-hant/aspose.slides.charts/chartseriesgroup/first_slice_angle/) | 取得或設定第一個圓餅或甜甜圈圖切片的角度，<br/>            以度數表示（順時針從上方，0 到 360 度）。<br/>            可讀寫 **int**. |
| [`doughnut_hole_size`](/slides/python-net/zh-hant/aspose.slides.charts/chartseriesgroup/doughnut_hole_size/) | 指定甜甜圈圖中孔的大小（可介於繪圖區大小的 0% 到 90% 之間）。<br/>            可讀寫 **int**. |
| [`overlap`](/slides/python-net/zh-hant/aspose.slides.charts/chartseriesgroup/overlap/) | 指定在二維圖表中長條和柱狀的重疊程度，以百分比表示（從 -100% 到 100%）。<br/>             - -100%：最大間距（長條完全分離）。<br/>             - 0%：長條並排放置，沒有重疊或間距。<br/>             - 100%：最大重疊（長條彼此完全重疊）。<br/>             此屬性為可讀寫 **int**. |
| [`second_pie_size`](/slides/python-net/zh-hant/aspose.slides.charts/chartseriesgroup/second_pie_size/) | 指定二層圓餅圖或條形-圓餅圖的第二個圓餅或條形的大小，作為第一個圓餅大小的百分比（可<br/>            介於 5% 到 200% 之間）。<br/>            可讀寫 **int**. |
| [`bubble_size_representation`](/slides/python-net/zh-hant/aspose.slides.charts/chartseriesgroup/bubble_size_representation/) | 指定在泡泡圖上泡泡大小值的表示方式。<br/>            可讀寫 [`BubbleSizeRepresentationType`](/slides/python-net/zh-hant/aspose.slides.charts/bubblesizerepresentationtype). |
| [`pie_split_position`](/slides/python-net/zh-hant/aspose.slides.charts/chartseriesgroup/pie_split_position/) | 指定用於判斷哪些資料點位於二層圓餅圖或條形-圓餅圖第二個圓餅或條形的值。<br/>            與 PieSplitBy 屬性一起使用。<br/>            可讀寫 **float**. |
| [`pie_split_by`](/slides/python-net/zh-hant/aspose.slides.charts/chartseriesgroup/pie_split_by/) | 指定如何判斷哪些資料點位於二層圓餅圖或條形-圓餅圖的第二個圓餅或條形。<br/>            可讀寫 [`PieSplitType`](/slides/python-net/zh-hant/aspose.slides.charts/piesplittype). |
| [`is_color_varied`](/slides/python-net/zh-hant/aspose.slides.charts/chartseriesgroup/is_color_varied/) | 指定系列中的每個資料標記都有不同的顏色。<br/>            可讀寫 **bool**. |
| [`has_series_lines`](/slides/python-net/zh-hant/aspose.slides.charts/chartseriesgroup/has_series_lines/) | 如果圖表具有系列線則為 True。適用於堆疊長條圖和 OfPie 圖表。<br/>            可讀寫 **bool**. |
| [`hi_low_lines_format`](/slides/python-net/zh-hant/aspose.slides.charts/chartseriesgroup/hi_low_lines_format/) | 指定 HiLowLines 格式。<br/>            HiLowLines 應用於 HiLowClose、OpenHiLowClose、VolumeHiLowClose 和 VolumeOpenHiLowClose 圖表類型. |
| [`bubble_size_scale`](/slides/python-net/zh-hant/aspose.slides.charts/chartseriesgroup/bubble_size_scale/) | 指定泡泡圖的比例因子（可<br/>            介於預設大小的 0% 到 300% 之間）。<br/>            可讀寫 **int**. |
| [`pie_split_custom_points`](/slides/python-net/zh-hant/aspose.slides.charts/chartseriesgroup/pie_split_custom_points/) | 具有自訂分割的二層圓餅圖或條形-圓餅圖的自訂分割資訊。<br/>            包含應在二層圓餅圖或條形-圓餅圖第二個圓餅或條形中繪製的資料點。<br/>            唯讀 [`PieSplitCustomPointCollection`](/slides/python-net/zh-hant/aspose.slides.charts/piesplitcustompointcollection). |
| [`chart`](/slides/python-net/zh-hant/aspose.slides.charts/chartseriesgroup/chart/) | 返回父圖表。<br/>            唯讀 [`IChart`](/slides/python-net/zh-hant/aspose.slides.charts/ichart). |
| [`slide`](/slides/python-net/zh-hant/aspose.slides.charts/chartseriesgroup/slide/) |  |
| [`presentation`](/slides/python-net/zh-hant/aspose.slides.charts/chartseriesgroup/presentation/) |  |

取得指定索引處的元素。

## 索引器

| 名稱 | 說明 |
| :- | :- |
| [`[index]`](/slides/python-net/zh-hant/aspose.slides.charts/chartseriesgroup/__getitem__/) |  |

### 備註

1) 請參閱 ChartSeriesGroupCollection 類別 和 CombinableSeriesTypesGroup 列舉 的摘要與備註。  
2) 系列群組包含一些對每個群組內系列共通的系列屬性（「系列群組屬性」）。  
「系列群組屬性」於 ChartSeriesGroup 類別中為可讀寫。  
每個「系列群組屬性」在 ChartSeries 類別中可能有唯讀的投影。

### 另見
* 模組 [`aspose.slides.charts`](/slides/python-net/zh-hant/aspose.slides.charts)
* 函式庫 [`Aspose.Slides`](/slides/python-net)