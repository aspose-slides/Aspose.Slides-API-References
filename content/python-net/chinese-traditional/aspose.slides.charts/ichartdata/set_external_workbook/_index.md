---
title: set_external_workbook method
second_title: Aspose.Slides for Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides.charts/ichartdata/set_external_workbook/
weight: 30
---
## set_external_workbook(self, workbook_path) {#str}
將外部活頁簿設定為圖表的資料來源。圖表資料將會從目標活頁簿更新。

```python
def set_external_workbook(self, workbook_path):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| workbook_path | **str** | 目標活頁簿的路徑 |

### Exceptions

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | 外部活頁簿不可用或無法載入。 |

## set_external_workbook(self, workbook_path, update_chart_data) {#str-bool}
將外部活頁簿設定為圖表的資料來源。

```python
def set_external_workbook(self, workbook_path, update_chart_data):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| workbook_path | **str** | 目標活頁簿的路徑 |
| update_chart_data | **bool** | 若值為 false，僅會更新活頁簿路徑。<br/><br/>圖表資料不會從目標活頁簿載入和更新。可在目標活頁簿不存在或不可用時使用。<br/><br/>若值為 true，圖表資料將會從目標活頁簿更新。 |

### Exceptions

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | 外部活頁簿不可用或無法載入。 |

### See Also
* 類別 [`IChartData`](/slides/python-net/zh-hant/aspose.slides.charts/ichartdata)
* 模組 [`aspose.slides.charts`](/slides/python-net/zh-hant/aspose.slides.charts)
* 函式庫 [`Aspose.Slides`](/slides/python-net)