---
title: add method
second_title: Aspose.Slides for Python via .NET API 參考
description: 
type: docs
url: /zh-hant/aspose.slides.charts/chartcellcollection/add/
weight: 10
---
## add(self, cell) {#ichartdatacell}
將新儲存格加入集合。


```python
def add(self, cell):
    ...
```


| 參數 | 類型 | 說明 |
| :- | :- | :- |
| cell | [`IChartDataCell`](/slides/python-net/zh-hant/aspose.slides.charts/ichartdatacell) | 新儲存格。 |


## add(self, value) {#any}
從指定值建立 [`ChartDataCell`](/slides/python-net/zh-hant/aspose.slides.charts/chartdatacell) 並將其加入集合。


```python
def add(self, value):
    ...
```


| 參數 | 類型 | 說明 |
| :- | :- | :- |
| value | **any** | 該值。 |

### 備註

此方法會新增名稱為 AUTO_DATA 的工作表，並將所有值加入其中。如果您使用 [`ChartDataWorkbook`](/slides/python-net/zh-hant/aspose.slides.charts/chartdataworkbook) 來新增或編輯 Cell 值，請確保不要使用此工作表。 使用此方法新增的值的最大數量不得超過 16711680。

### 例外情況

| 例外 | 說明 |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | 若超過限制 |



### 另請參閱
* 類別 [`ChartCellCollection`](/slides/python-net/zh-hant/aspose.slides.charts/chartcellcollection)
* 類別 [`ChartDataCell`](/slides/python-net/zh-hant/aspose.slides.charts/chartdatacell)
* 類別 [`ChartDataWorkbook`](/slides/python-net/zh-hant/aspose.slides.charts/chartdataworkbook)
* 類別 [`IChartDataCell`](/slides/python-net/zh-hant/aspose.slides.charts/ichartdatacell)
* 模組 [`aspose.slides.charts`](/slides/python-net/zh-hant/aspose.slides.charts)
* 函式庫 [`Aspose.Slides`](/slides/python-net)