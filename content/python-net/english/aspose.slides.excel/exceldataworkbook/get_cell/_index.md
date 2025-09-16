---
title: get_cell method
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides.excel/exceldataworkbook/get_cell/
weight: 20
---


## get_cell {#int-str}
Retrieves a cell from the specified worksheet using its index and Excel-style cell name (e.g., "B2").

### Returns

The cell at the specified location.



```python
def get_cell(self, worksheet_index, cell_name):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| worksheet_index | **int** | Zero-based index of the worksheet. |
| cell_name | **str** | The Excel-style cell reference (e.g., "A1", "C5"). |

### Examples

Example:


## get_cell {#str-str}
Retrieves a cell from the specified worksheet using Excel-style cell name (e.g., "B2").

### Returns

The cell at the specified location.



```python
def get_cell(self, worksheet_name, cell_name):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| worksheet_name | **str** | The name of the worksheet. |
| cell_name | **str** | The Excel-style cell reference (e.g., "A1", "C5"). |

### Examples

Example:


## get_cell {#int-int-int}
Retrieves a cell from the specified worksheet using its index and cell coordinates.

### Returns

The cell at the specified location.



```python
def get_cell(self, worksheet_index, row, column):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| worksheet_index | **int** | Zero-based index of the worksheet. |
| row | **int** | Zero-based row index of the cell. |
| column | **int** | Zero-based column index of the cell. |

### Examples

Example:


## get_cell {#str-int-int}
Retrieves a cell from the specified worksheet using its name and cell coordinates.

### Returns

The cell at the specified location.



```python
def get_cell(self, worksheet_name, row, column):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| worksheet_name | **str** | The name of the worksheet. |
| row | **int** | Zero-based row index of the cell. |
| column | **int** | Zero-based column index of the cell. |

### Examples

Example:



### See Also
* class [`ExcelDataWorkbook`](/slides/python-net/aspose.slides.excel/exceldataworkbook)
* class [`IExcelDataCell`](/slides/python-net/aspose.slides.excel/iexceldatacell)
* module [`aspose.slides.excel`](/slides/python-net/aspose.slides.excel)
* library [`Aspose.Slides`](/slides/python-net)

