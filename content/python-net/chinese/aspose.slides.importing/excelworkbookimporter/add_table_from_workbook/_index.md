---
title: add_table_from_workbook method
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides.importing/excelworkbookimporter/add_table_from_workbook/
weight: 20
---
## add_table_from_workbook(shapes, x, y, workbook, worksheet_name, cell_range) {#ishapecollection-float-float-asposeslidesexceliexceldataworkbook-str-str}
从指定的 Excel 工作簿检索表格，并在指定坐标处将其添加到给定形状集合的末尾。

### 返回值

已添加到形状集合的表格。



```python
@staticmethod
def add_table_from_workbook(shapes, x, y, workbook, worksheet_name, cell_range):
    ...
```


| 参数 | 类型 | 描述 |
| :- | :- | :- |
| shapes | [`IShapeCollection`](/slides/python-net/zh/aspose.slides/ishapecollection) | 将添加表格的形状集合。 |
| x | **float** | 用于定位表格的 X 坐标。 |
| y | **float** | 用于定位表格的 Y 坐标。 |
| workbook | [`IExcelDataWorkbook`](/slides/python-net/zh/aspose.slides.excel/iexceldataworkbook) | Excel 工作簿。 |
| worksheet_name | **str** | 包含表格的工作表名称。 |
| cell_range | **str** | 定义表格的单元格范围（例如 "A1:D10"）。 |

### 异常

| 异常 | 描述 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | 当任意必需参数为 None 或为空，或指定的工作表或单元格范围无效时抛出。 |
| **RuntimeError(Proxy error(InvalidOperationException))** | 当输入数据格式不受支持时抛出。 |


## add_table_from_workbook(shapes, x, y, workbook_path, worksheet_name, cell_range) {#ishapecollection-float-float-str-str-str}
从指定的 Excel 工作簿文件检索表格，并在指定坐标处将其添加到给定形状集合的末尾。

### 返回值

已添加到形状集合的表格。



```python
@staticmethod
def add_table_from_workbook(shapes, x, y, workbook_path, worksheet_name, cell_range):
    ...
```


| 参数 | 类型 | 描述 |
| :- | :- | :- |
| shapes | [`IShapeCollection`](/slides/python-net/zh/aspose.slides/ishapecollection) | 将添加表格的形状集合。 |
| x | **float** | 用于定位表格的 X 坐标。 |
| y | **float** | 用于定位表格的 Y 坐标。 |
| workbook_path | **str** | Excel 工作簿文件的路径。 |
| worksheet_name | **str** | 包含表格的工作表名称。 |
| cell_range | **str** | 定义表格的单元格范围（例如 "A1:D10"）。 |

### 异常

| 异常 | 描述 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | 当任意必需参数为 None 或为空，或指定的工作表或单元格范围无效时抛出。 |
| **RuntimeError(Proxy error(IOException))** | 在访问工作簿文件时发生 I/O 错误时抛出。 |
| **RuntimeError(Proxy error(InvalidOperationException))** | 当输入数据格式不受支持时抛出。 |


## add_table_from_workbook(shapes, x, y, workbook_stream, worksheet_name, cell_range) {#ishapecollection-float-float-iorawiobase-str-str}
从指定的 Excel 工作簿文件检索表格，并在指定坐标处将其添加到给定形状集合的末尾。

### 返回值

已添加到形状集合的表格。



```python
@staticmethod
def add_table_from_workbook(shapes, x, y, workbook_stream, worksheet_name, cell_range):
    ...
```


| 参数 | 类型 | 描述 |
| :- | :- | :- |
| shapes | [`IShapeCollection`](/slides/python-net/zh/aspose.slides/ishapecollection) | 将添加表格的形状集合。 |
| x | **float** | 用于定位表格的 X 坐标。 |
| y | **float** | 用于定位表格的 Y 坐标。 |
| workbook_stream | **io.RawIOBase** | 包含工作簿数据的流。 |
| worksheet_name | **str** | 包含表格的工作表名称。 |
| cell_range | **str** | 定义表格的单元格范围（例如 "A1:D10"）。 |

### 异常

| 异常 | 描述 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | 当任意必需参数为 None 或为空，或指定的工作表或单元格范围无效时抛出。 |
| **RuntimeError(Proxy error(InvalidOperationException))** | 当输入数据格式不受支持时抛出。 |



### 另请参见
* 类 [`ExcelWorkbookImporter`](/slides/python-net/zh/aspose.slides.importing/excelworkbookimporter)
* 类 [`IExcelDataWorkbook`](/slides/python-net/zh/aspose.slides.excel/iexceldataworkbook)
* 类 [`IShapeCollection`](/slides/python-net/zh/aspose.slides/ishapecollection)
* 类 [`ITable`](/slides/python-net/zh/aspose.slides/itable)
* 模块 [`aspose.slides.importing`](/slides/python-net/zh/aspose.slides.importing)
* 库 [`Aspose.Slides`](/slides/python-net)