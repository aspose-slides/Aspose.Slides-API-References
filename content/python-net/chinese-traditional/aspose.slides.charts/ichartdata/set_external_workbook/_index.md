---
title: set_external_workbook method
second_title: Aspose.Slides for Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides.charts/ichartdata/set_external_workbook/
weight: 40
---
## set_external_workbook(self, workbook_path) {#str}
將外部工作簿設定為圖表的資料來源。圖表資料將從目標工作簿更新。


```python
def set_external_workbook(self, workbook_path):
    ...
```


| 參數 | 類型 | 描述 |
| :- | :- | :- |
| workbook_path | **str** | 目標工作簿的路徑 |

### 例外情況

| 例外 | 描述 |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | 外部工作簿不可用或無法載入。 |


## set_external_workbook(self, workbook_path, update_chart_data) {#str-bool}
將外部工作簿設定為圖表的資料來源。


```python
def set_external_workbook(self, workbook_path, update_chart_data):
    ...
```


| 參數 | 類型 | 描述 |
| :- | :- | :- |
| workbook_path | **str** | 目標工作簿的路徑 |
| update_chart_data | **bool** | 如果值為 false，則只會更新工作簿路徑。 <br/><br/>             不會從目標工作簿載入和更新圖表資料。當目標工作簿不存在或無法取得時，可使用此設定。<br/><br/>             如果值為 true，則會從目標工作簿更新圖表資料。 |

### 例外情況

| 例外 | 描述 |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | 外部工作簿不可用或無法載入。 |



### 另請參閱
* 類別 [`IChartData`](/slides/python-net/zh-hant/aspose.slides.charts/ichartdata)
* 模組 [`aspose.slides.charts`](/slides/python-net/zh-hant/aspose.slides.charts)
* 函式庫 [`Aspose.Slides`](/slides/python-net)