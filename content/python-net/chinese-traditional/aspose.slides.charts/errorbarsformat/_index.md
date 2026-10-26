---
title: ErrorBarsFormat class
second_title: Aspose.Slides for Python via .NET API 參考
description: 
type: docs
url: /zh-hant/aspose.slides.charts/errorbarsformat/
---
## ErrorBarsFormat 類別

代表圖表系列的誤差棒。ErrorBars 的自訂值位於 IChartDataPointCollection（在 [`IChartDataPoint.error_bars_custom_values`](/slides/python-net/zh-hant/aspose.slides.charts/ichartdatapoint/error_bars_custom_values) 屬性中）。

ErrorBarsFormat 類型公開以下成員：

## 屬性

| Property | Description |
| :- | :- |
| [`type`](/slides/python-net/zh-hant/aspose.slides.charts/errorbarsformat/type/) | 取得或設定誤差棒的類型。<br/>            讀寫 [`ErrorBarType`](/slides/python-net/zh-hant/aspose.slides.charts/errorbartype)。 |
| [`value_type`](/slides/python-net/zh-hant/aspose.slides.charts/errorbarsformat/value_type/) | 表示決定誤差棒長度的可能方式。<br/>            若為自訂值類型，請使用系列 DataPoints 集合中特定資料點的 [`IChartDataPoint.error_bars_custom_values`](/slides/python-net/zh-hant/aspose.slides.charts/ichartdatapoint/error_bars_custom_values) 屬性來指定值。<br/>            若為 Fixed、Percentage 或 StandardDeviation 類型，請使用 Value 屬性來指定值。<br/>            讀寫 [`ErrorBarValueType`](/slides/python-net/zh-hant/aspose.slides.charts/errorbarvaluetype)。 |
| [`has_end_cap`](/slides/python-net/zh-hant/aspose.slides.charts/errorbarsformat/has_end_cap/) | 指定不在誤差棒上繪製端帽。<br/>            讀寫 **bool**。 |
| [`value`](/slides/python-net/zh-hant/aspose.slides.charts/errorbarsformat/value/) | 取得或設定用於 Fixed、Percentage 與 StandardDeviation 類型以決定誤差棒長度的值。<br/>            在其他情況下將返回 NaN。<br/>            讀寫 **float**。 |
| [`format`](/slides/python-net/zh-hant/aspose.slides.charts/errorbarsformat/format/) | 表示誤差棒的格式。<br/>            讀寫 [`IFormat`](/slides/python-net/zh-hant/aspose.slides.charts/iformat)。 |
| [`chart`](/slides/python-net/zh-hant/aspose.slides.charts/errorbarsformat/chart/) | 返回父圖表。<br/>            唯讀 [`IChart`](/slides/python-net/zh-hant/aspose.slides.charts/ichart)。 |
| [`is_visible`](/slides/python-net/zh-hant/aspose.slides.charts/errorbarsformat/is_visible/) | 取得或設定誤差棒的可見性。<br/>            讀寫 **bool**。 |
| [`slide`](/slides/python-net/zh-hant/aspose.slides.charts/errorbarsformat/slide/) |  |
| [`presentation`](/slides/python-net/zh-hant/aspose.slides.charts/errorbarsformat/presentation/) |  |

### 另請參閱
* 模組 [`aspose.slides.charts`](/slides/python-net/zh-hant/aspose.slides.charts)
* 函式庫 [`Aspose.Slides`](/slides/python-net)