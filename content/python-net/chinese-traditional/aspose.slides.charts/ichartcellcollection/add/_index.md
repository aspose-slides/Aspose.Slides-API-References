---
title: add method
second_title: Aspose.Slides for Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides.charts/ichartcellcollection/add/
weight: 10
---
## add(self, chart_data_cell) {#ichartdatacell}
將新的儲存格加入集合。

```python
def add(self, chart_data_cell):
    ...
```

| 參數 | 類型 | 說明 |
| :- | :- | :- |
| chart_data_cell | [`IChartDataCell`](/slides/python-net/zh-hant/aspose.slides.charts/ichartdatacell) | 要加入的新儲存格。 |

## add(self, value) {#any}
根據指定的值建立 [`IChartDataCell`](/slides/python-net/zh-hant/aspose.slides.charts/ichartdatacell) 並將其加入集合。

```python
def add(self, value):
    ...
```

| 參數 | 類型 | 說明 |
| :- | :- | :- |
| value | **any** | 該值。 |

### 備註

此方法會新增名稱為 AUTO_DATA 的工作表，並在其中加入所有值。若使用 [`IChartDataWorkbook`](/slides/python-net/zh-hant/aspose.slides.charts/ichartdataworkbook) 新增或編輯 Cell 值，請確保不要使用此工作表
            使用此方法新增的最大值數量不得超過 16711680

### 例外情形

| 例外 | 說明 |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | 若超過限制 |

### 另請參閱
* 類別 [`IChartCellCollection`](/slides/python-net/zh-hant/aspose.slides.charts/ichartcellcollection)
* 類別 [`IChartDataCell`](/slides/python-net/zh-hant/aspose.slides.charts/ichartdatacell)
* 類別 [`IChartDataWorkbook`](/slides/python-net/zh-hant/aspose.slides.charts/ichartdataworkbook)
* 模組 [`aspose.slides.charts`](/slides/python-net/zh-hant/aspose.slides.charts)
* 函式庫 [`Aspose.Slides`](/slides/python-net)