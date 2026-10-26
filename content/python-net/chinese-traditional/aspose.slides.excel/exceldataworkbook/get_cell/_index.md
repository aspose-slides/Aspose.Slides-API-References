---
title: get_cell method
second_title: Aspose.Slides for Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides.excel/exceldataworkbook/get_cell/
weight: 20
---
## get_cell(self, worksheet_index, cell_name) {#int-str}
取得指定工作表中，使用其索引及 Excel 風格儲存格名稱（例如 "B2"）的儲存格。

### 返回

位於指定位置的儲存格。



```python
def get_cell(self, worksheet_index, cell_name):
    ...
```


| 參數 | 型別 | 說明 |
| :- | :- | :- |
| worksheet_index | **int** | 工作表的零基索引。 |
| cell_name | **str** | Excel 風格的儲存格參照（例如 "A1", "C5"）。 |


## get_cell(self, worksheet_name, cell_name) {#str-str}
取得指定工作表中，使用 Excel 風格儲存格名稱（例如 "B2"）的儲存格。

### 返回

位於指定位置的儲存格。



```python
def get_cell(self, worksheet_name, cell_name):
    ...
```


| 參數 | 型別 | 說明 |
| :- | :- | :- |
| worksheet_name | **str** | 工作表的名稱。 |
| cell_name | **str** | Excel 風格的儲存格參照（例如 "A1", "C5"）。 |


## get_cell(self, worksheet_index, row, column) {#int-int-int}
取得指定工作表中，使用其索引與儲存格座標的儲存格。

### 返回

位於指定位置的儲存格。



```python
def get_cell(self, worksheet_index, row, column):
    ...
```


| 參數 | 型別 | 說明 |
| :- | :- | :- |
| worksheet_index | **int** | 工作表的零基索引。 |
| row | **int** | 儲存格所在列的零基索引。 |
| column | **int** | 儲存格所在欄的零基索引。 |


## get_cell(self, worksheet_name, row, column) {#str-int-int}
取得指定工作表中，使用其名稱與儲存格座標的儲存格。

### 返回

位於指定位置的儲存格。



```python
def get_cell(self, worksheet_name, row, column):
    ...
```


| 參數 | 型別 | 說明 |
| :- | :- | :- |
| worksheet_name | **str** | 工作表的名稱。 |
| row | **int** | 儲存格所在列的零基索引。 |
| column | **int** | 儲存格所在欄的零基索引。 |



### 另見
* 類別 [`ExcelDataWorkbook`](/slides/python-net/zh-hant/aspose.slides.excel/exceldataworkbook)
* 類別 [`IExcelDataCell`](/slides/python-net/zh-hant/aspose.slides.excel/iexceldatacell)
* 模組 [`aspose.slides.excel`](/slides/python-net/zh-hant/aspose.slides.excel)
* 程式庫 [`Aspose.Slides`](/slides/python-net)