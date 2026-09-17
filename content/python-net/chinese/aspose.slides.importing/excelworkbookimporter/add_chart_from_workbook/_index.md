---
title: add_chart_from_workbook method
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides.importing/excelworkbookimporter/add_chart_from_workbook/
weight: 10
---
## add_chart_from_workbook(shapes, x, y, workbook, worksheet_name, chart_index, embed_all_workbook) {#ishapecollection-float-float-asposeslidesexceliexceldataworkbook-str-int-bool}
检索指定 Excel 工作簿中的图表，并在给定坐标处将其添加到形状集合的末尾。

### 返回

已添加到形状集合中的图表。

```python
@staticmethod
def add_chart_from_workbook(shapes, x, y, workbook, worksheet_name, chart_index, embed_all_workbook):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| shapes | [`IShapeCollection`](/slides/python-net/zh/aspose.slides/ishapecollection) | 将添加图表的形状集合。 |
| x | **float** | 用于定位图表的 X 坐标。 |
| y | **float** | 用于定位图表的 Y 坐标。 |
| workbook | [`IExcelDataWorkbook`](/slides/python-net/zh/aspose.slides.excel/iexceldataworkbook) | Excel 工作簿。 |
| worksheet_name | **str** | 包含图表的工作表名称。 |
| chart_index | **int** | 要插入的图表形状的零基索引。 <br/><br/>            This index can be obtained using the **Aspose.Slides.Excel.IExcelDataWorkbook.GetChartsFromWorksheet(Syste** method. |
| embed_all_workbook | **bool** | 如果 `true`，整个工作簿将嵌入到图表中； <br/><br/>            如果 `false`，仅嵌入图表数据。 |

### 异常

| 异常 | 描述 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | 当任何必需参数为 None、为空，或在工作簿中找不到图表时抛出此异常。 |

## add_chart_from_workbook(shapes, x, y, workbook, worksheet_name, chart_name, embed_all_workbook) {#ishapecollection-float-float-asposeslidesexceliexceldataworkbook-str-str-bool}
检索指定 Excel 工作簿中的图表，并在给定坐标处将其添加到形状集合的末尾。

### 返回

已添加到形状集合中的图表。

```python
@staticmethod
def add_chart_from_workbook(shapes, x, y, workbook, worksheet_name, chart_name, embed_all_workbook):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| shapes | [`IShapeCollection`](/slides/python-net/zh/aspose.slides/ishapecollection) | 将添加图表的形状集合。 |
| x | **float** | 用于定位图表的 X 坐标。 |
| y | **float** | 用于定位图表的 Y 坐标。 |
| workbook | [`IExcelDataWorkbook`](/slides/python-net/zh/aspose.slides.excel/iexceldataworkbook) | Excel 工作簿。 |
| worksheet_name | **str** | 包含图表的工作表名称。 |
| chart_name | **str** | 要添加的图表名称。 |
| embed_all_workbook | **bool** | 如果 `true`，整个工作簿将嵌入到图表中； <br/><br/>            如果 `false`，仅嵌入图表数据。 |

### 异常

| 异常 | 描述 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | 当任何必需参数为 None、为空，或在工作簿中找不到图表时抛出此异常。 |

## add_chart_from_workbook(shapes, x, y, workbook_stream, worksheet_name, chart_name, embed_all_workbook) {#ishapecollection-float-float-iorawiobase-str-str-bool}
检索指定 Excel 工作簿中的图表，并在给定坐标处将其添加到形状集合的末尾。

### 返回

已添加到形状集合中的图表。

```python
@staticmethod
def add_chart_from_workbook(shapes, x, y, workbook_stream, worksheet_name, chart_name, embed_all_workbook):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| shapes | [`IShapeCollection`](/slides/python-net/zh/aspose.slides/ishapecollection) | 将添加图表的形状集合。 |
| x | **float** | 用于定位图表的 X 坐标。 |
| y | **float** | 用于定位图表的 Y 坐标。 |
| workbook_stream | **io.RawIOBase** | 包含工作簿数据的流。 |
| worksheet_name | **str** | 包含图表的工作表名称。 |
| chart_name | **str** | 要添加的图表名称。 |
| embed_all_workbook | **bool** | 如果 `true`，整个工作簿将嵌入到图表中； <br/><br/>            如果 `false`，仅嵌入图表数据。 |

### 异常

| 异常 | 描述 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | 当任何必需参数为 None、为空，或在工作簿中找不到图表时抛出此异常。 |
| **RuntimeError(Proxy error(InvalidOperationException))** | 当输入数据的格式不受支持时抛出此异常。 |

## add_chart_from_workbook(shapes, x, y, workbook_path, worksheet_name, chart_name, embed_workbook) {#ishapecollection-float-float-str-str-str-bool}
检索指定 Excel 工作簿中的图表，并在给定坐标处将其添加到形状集合的末尾。

### 返回

已添加到形状集合中的图表。

```python
@staticmethod
def add_chart_from_workbook(shapes, x, y, workbook_path, worksheet_name, chart_name, embed_workbook):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| shapes | [`IShapeCollection`](/slides/python-net/zh/aspose.slides/ishapecollection) | 将添加图表的形状集合。 |
| x | **float** | 用于定位图表的 X 坐标。 |
| y | **float** | 用于定位图表的 Y 坐标。 |
| workbook_path | **str** | 包含图表的工作簿文件路径。 |
| worksheet_name | **str** | 包含图表的工作表名称。 |
| chart_name | **str** | 要添加的图表名称。 |
| embed_workbook | **bool** | 如果 `true`，工作簿将嵌入到图表中； <br/><br/>            如果 `false`，图表将链接到外部工作簿。 |

### 异常

| 异常 | 描述 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | 当任何必需参数为 None、为空，或在工作簿中找不到图表时抛出此异常。 |
| **RuntimeError(Proxy error(IOException))** | 当访问文件时发生 I/O 错误时抛出此异常。 |
| **RuntimeError(Proxy error(InvalidOperationException))** | 当输入数据的格式不受支持时抛出此异常。 |

### 另请参阅
* 类 [`ExcelWorkbookImporter`](/slides/python-net/zh/aspose.slides.importing/excelworkbookimporter)
* 类 [`IExcelDataWorkbook`](/slides/python-net/zh/aspose.slides.excel/iexceldataworkbook)
* 类 [`IShapeCollection`](/slides/python-net/zh/aspose.slides/ishapecollection)
* 模块 [`aspose.slides.importing`](/slides/python-net/zh/aspose.slides.importing)
* 库 [`Aspose.Slides`](/slides/python-net)