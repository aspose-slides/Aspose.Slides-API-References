---
title: set_external_workbook method
second_title: Aspose.Slides for Python via .NET API 參考
description: 
type: docs
url: /zh-hant/aspose.slides.charts/chartdata/set_external_workbook/
weight: 40
---
## set_external_workbook(self, workbook_path) {#str}
將外部活頁簿設為圖表的資料來源。圖表資料將從目標活頁簿更新。

```python
def set_external_workbook(self, workbook_path):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| workbook_path | **str** | 目標活頁簿的路徑 |

### 例外情況

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | 外部活頁簿不可用或無法載入。 |

## set_external_workbook(self, workbook_path, update_chart_data) {#str-bool}
將外部活頁簿設為圖表的資料來源。

```python
def set_external_workbook(self, workbook_path, update_chart_data):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| workbook_path | **str** | 目標活頁簿的路徑 |
| update_chart_data | **bool** | 如果值為 false，僅會更新活頁簿路徑。<br/><br/>              圖表資料將不會從目標活頁簿載入或更新。可在目標活頁簿不存在或不可用時使用。<br/><br/>              如果值為 true，圖表資料將從目標活頁簿更新。 |

### 例外情況

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | 外部活頁簿不可用或無法載入。 |

### 另見
* 類別 [`ChartData`](/slides/python-net/zh-hant/aspose.slides.charts/chartdata)
* 模組 [`aspose.slides.charts`](/slides/python-net/zh-hant/aspose.slides.charts)
* 程式庫 [`Aspose.Slides`](/slides/python-net)