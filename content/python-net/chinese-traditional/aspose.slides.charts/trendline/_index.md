---
title: Trendline class
second_title: Aspose.Slides for Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides.charts/trendline/
---
## Trendline 類別

類別表示圖表系列的趨勢線

The Trendline type exposes the following members:

## 屬性

| 屬性 | 說明 |
| :- | :- |
| [`trendline_name`](/slides/python-net/zh-hant/aspose.slides.charts/trendline/trendline_name/) | 取得或設定 趨勢線的名稱。<br/>            讀寫 **str**. |
| [`trendline_type`](/slides/python-net/zh-hant/aspose.slides.charts/trendline/trendline_type/) | 取得或設定 趨勢線的類型。<br/>            讀寫 [`TrendlineType`](/slides/python-net/zh-hant/aspose.slides.charts/trendlinetype). |
| [`format`](/slides/python-net/zh-hant/aspose.slides.charts/trendline/format/) | 表示趨勢線的格式。<br/>            讀寫 [`IFormat`](/slides/python-net/zh-hant/aspose.slides.charts/iformat). |
| [`backward`](/slides/python-net/zh-hant/aspose.slides.charts/trendline/backward/) | 指定趨勢線在被趨勢化的系列資料之前延伸的類別（或散佈圖上的單位）數量。<br/>            在散佈圖和非散佈圖上，該值應為任何非負值。<br/>            讀寫 **float**. |
| [`forward`](/slides/python-net/zh-hant/aspose.slides.charts/trendline/forward/) | 指定趨勢線在被趨勢化的系列資料之後延伸的類別（或散佈圖上的單位）數量。<br/>            在散佈圖和非散佈圖上，該值應為任何非負值。<br/>            讀寫 **float**. |
| [`intercept`](/slides/python-net/zh-hant/aspose.slides.charts/trendline/intercept/) | 指定趨勢線與 y 軸相交的數值。僅在趨勢線類型為 exp、linear 或 poly 時支援此屬性。<br/>            讀寫 **float**. |
| [`display_equation`](/slides/python-net/zh-hant/aspose.slides.charts/trendline/display_equation/) | 指定是否在圖表上顯示趨勢線的方程式（與 Rsquaredvalue 同一標籤）。<br/>            讀寫 **bool**. |
| [`order`](/slides/python-net/zh-hant/aspose.slides.charts/trendline/order/) | 指定多項式趨勢線的階數。對其他趨勢線類型忽略。值須介於 2 到 6 之間。<br/>            讀寫 **int**. |
| [`period`](/slides/python-net/zh-hant/aspose.slides.charts/trendline/period/) | 指定移動平均趨勢線的週期。對其他趨勢線變體忽略。值須介於 2 到 255 之間。<br/>            讀寫 **int**. |
| [`display_r_squared_value`](/slides/python-net/zh-hant/aspose.slides.charts/trendline/display_r_squared_value/) | 指定是否在圖表上顯示趨勢線的 R 平方值（與方程式同一標籤）。<br/>            讀寫 **bool**. |
| [`related_legend_entry`](/slides/python-net/zh-hant/aspose.slides.charts/trendline/related_legend_entry/) | 表示與此趨勢線相關的圖例項目<br/>            唯讀 [`ILegendEntryProperties`](/slides/python-net/zh-hant/aspose.slides.charts/ilegendentryproperties). |
| [`text_frame_for_overriding`](/slides/python-net/zh-hant/aspose.slides.charts/trendline/text_frame_for_overriding/) | 可包含豐富格式的文字。如果此屬性非 None，則此<br/>            格式化文字會覆寫資料標籤的自動產生文字。<br/>            資料標籤的自動產生文字是指由 ShowSeriesName、<br/>            ShowValue 等屬性管理，並使用 TextFormatManager.TextFormat 屬性格式化的文字。<br/>            唯讀 [`ITextFrame`](/slides/python-net/zh-hant/aspose.slides/itextframe). |
| [`text_format`](/slides/python-net/zh-hant/aspose.slides.charts/trendline/text_format/) | 傳回文字格式。<br/>            唯讀 [`IChartTextFormat`](/slides/python-net/zh-hant/aspose.slides.charts/icharttextformat). |
| [`chart`](/slides/python-net/zh-hant/aspose.slides.charts/trendline/chart/) | 傳回父圖表。<br/>            唯讀 [`IChart`](/slides/python-net/zh-hant/aspose.slides.charts/ichart). |
| [`slide`](/slides/python-net/zh-hant/aspose.slides.charts/trendline/slide/) |  |
| [`presentation`](/slides/python-net/zh-hant/aspose.slides.charts/trendline/presentation/) |  |

## 方法

| 方法 | 說明 |
| :- | :- |
| [`add_text_frame_for_overriding(self, text)`](/slides/python-net/zh-hant/aspose.slides.charts/trendline/add_text_frame_for_overriding/#str) | 使用參數 "text" 中的文字初始化 TextFrameForOverriding。<br/>            如果 TextFrameForOverriding 已經初始化，則僅變更其文字。 |

### 另請參閱
* 模組 [`aspose.slides.charts`](/slides/python-net/zh-hant/aspose.slides.charts)
* 函式庫 [`Aspose.Slides`](/slides/python-net)