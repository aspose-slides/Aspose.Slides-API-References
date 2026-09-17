---
title: get_cell method
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides.excel/exceldataworkbook/get_cell/
weight: 20
---
## get_cell(self, worksheet_index, cell_name) {#int-str}
检索指定工作表中的单元格，使用其索引和 Excel-style 单元格名称（例如 "B2"）。

### 返回

指定位置的单元格。

```python
def get_cell(self, worksheet_index, cell_name):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| worksheet_index | **int** | 工作表的零基索引。 |
| cell_name | **str** | Excel-style 单元格引用（例如 "A1", "C5"）。 |

## get_cell(self, worksheet_name, cell_name) {#str-str}
检索指定工作表中的单元格，使用 Excel-style 单元格名称（例如 "B2"）。

### 返回

指定位置的单元格。

```python
def get_cell(self, worksheet_name, cell_name):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| worksheet_name | **str** | 工作表的名称。 |
| cell_name | **str** | Excel-style 单元格引用（例如 "A1", "C5"）。 |

## get_cell(self, worksheet_index, row, column) {#int-int-int}
检索指定工作表中的单元格，使用其索引和单元格坐标。

### 返回

指定位置的单元格。

```python
def get_cell(self, worksheet_index, row, column):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| worksheet_index | **int** | 工作表的零基索引。 |
| row | **int** | 单元格的零基行索引。 |
| column | **int** | 单元格的零基列索引。 |

## get_cell(self, worksheet_name, row, column) {#str-int-int}
检索指定工作表中的单元格，使用其名称和单元格坐标。

### 返回

指定位置的单元格。

```python
def get_cell(self, worksheet_name, row, column):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| worksheet_name | **str** | 工作表的名称。 |
| row | **int** | 单元格的零基行索引。 |
| column | **int** | 单元格的零基列索引。 |

### 参见
* 类 [`ExcelDataWorkbook`](/slides/python-net/zh/aspose.slides.excel/exceldataworkbook)
* 类 [`IExcelDataCell`](/slides/python-net/zh/aspose.slides.excel/iexceldatacell)
* 模块 [`aspose.slides.excel`](/slides/python-net/zh/aspose.slides.excel)
* library [`Aspose.Slides`](/slides/python-net)