---
title: refresh_data method
second_title: Aspose.Slides for Python via .NET API 參考
description: 
type: docs
url: /zh-hant/aspose.slides.charts/ichartdata/refresh_data/
weight: 30
---
## refresh_data(self) {#}
從來源活頁簿重新載入以刷新圖表資料。

```python
def refresh_data(self):
    ...
```

### 說明

如果圖表使用外部活頁簿，必須在呼叫時確保該活頁簿可存取。

### 例外

| 例外 | 描述 |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | 當活頁簿格式不受支援，或當 [`IChartData.data_source_type`](/slides/python-net/zh-hant/aspose.slides.charts/ichartdata/data_source_type) 為<br/>            [`ChartDataSourceType.EXTERNAL_WORKBOOK`](/slides/python-net/zh-hant/aspose.slides.charts/chartdatasourcetype/EXTERNAL_WORKBOOK) 且無法存取或載入外部活頁簿時拋出。 |

### 參見
* 類別 [`IChartData`](/slides/python-net/zh-hant/aspose.slides.charts/ichartdata)
* 模組 [`aspose.slides.charts`](/slides/python-net/zh-hant/aspose.slides.charts)
* 函式庫 [`Aspose.Slides`](/slides/python-net)