---
title: add_chart_from_workbook method
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides.importing/excelworkbookimporter/add_chart_from_workbook/
weight: 10
---


## add_chart_from_workbook {#ishapecollection-float-float-asposeslidesexceliexceldataworkbook-str-int-bool}
Retrieves a chart from the specified Excel workbook and adds it to the end of the given shape collection at the specified coordinates.

### Returns

The chart that was added to the shape collection.



```python
@staticmethod
def add_chart_from_workbook(shapes, x, y, workbook, worksheet_name, chart_index, embed_all_workbook):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| shapes | [`IShapeCollection`](/slides/python-net/aspose.slides/ishapecollection) | The shape collection to which the chart will be added. |
| x | **float** | The X coordinate for positioning the chart. |
| y | **float** | The Y coordinate for positioning the chart. |
| workbook | [`IExcelDataWorkbook`](/slides/python-net/aspose.slides.excel/iexceldataworkbook) | The Excel workbook. |
| worksheet_name | **str** | The name of the worksheet that contains the chart. |
| chart_index | **int** | The zero-based index of the chart shape to insert. <br/><br/>            This index can be obtained using the [`IExcelDataWorkbook.get_charts_from_worksheet`](/slides/python-net/aspose.slides.excel/iexceldataworkbook/get_charts_from_worksheet) method. |
| embed_all_workbook | **bool** | If `true`, the entire workbook will be embedded in the chart; <br/><br/>            if `false`, only the chart data will be embedded. |

### Examples

Example:

### Exceptions

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Thrown when any required parameter is None, empty, or if the chart cannot be found in the workbook. |


## add_chart_from_workbook {#ishapecollection-float-float-asposeslidesexceliexceldataworkbook-str-str-bool}
Retrieves a chart from the specified Excel workbook and adds it to the end of the given shape collection at the specified coordinates.

### Returns

The chart that was added to the shape collection.



```python
@staticmethod
def add_chart_from_workbook(shapes, x, y, workbook, worksheet_name, chart_name, embed_all_workbook):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| shapes | [`IShapeCollection`](/slides/python-net/aspose.slides/ishapecollection) | The shape collection to which the chart will be added. |
| x | **float** | The X coordinate for positioning the chart. |
| y | **float** | The Y coordinate for positioning the chart. |
| workbook | [`IExcelDataWorkbook`](/slides/python-net/aspose.slides.excel/iexceldataworkbook) | The Excel workbook. |
| worksheet_name | **str** | The name of the worksheet that contains the chart. |
| chart_name | **str** | The name of the chart to be added. |
| embed_all_workbook | **bool** | If `true`, the entire workbook will be embedded in the chart; <br/><br/>            if `false`, only the chart data will be embedded. |

### Examples

Example:

### Exceptions

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Thrown when any required parameter is None, empty, or if the chart cannot be found in the workbook. |


## add_chart_from_workbook {#ishapecollection-float-float-iorawiobase-str-str-bool}
Retrieves a chart from the specified Excel workbook and adds it to the end of the given shape collection at the specified coordinates.

### Returns

The chart that was added to the shape collection.



```python
@staticmethod
def add_chart_from_workbook(shapes, x, y, workbook_stream, worksheet_name, chart_name, embed_all_workbook):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| shapes | [`IShapeCollection`](/slides/python-net/aspose.slides/ishapecollection) | The shape collection to which the chart will be added. |
| x | **float** | The X coordinate for positioning the chart. |
| y | **float** | The Y coordinate for positioning the chart. |
| workbook_stream | **io.RawIOBase** | A stream containing the workbook data. |
| worksheet_name | **str** | The name of the worksheet that contains the chart. |
| chart_name | **str** | The name of the chart to be added. |
| embed_all_workbook | **bool** | If `true`, the entire workbook will be embedded in the chart; <br/><br/>            if `false`, only the chart data will be embedded. |

### Examples

Example:

### Exceptions

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Thrown when any required parameter is None, empty, or if the chart cannot be found in the workbook. |
| **RuntimeError(Proxy error(InvalidOperationException))** | Thrown when the input data is in an unsupported format. |


## add_chart_from_workbook {#ishapecollection-float-float-str-str-str-bool}
Retrieves a chart from the specified Excel workbook and adds it to the end of the given shape collection at the specified coordinates.

### Returns

The chart that was added to the shape collection.



```python
@staticmethod
def add_chart_from_workbook(shapes, x, y, workbook_path, worksheet_name, chart_name, embed_workbook):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| shapes | [`IShapeCollection`](/slides/python-net/aspose.slides/ishapecollection) | The shape collection to which the chart will be added. |
| x | **float** | The X coordinate for positioning the chart. |
| y | **float** | The Y coordinate for positioning the chart. |
| workbook_path | **str** | The file path to the workbook containing the chart. |
| worksheet_name | **str** | The name of the worksheet that contains the chart. |
| chart_name | **str** | The name of the chart to be added. |
| embed_workbook | **bool** | If `true`, the workbook will be embedded in the chart; <br/><br/>            if `false`, the chart will link to the external workbook. |

### Examples

Example:

### Exceptions

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Thrown when any required parameter is None, empty, or if the chart cannot be found in the workbook. |
| **RuntimeError(Proxy error(IOException))** | Thrown when an I/O error occurs while accessing the file. |
| **RuntimeError(Proxy error(InvalidOperationException))** | Thrown when the input data is in an unsupported format. |



### See Also
* class [`ExcelWorkbookImporter`](/slides/python-net/aspose.slides.importing/excelworkbookimporter)
* class [`IExcelDataWorkbook`](/slides/python-net/aspose.slides.excel/iexceldataworkbook)
* class [`IShapeCollection`](/slides/python-net/aspose.slides/ishapecollection)
* module [`aspose.slides.importing`](/slides/python-net/aspose.slides.importing)
* library [`Aspose.Slides`](/slides/python-net)

