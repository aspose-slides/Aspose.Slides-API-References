---
title: set_external_workbook method
second_title: Aspose.Slides for Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides.charts/chartdata/set_external_workbook/
weight: 30
---
## set_external_workbook(self, workbook_path) {#str}
將外部工作簿設為圖表的資料來源。圖表資料將從目標工作簿更新。


```python
def set_external_workbook(self, workbook_path):
    ...
```


| 參數 | 類型 | 說明 |
| :- | :- | :- |
| workbook_path | **str** | 目標工作簿的路徑 |

### 例外

| 例外 | 說明 |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | 外部工作簿不可用或無法載入。 |


## set_external_workbook(self, workbook_path, update_chart_data) {#str-bool}
將外部工作簿設為圖表的資料來源。


```python
def set_external_workbook(self, workbook_path, update_chart_data):
    ...
```


| 參數 | 類型 | 說明 |
| :- | :- | :- |
| workbook_path | **str** | 目標工作簿的路徑 |
| update_chart_data | **bool** | 如果值為 false，僅會更新工作簿路徑。 <br/><br/>             圖表資料不會從目標工作簿載入和更新。可在目標工作簿不存在或無法取得時使用。<br/><br/>             如果值為 true，圖表資料將從目標工作簿更新。 |

### 例外

| 例外 | 說明 |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | 外部工作簿不可用或無法載入。 |



### 另見
* 類別 [`ChartData`](/slides/python-net/zh-hant/aspose.slides.charts/chartdata)
* 模組 [`aspose.slides.charts`](/slides/python-net/zh-hant/aspose.slides.charts)
* 函式庫 [`Aspose.Slides`](/slides/python-net)