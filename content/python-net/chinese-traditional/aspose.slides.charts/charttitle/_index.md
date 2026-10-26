---
title: ChartTitle class
second_title: Aspose.Slides 用於 Python via .NET API 參考
description: 
type: docs
url: /zh-hant/aspose.slides.charts/charttitle/
---
## ChartTitle 類別

表示圖表標題屬性。

ChartTitle 類型公開以下成員：

## 屬性

| Property | Description |
| :- | :- |
| [`x`](/slides/python-net/zh-hant/aspose.slides.charts/charttitle/x/) | 返回或設定標題的 x 座標，作為圖表寬度的比例。<br/>            讀寫 **float**。 |
| [`y`](/slides/python-net/zh-hant/aspose.slides.charts/charttitle/y/) | 返回或設定標題的 y 座標，作為圖表高度的比例。<br/>            讀寫 **float**。 |
| [`width`](/slides/python-net/zh-hant/aspose.slides.charts/charttitle/width/) | 返回或設定標題的寬度，作為圖表寬度的比例。<br/>            讀寫 **float**。 |
| [`height`](/slides/python-net/zh-hant/aspose.slides.charts/charttitle/height/) | 返回或設定標題的高度，作為圖表高度的比例。<br/>            讀寫 **float**。 |
| [`right`](/slides/python-net/zh-hant/aspose.slides.charts/charttitle/right/) | 右側。<br/>            唯讀 **float**。 |
| [`bottom`](/slides/python-net/zh-hant/aspose.slides.charts/charttitle/bottom/) | 底部。<br/>            唯讀 **float**。 |
| [`overlay`](/slides/python-net/zh-hant/aspose.slides.charts/charttitle/overlay/) | 判斷是否允許其他圖表元素覆蓋標題。<br/>            讀寫 **bool**。 |
| [`format`](/slides/python-net/zh-hant/aspose.slides.charts/charttitle/format/) | 返回標題的填充、線條、效果樣式。<br/>            唯讀 [`IFormat`](/slides/python-net/zh-hant/aspose.slides.charts/iformat)。 |
| [`text_frame_for_overriding`](/slides/python-net/zh-hant/aspose.slides.charts/charttitle/text_frame_for_overriding/) | 可包含富格式文字。若此屬性不為 None，則此格式化文字值會覆寫自動產生的文字。<br/>            自動產生的文字是資料標籤、數值軸的單位標籤、軸標題、圖表標題、趨勢線標籤等的隱含屬性。<br/>            自動產生的文字會使用 IFormattedTextContainer.TextFormat 屬性進行格式化。<br/>            唯讀 [`ITextFrame`](/slides/python-net/zh-hant/aspose.slides/itextframe)。 |
| [`text_format`](/slides/python-net/zh-hant/aspose.slides.charts/charttitle/text_format/) | 返回文字格式。<br/>            唯讀 [`IChartTextFormat`](/slides/python-net/zh-hant/aspose.slides.charts/icharttextformat)。 |
| [`actual_x`](/slides/python-net/zh-hant/aspose.slides.charts/charttitle/actual_x/) | 指定圖表元素相對於圖表左上角的實際 x 位置（左）。<br/>            在取得實際值前請先呼叫 IChart.ValidateChartLayout() 方法。<br/>            讀 **float**。 |
| [`actual_y`](/slides/python-net/zh-hant/aspose.slides.charts/charttitle/actual_y/) | 指定圖表元素相對於圖表左上角的實際頂部位置。<br/>            在取得實際值前請先呼叫 IChart.ValidateChartLayout() 方法。<br/>            讀 **float**。 |
| [`actual_width`](/slides/python-net/zh-hant/aspose.slides.charts/charttitle/actual_width/) | 指定圖表元素的實際寬度。請先呼叫 IChart.ValidateChartLayout() 方法以取得實際值。<br/>            讀 **float**。 |
| [`actual_height`](/slides/python-net/zh-hant/aspose.slides.charts/charttitle/actual_height/) | 指定圖表元素的實際高度。請先呼叫 IChart.ValidateChartLayout() 方法以取得實際值。<br/>            讀 **float**。 |
| [`chart`](/slides/python-net/zh-hant/aspose.slides.charts/charttitle/chart/) | 返回父圖表。<br/>            唯讀 [`IChart`](/slides/python-net/zh-hant/aspose.slides.charts/ichart)。 |
| [`slide`](/slides/python-net/zh-hant/aspose.slides.charts/charttitle/slide/) |  |
| [`presentation`](/slides/python-net/zh-hant/aspose.slides.charts/charttitle/presentation/) |  |

## 方法

| Method | Description |
| :- | :- |
| [`add_text_frame_for_overriding(self, text)`](/slides/python-net/zh-hant/aspose.slides.charts/charttitle/add_text_frame_for_overriding/#str) | 使用參數「text」中的文字初始化 TextFrameForOverriding。<br/>            若 TextFrameForOverriding 已初始化，則僅變更其文字。 |

### 另請參閱
* 模組 [`aspose.slides.charts`](/slides/python-net/zh-hant/aspose.slides.charts)
* 函式庫 [`Aspose.Slides`](/slides/python-net)