---
title: add_table_from_workbook method
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides.importing/excelworkbookimporter/add_table_from_workbook/
weight: 20
---


## add_table_from_workbook {#ishapecollection-float-float-asposeslidesexceliexceldataworkbook-str-str}
Retrieves a table from the specified Excel workbook and adds it to the end of the given shape collection at the specified coordinates.

### Returns

The table that was added to the shape collection.



```python
@staticmethod
def add_table_from_workbook(shapes, x, y, workbook, worksheet_name, cell_range):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| shapes | [`IShapeCollection`](/slides/python-net/aspose.slides/ishapecollection) | The shape collection to which the table will be added. |
| x | **float** | The X coordinate for positioning the table. |
| y | **float** | The Y coordinate for positioning the table. |
| workbook | [`IExcelDataWorkbook`](/slides/python-net/aspose.slides.excel/iexceldataworkbook) | The Excel workbook. |
| worksheet_name | **str** | The name of the worksheet that contains the table. |
| cell_range | **str** | The cell range that defines the table (for example, "A1:D10"). |

### Exceptions

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Thrown when any required parameter is None or empty, or when the specified worksheet or cell range is invalid. |
| **RuntimeError(Proxy error(InvalidOperationException))** | Thrown when the input data is in an unsupported format. |


## add_table_from_workbook {#ishapecollection-float-float-str-str-str}
Retrieves a table from the specified Excel workbook file and adds it to the end of the given shape collection at the specified coordinates.

### Returns

The table that was added to the shape collection.



```python
@staticmethod
def add_table_from_workbook(shapes, x, y, workbook_path, worksheet_name, cell_range):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| shapes | [`IShapeCollection`](/slides/python-net/aspose.slides/ishapecollection) | The shape collection to which the table will be added. |
| x | **float** | The X coordinate for positioning the table. |
| y | **float** | The Y coordinate for positioning the table. |
| workbook_path | **str** | The path to the Excel workbook file. |
| worksheet_name | **str** | The name of the worksheet that contains the table. |
| cell_range | **str** | The cell range that defines the table (for example, "A1:D10"). |

### Exceptions

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Thrown when any required parameter is None or empty, or when the specified worksheet or cell range is invalid. |
| **RuntimeError(Proxy error(IOException))** | Thrown when an I/O error occurs while accessing the workbook file. |
| **RuntimeError(Proxy error(InvalidOperationException))** | Thrown when the input data is in an unsupported format. |


## add_table_from_workbook {#ishapecollection-float-float-iorawiobase-str-str}
Retrieves a table from the specified Excel workbook file and adds it to the end of the given shape collection at the specified coordinates.

### Returns

The table that was added to the shape collection.



```python
@staticmethod
def add_table_from_workbook(shapes, x, y, workbook_stream, worksheet_name, cell_range):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| shapes | [`IShapeCollection`](/slides/python-net/aspose.slides/ishapecollection) | The shape collection to which the table will be added. |
| x | **float** | The X coordinate for positioning the table. |
| y | **float** | The Y coordinate for positioning the table. |
| workbook_stream | **io.RawIOBase** | A stream containing the workbook data. |
| worksheet_name | **str** | The name of the worksheet that contains the table. |
| cell_range | **str** | The cell range that defines the table (for example, "A1:D10"). |

### Exceptions

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Thrown when any required parameter is None or empty, or when the specified worksheet or cell range is invalid. |
| **RuntimeError(Proxy error(InvalidOperationException))** | Thrown when the input data is in an unsupported format. |



### See Also
* class [`ExcelWorkbookImporter`](/slides/python-net/aspose.slides.importing/excelworkbookimporter)
* class [`IExcelDataWorkbook`](/slides/python-net/aspose.slides.excel/iexceldataworkbook)
* class [`IShapeCollection`](/slides/python-net/aspose.slides/ishapecollection)
* class [`ITable`](/slides/python-net/aspose.slides/itable)
* module [`aspose.slides.importing`](/slides/python-net/aspose.slides.importing)
* library [`Aspose.Slides`](/slides/python-net)

