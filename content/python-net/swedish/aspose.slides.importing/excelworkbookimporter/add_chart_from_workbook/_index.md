---
title: add_chart_from_workbook method
second_title: Aspose.Slides för Python via .NET API Referens
description: 
type: docs
url: /sv/aspose.slides.importing/excelworkbookimporter/add_chart_from_workbook/
weight: 10
---
## add_chart_from_workbook(shapes, x, y, workbook, worksheet_name, chart_index, embed_all_workbook) {#ishapecollection-float-float-asposeslidesexceliexceldataworkbook-str-int-bool}
Hämtar ett chart från den angivna Excel workbook och lägger till det i slutet av den givna shape collection på de angivna koordinaterna.

### Returns

The chart that was added to the shape collection.



```python
@staticmethod
def add_chart_from_workbook(shapes, x, y, workbook, worksheet_name, chart_index, embed_all_workbook):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| shapes | [`IShapeCollection`](/slides/python-net/sv/aspose.slides/ishapecollection) | Den shape collection till vilken chart kommer att läggas till. |
| x | **float** | X-koordinaten för att positionera chart. |
| y | **float** | Y-koordinaten för att positionera chart. |
| workbook | [`IExcelDataWorkbook`](/slides/python-net/sv/aspose.slides.excel/iexceldataworkbook) | Excel workbook. |
| worksheet_name | **str** | Namnet på worksheet som innehåller chart. |
| chart_index | **int** | Det nollbaserade indexet för chart shape att infoga. <br/><br/>            Detta index kan erhållas med **Aspose.Slides.Excel.IExcelDataWorkbook.GetChartsFromWorksheet(Syste** method. |
| embed_all_workbook | **bool** | Om `true` kommer hela workbook att bäddas in i chart; <br/><br/>            om `false` kommer endast chart-data att bäddas in. |

### Exceptions

| Undantag | Beskrivning |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Kastas när någon obligatorisk parameter är None, tom, eller om chart inte kan hittas i workbook. |


## add_chart_from_workbook(shapes, x, y, workbook, worksheet_name, chart_name, embed_all_workbook) {#ishapecollection-float-float-asposeslidesexceliexceldataworkbook-str-str-bool}
Hämtar ett chart från den angivna Excel workbook och lägger till det i slutet av den givna shape collection på de angivna koordinaterna.

### Returns

The chart that was added to the shape collection.



```python
@staticmethod
def add_chart_from_workbook(shapes, x, y, workbook, worksheet_name, chart_name, embed_all_workbook):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| shapes | [`IShapeCollection`](/slides/python-net/sv/aspose.slides/ishapecollection) | Den shape collection till vilken chart kommer att läggas till. |
| x | **float** | X-koordinaten för att positionera chart. |
| y | **float** | Y-koordinaten för att positionera chart. |
| workbook | [`IExcelDataWorkbook`](/slides/python-net/sv/aspose.slides.excel/iexceldataworkbook) | Excel workbook. |
| worksheet_name | **str** | Namnet på worksheet som innehåller chart. |
| chart_name | **str** | Namnet på chart som ska läggas till. |
| embed_all_workbook | **bool** | Om `true` kommer hela workbook att bäddas in i chart; <br/><br/>            om `false` kommer endast chart-data att bäddas in. |

### Exceptions

| Undantag | Beskrivning |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Kastas när någon obligatorisk parameter är None, tom, eller om chart inte kan hittas i workbook. |


## add_chart_from_workbook(shapes, x, y, workbook_stream, worksheet_name, chart_name, embed_all_workbook) {#ishapecollection-float-float-iorawiobase-str-str-bool}
Hämtar ett chart från den angivna Excel workbook och lägger till det i slutet av den givna shape collection på de angivna koordinaterna.

### Returns

The chart that was added to the shape collection.



```python
@staticmethod
def add_chart_from_workbook(shapes, x, y, workbook_stream, worksheet_name, chart_name, embed_all_workbook):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| shapes | [`IShapeCollection`](/slides/python-net/sv/aspose.slides/ishapecollection) | Den shape collection till vilken chart kommer att läggas till. |
| x | **float** | X-koordinaten för att positionera chart. |
| y | **float** | Y-koordinaten för att positionera chart. |
| workbook_stream | **io.RawIOBase** | En ström som innehåller workbook-data. |
| worksheet_name | **str** | Namnet på worksheet som innehåller chart. |
| chart_name | **str** | Namnet på chart som ska läggas till. |
| embed_all_workbook | **bool** | Om `true` kommer hela workbook att bäddas in i chart; <br/><br/>            om `false` kommer endast chart-data att bäddas in. |

### Exceptions

| Undantag | Beskrivning |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Kastas när någon obligatorisk parameter är None, tom, eller om chart inte kan hittas i workbook. |
| **RuntimeError(Proxy error(InvalidOperationException))** | Kastas när indata är i ett format som inte stöds. |


## add_chart_from_workbook(shapes, x, y, workbook_path, worksheet_name, chart_name, embed_workbook) {#ishapecollection-float-float-str-str-str-bool}
Hämtar ett chart från den angivna Excel workbook och lägger till det i slutet av den givna shape collection på de angivna koordinaterna.

### Returns

The chart that was added to the shape collection.



```python
@staticmethod
def add_chart_from_workbook(shapes, x, y, workbook_path, worksheet_name, chart_name, embed_workbook):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| shapes | [`IShapeCollection`](/slides/python-net/sv/aspose.slides/ishapecollection) | Den shape collection till vilken chart kommer att läggas till. |
| x | **float** | X-koordinaten för att positionera chart. |
| y | **float** | Y-koordinaten för att positionera chart. |
| workbook_path | **str** | Filvägen till workbook som innehåller chart. |
| worksheet_name | **str** | Namnet på worksheet som innehåller chart. |
| chart_name | **str** | Namnet på chart som ska läggas till. |
| embed_workbook | **bool** | Om `true` kommer workbook att bäddas in i chart; <br/><br/>            om `false` kommer chart att länka till den externa workbook. |

### Exceptions

| Undantag | Beskrivning |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Kastas när någon obligatorisk parameter är None, tom, eller om chart inte kan hittas i workbook. |
| **RuntimeError(Proxy error(IOException))** | Kastas när ett I/O-fel inträffar vid åtkomst av filen. |
| **RuntimeError(Proxy error(InvalidOperationException))** | Kastas när indata är i ett format som inte stöds. |



### See Also
* klass [`ExcelWorkbookImporter`](/slides/python-net/sv/aspose.slides.importing/excelworkbookimporter)
* klass [`IExcelDataWorkbook`](/slides/python-net/sv/aspose.slides.excel/iexceldataworkbook)
* klass [`IShapeCollection`](/slides/python-net/sv/aspose.slides/ishapecollection)
* modul [`aspose.slides.importing`](/slides/python-net/sv/aspose.slides.importing)
* bibliotek [`Aspose.Slides`](/slides/python-net)