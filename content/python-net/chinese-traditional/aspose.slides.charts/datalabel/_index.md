---
title: DataLabel class
second_title: Aspose.Slides for Python via .NET API 參考
description: 
type: docs
url: /zh-hant/aspose.slides.charts/datalabel/
---
## DataLabel 類別

表示系列標籤。

DataLabel 型別公開以下成員：

## 建構子

| 建構子 | 說明 |
| :- | :- |
| [`__init__(self, parent_immediate)`](/slides/python-net/zh-hant/aspose.slides.charts/datalabel/__init__/#ichartdatapoint) | 建立 DataLabel 類別的新實例。 |

## 屬性

| 屬性 | 說明 |
| :- | :- |
| [`chart`](/slides/python-net/zh-hant/aspose.slides.charts/datalabel/chart/) | 傳回父圖表。<br/>            唯讀 [`IChart`](/slides/python-net/zh-hant/aspose.slides.charts/ichart)。 |
| [`is_visible`](/slides/python-net/zh-hant/aspose.slides.charts/datalabel/is_visible/) | False 表示資料標籤不可見（因此所有 Show*-旗標 (ShowValue, ...) 為 false）。<br/>            唯讀 **bool**。 |
| [`text_frame_for_overriding`](/slides/python-net/zh-hant/aspose.slides.charts/datalabel/text_frame_for_overriding/) | 可以包含富格式文字。如果此屬性非 None，則此<br/>            格式化文字值會覆寫資料標籤的自動產生文字。<br/>            資料標籤的自動產生文字指由 ShowSeriesName、<br/>            ShowValue 等屬性管理，且使用 TextFormatManager.TextFormat 屬性格式化的文字。<br/>            唯讀 [`ITextFrame`](/slides/python-net/zh-hant/aspose.slides/itextframe)。 |
| [`text_format`](/slides/python-net/zh-hant/aspose.slides.charts/datalabel/text_format/) | 傳回文字格式。<br/>            唯讀 [`IChartTextFormat`](/slides/python-net/zh-hant/aspose.slides.charts/icharttextformat)。 |
| [`x`](/slides/python-net/zh-hant/aspose.slides.charts/datalabel/x/) | 傳回或設定標題的 x 座標，作為圖表寬度的比例。<br/>            可讀寫 **float**。 |
| [`y`](/slides/python-net/zh-hant/aspose.slides.charts/datalabel/y/) | 傳回或設定標題的 y 座標，作為圖表高度的比例。<br/>            可讀寫 **float**。 |
| [`width`](/slides/python-net/zh-hant/aspose.slides.charts/datalabel/width/) | 傳回或設定標題的寬度，作為圖表寬度的比例。<br/>            可讀寫 **float**。 |
| [`height`](/slides/python-net/zh-hant/aspose.slides.charts/datalabel/height/) | 傳回或設定標題的高度，作為圖表高度的比例。<br/>            可讀寫 **float**。 |
| [`right`](/slides/python-net/zh-hant/aspose.slides.charts/datalabel/right/) | 右側。<br/>            唯讀 **float**。 |
| [`bottom`](/slides/python-net/zh-hant/aspose.slides.charts/datalabel/bottom/) | 底部。<br/>            唯讀 **float**。 |
| [`data_label_format`](/slides/python-net/zh-hant/aspose.slides.charts/datalabel/data_label_format/) | 傳回資料標籤格式。<br/>            唯讀 [`IDataLabelFormat`](/slides/python-net/zh-hant/aspose.slides.charts/idatalabelformat)。 |
| [`value_from_cell`](/slides/python-net/zh-hant/aspose.slides.charts/datalabel/value_from_cell/) | 取得或設定工作簿資料儲存格。若 IDataLabelFormat.ShowLabelValueFromCell 屬性為 true，則套用。 |
| [`label_shape_type`](/slides/python-net/zh-hant/aspose.slides.charts/datalabel/label_shape_type/) | 取得或設定資料標籤的形狀類型。<br/>             若未定義形狀，則傳回 [`ShapeType.NOT_DEFINED`](/slides/python-net/zh-hant/aspose.slides/shapetype/NOT_DEFINED)。 |
| [`actual_x`](/slides/python-net/zh-hant/aspose.slides.charts/datalabel/actual_x/) | 指定圖表元件相對於圖表左上角的實際 x 位置（左側）。<br/>            在取得實際值前請先呼叫 IChart.ValidateChartLayout() 方法。<br/>            讀 **float**。 |
| [`actual_y`](/slides/python-net/zh-hant/aspose.slides.charts/datalabel/actual_y/) | 指定圖表元件相對於圖表左上角的實際上方位置。<br/>            在取得實際值前請先呼叫 IChart.ValidateChartLayout() 方法。<br/>            讀 **float**。 |
| [`actual_width`](/slides/python-net/zh-hant/aspose.slides.charts/datalabel/actual_width/) | 指定圖表元件的實際寬度。於取得實際值前請先呼叫 IChart.ValidateChartLayout() 方法。<br/>            讀 **float**。 |
| [`actual_height`](/slides/python-net/zh-hant/aspose.slides.charts/datalabel/actual_height/) | 指定圖表元件的實際高度。於取得實際值前請先呼叫 IChart.ValidateChartLayout() 方法。<br/>            讀 **float**。 |
| [`slide`](/slides/python-net/zh-hant/aspose.slides.charts/datalabel/slide/) |  |
| [`presentation`](/slides/python-net/zh-hant/aspose.slides.charts/datalabel/presentation/) |  |

## 方法

| 方法 | 說明 |
| :- | :- |
| [`hide(self)`](/slides/python-net/zh-hant/aspose.slides.charts/datalabel/hide/#) | 透過將所有 Show*-旗標 (ShowValue, ...) 設為 false，使資料標籤隱藏。<br/>            之後 IsVisible 會為 false。 |
| [`get_actual_label_text(self)`](/slides/python-net/zh-hant/aspose.slides.charts/datalabel/get_actual_label_text/#) | 根據 DataLabelFormat 設定或 TextFrameForOverriding.Text 值傳回實際標籤文字。 |
| [`add_text_frame_for_overriding(self, text)`](/slides/python-net/zh-hant/aspose.slides.charts/datalabel/add_text_frame_for_overriding/#str) | 使用參數 "text" 的文字初始化 TextFrameForOverriding。<br/>            若 TextFrameForOverriding 已初始化，則直接變更其文字。 |

### 另請參閱
* 模組 [`aspose.slides.charts`](/slides/python-net/zh-hant/aspose.slides.charts)
* 函式庫 [`Aspose.Slides`](/slides/python-net)