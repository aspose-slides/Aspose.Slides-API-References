---
title: IErrorBarsFormat class
second_title: Aspose.Slides for Python via .NET API 參考
description: 
type: docs
url: /zh-hant/aspose.slides.charts/ierrorbarsformat/
---
## IErrorBarsFormat 類別

表示圖表系列的誤差棒。ErrorBars 的自訂值位於 IChartDataPointCollection（在 [`IChartDataPoint.error_bars_custom_values`](/slides/python-net/zh-hant/aspose.slides.charts/ichartdatapoint/error_bars_custom_values) 屬性中）。

IErrorBarsFormat 類型公開以下成員：

## 屬性

| Property | Description |
| :- | :- |
| [`type`](/slides/python-net/zh-hant/aspose.slides.charts/ierrorbarsformat/type/) | 取得或設定誤差棒的類型。<br/>            可讀寫 [`ErrorBarType`](/slides/python-net/zh-hant/aspose.slides.charts/errorbartype). |
| [`value_type`](/slides/python-net/zh-hant/aspose.slides.charts/ierrorbarsformat/value_type/) | 表示決定誤差棒長度的可能方式。<br/>            若為自訂值類型，要指定值請使用系列 DataPoints 集合中特定資料點的 [`IChartDataPoint.error_bars_custom_values`](/slides/python-net/zh-hant/aspose.slides.charts/ichartdatapoint/error_bars_custom_values) 屬性。<br/>            可讀寫 [`ErrorBarValueType`](/slides/python-net/zh-hant/aspose.slides.charts/errorbarvaluetype). |
| [`has_end_cap`](/slides/python-net/zh-hant/aspose.slides.charts/ierrorbarsformat/has_end_cap/) | 指定在誤差棒上不繪製末端帽。<br/>            可讀寫 **bool**. |
| [`value`](/slides/python-net/zh-hant/aspose.slides.charts/ierrorbarsformat/value/) | 取得或設定用於 Fixed、Percentage 和 StandardDeviation 類型以決定誤差棒長度的值。<br/>            可讀寫 **float**. |
| [`format`](/slides/python-net/zh-hant/aspose.slides.charts/ierrorbarsformat/format/) | 表示誤差棒的格式。<br/>            可讀寫 [`IFormat`](/slides/python-net/zh-hant/aspose.slides.charts/iformat). |
| [`is_visible`](/slides/python-net/zh-hant/aspose.slides.charts/ierrorbarsformat/is_visible/) | 取得或設定誤差棒的可見性。<br/>            可讀寫 **bool**. |
| [`chart`](/slides/python-net/zh-hant/aspose.slides.charts/ierrorbarsformat/chart/) |  |
| [`slide`](/slides/python-net/zh-hant/aspose.slides.charts/ierrorbarsformat/slide/) |  |
| [`presentation`](/slides/python-net/zh-hant/aspose.slides.charts/ierrorbarsformat/presentation/) |  |

### 參見
* 模組 [`aspose.slides.charts`](/slides/python-net/zh-hant/aspose.slides.charts)
* 函式庫 [`Aspose.Slides`](/slides/python-net)