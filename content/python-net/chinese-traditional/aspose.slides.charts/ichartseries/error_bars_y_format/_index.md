---
title: error_bars_y_format property
second_title: Aspose.Slides for Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides.charts/ichartseries/error_bars_y_format/
weight: 120
---
## error_bars_y_format 屬性
表示具有 Y 方向的系列的 ErrorBars。

            具有 Y 方向的 ErrorBars 可用於 area、bar、line、scatter 和 bubble 類型的系列。 
            對於其他任何類型的圖表，此屬性返回 None（包括 3D 圖表）。 
            如果使用自訂值，請使用 DataPoints 集合來指定值（使用 [`IChartDataPoint.error_bars_custom_values`](/slides/python-net/zh-hant/aspose.slides.charts/ichartdatapoint/error_bars_custom_values) 屬性）。
            
            唯讀 [`IErrorBarsFormat`](/slides/python-net/zh-hant/aspose.slides.charts/ierrorbarsformat)。

### 定義：
```python
@property
def error_bars_y_format(self):
    ...
```


### 另見
* 類別 [`IChartSeries`](/slides/python-net/zh-hant/aspose.slides.charts/ichartseries)
* 類別 [`IErrorBarsFormat`](/slides/python-net/zh-hant/aspose.slides.charts/ierrorbarsformat)
* 模組 [`aspose.slides.charts`](/slides/python-net/zh-hant/aspose.slides.charts)
* 函式庫 [`Aspose.Slides`](/slides/python-net)