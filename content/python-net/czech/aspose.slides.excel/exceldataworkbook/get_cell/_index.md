---
title: get_cell method
second_title: Aspose.Slides pro Python přes .NET referenci API
description: 
type: docs
url: /cs/aspose.slides.excel/exceldataworkbook/get_cell/
weight: 20
---
## get_cell(self, worksheet_index, cell_name) {#int-str}
Vrátí buňku z určeného listu pomocí jeho indexu a názvu buňky ve stylu Excel (např. "B2").

### Returns
Buňka na zadaném místě.



```python
def get_cell(self, worksheet_index, cell_name):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| worksheet_index | **int** | Zero-based index of the worksheet. |
| cell_name | **str** | The Excel-style cell reference (e.g., "A1", "C5"). |


## get_cell(self, worksheet_name, cell_name) {#str-str}
Vrátí buňku z určeného listu pomocí názvu buňky ve stylu Excel (např. "B2").

### Returns
Buňka na zadaném místě.



```python
def get_cell(self, worksheet_name, cell_name):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| worksheet_name | **str** | The name of the worksheet. |
| cell_name | **str** | The Excel-style cell reference (e.g., "A1", "C5"). |


## get_cell(self, worksheet_index, row, column) {#int-int-int}
Vrátí buňku z určeného listu pomocí jeho indexu a souřadnic buňky.

### Returns
Buňka na zadaném místě.



```python
def get_cell(self, worksheet_index, row, column):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| worksheet_index | **int** | Zero-based index of the worksheet. |
| row | **int** | Zero-based row index of the cell. |
| column | **int** | Zero-based column index of the cell. |


## get_cell(self, worksheet_name, row, column) {#str-int-int}
Vrátí buňku z určeného listu pomocí jeho názvu a souřadnic buňky.

### Returns
Buňka na zadaném místě.



```python
def get_cell(self, worksheet_name, row, column):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| worksheet_name | **str** | The name of the worksheet. |
| row | **int** | Zero-based row index of the cell. |
| column | **int** | Zero-based column index of the cell. |



### See Also
* class [`ExcelDataWorkbook`](/slides/python-net/cs/aspose.slides.excel/exceldataworkbook)
* class [`IExcelDataCell`](/slides/python-net/cs/aspose.slides.excel/iexceldatacell)
* module [`aspose.slides.excel`](/slides/python-net/cs/aspose.slides.excel)
* library [`Aspose.Slides`](/slides/python-net)