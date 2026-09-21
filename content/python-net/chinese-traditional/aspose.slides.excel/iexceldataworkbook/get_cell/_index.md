---
title: get_cell method
second_title: Aspose.Slides for Python via .NET API 參考手冊
description: 
type: docs
url: /zh-hant/aspose.slides.excel/iexceldataworkbook/get_cell/
weight: 10
---
## get_cell(self, worksheet_index, cell_name) {#int-str}
使用其索引和 Excel 風格的儲存格名稱（例如 "B2"）從指定的工作表檢索儲存格。

### 回傳

指定位置的儲存格。



```python
def get_cell(self, worksheet_index, cell_name):
    ...
```


| 參數 | 類型 | 描述 |
| :- | :- | :- |
| worksheet_index | **int** | 工作表的零基索引。 |
| cell_name | **str** | Excel 風格的儲存格參照（例如 "A1", "C5"）。 |


## get_cell(self, worksheet_name, cell_name) {#str-str}
使用 Excel 風格的儲存格名稱（例如 "B2"）從指定的工作表檢索儲存格。

### 回傳

指定位置的儲存格。



```python
def get_cell(self, worksheet_name, cell_name):
    ...
```


| 參數 | 類型 | 描述 |
| :- | :- | :- |
| worksheet_name | **str** | 工作表的名稱。 |
| cell_name | **str** | Excel 風格的儲存格參照（例如 "A1", "C5"）。 |


## get_cell(self, worksheet_index, row, column) {#int-int-int}
使用其索引和儲存格座標從指定的工作表檢索儲存格。

### 回傳

指定位置的儲存格。



```python
def get_cell(self, worksheet_index, row, column):
    ...
```


| 參數 | 類型 | 描述 |
| :- | :- | :- |
| worksheet_index | **int** | 工作表的零基索引。 |
| row | **int** | 儲存格的零基列索引。 |
| column | **int** | 儲存格的零基欄索引。 |


## get_cell(self, worksheet_name, row, column) {#str-int-int}
使用其名稱和儲存格座標從指定的工作表檢索儲存格。

### 回傳

指定位置的儲存格。



```python
def get_cell(self, worksheet_name, row, column):
    ...
```


| 參數 | 類型 | 描述 |
| :- | :- | :- |
| worksheet_name | **str** | 工作表的名稱。 |
| row | **int** | 儲存格的零基列索引。 |
| column | **int** | 儲存格的零基欄索引。 |



### 另見
* 類別 [`IExcelDataCell`](/slides/python-net/zh-hant/aspose.slides.excel/iexceldatacell)
* 類別 [`IExcelDataWorkbook`](/slides/python-net/zh-hant/aspose.slides.excel/iexceldataworkbook)
* 模組 [`aspose.slides.excel`](/slides/python-net/zh-hant/aspose.slides.excel)
* 函式庫 [`Aspose.Slides`](/slides/python-net)