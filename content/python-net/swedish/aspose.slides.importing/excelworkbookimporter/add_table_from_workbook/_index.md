---
title: add_table_from_workbook method
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides.importing/excelworkbookimporter/add_table_from_workbook/
weight: 20
---
## add_table_from_workbook(shapes, x, y, workbook, worksheet_name, cell_range) {#ishapecollection-float-float-asposeslidesexceliexceldataworkbook-str-str}
Hämtar en tabell från den angivna Excel-arbetsboken och lägger till den i slutet av den angivna shape-samlingen på de angivna koordinaterna.

### Returnerar

Tabellen som lades till i shape-samlingen.



```python
@staticmethod
def add_table_from_workbook(shapes, x, y, workbook, worksheet_name, cell_range):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| shapes | [`IShapeCollection`](/slides/python-net/sv/aspose.slides/ishapecollection) | Shape-samlingen som tabellen kommer att läggas till i. |
| x | **float** | X-koordinaten för placering av tabellen. |
| y | **float** | Y-koordinaten för placering av tabellen. |
| workbook | [`IExcelDataWorkbook`](/slides/python-net/sv/aspose.slides.excel/iexceldataworkbook) | Excel-arbetsboken. |
| worksheet_name | **str** | Namnet på kalkylbladet som innehåller tabellen. |
| cell_range | **str** | Cellområdet som definierar tabellen (till exempel "A1:D10"). |

### Undantag

| Undantag | Beskrivning |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Kastas när någon obligatorisk parameter är None eller tom, eller när det angivna kalkylbladet eller cellområdet är ogiltigt. |
| **RuntimeError(Proxy error(InvalidOperationException))** | Kastas när indata är i ett format som inte stöds. |


## add_table_from_workbook(shapes, x, y, workbook_path, worksheet_name, cell_range) {#ishapecollection-float-float-str-str-str}
Hämtar en tabell från den angivna Excel-arbetsbokfilen och lägger till den i slutet av den angivna shape-samlingen på de angivna koordinaterna.

### Returnerar

Tabellen som lades till i shape-samlingen.



```python
@staticmethod
def add_table_from_workbook(shapes, x, y, workbook_path, worksheet_name, cell_range):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| shapes | [`IShapeCollection`](/slides/python-net/sv/aspose.slides/ishapecollection) | Shape-samlingen som tabellen kommer att läggas till i. |
| x | **float** | X-koordinaten för placering av tabellen. |
| y | **float** | Y-koordinaten för placering av tabellen. |
| workbook_path | **str** | Sökvägen till Excel-arbetsbokfilen. |
| worksheet_name | **str** | Namnet på kalkylbladet som innehåller tabellen. |
| cell_range | **str** | Cellområdet som definierar tabellen (till exempel "A1:D10"). |

### Undantag

| Undantag | Beskrivning |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Kastas när någon obligatorisk parameter är None eller tom, eller när det angivna kalkylbladet eller cellområdet är ogiltigt. |
| **RuntimeError(Proxy error(IOException))** | Kastas när ett I/O-fel uppstår vid åtkomst av arbetsbokfilen. |
| **RuntimeError(Proxy error(InvalidOperationException))** | Kastas när indata är i ett format som inte stöds. |


## add_table_from_workbook(shapes, x, y, workbook_stream, worksheet_name, cell_range) {#ishapecollection-float-float-iorawiobase-str-str}
Hämtar en tabell från den angivna Excel-arbetsbokfilen och lägger till den i slutet av den angivna shape-samlingen på de angivna koordinaterna.

### Returnerar

Tabellen som lades till i shape-samlingen.



```python
@staticmethod
def add_table_from_workbook(shapes, x, y, workbook_stream, worksheet_name, cell_range):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| shapes | [`IShapeCollection`](/slides/python-net/sv/aspose.slides/ishapecollection) | Shape-samlingen som tabellen kommer att läggas till i. |
| x | **float** | X-koordinaten för placering av tabellen. |
| y | **float** | Y-koordinaten för placering av tabellen. |
| workbook_stream | **io.RawIOBase** | En ström som innehåller arbetsbokdata. |
| worksheet_name | **str** | Namnet på kalkylbladet som innehåller tabellen. |
| cell_range | **str** | Cellområdet som definierar tabellen (till exempel "A1:D10"). |

### Undantag

| Undantag | Beskrivning |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Kastas när någon obligatorisk parameter är None eller tom, eller när det angivna kalkylbladet eller cellområdet är ogiltigt. |
| **RuntimeError(Proxy error(InvalidOperationException))** | Kastas när indata är i ett format som inte stöds. |



### Se också
* klass [`ExcelWorkbookImporter`](/slides/python-net/sv/aspose.slides.importing/excelworkbookimporter)
* klass [`IExcelDataWorkbook`](/slides/python-net/sv/aspose.slides.excel/iexceldataworkbook)
* klass [`IShapeCollection`](/slides/python-net/sv/aspose.slides/ishapecollection)
* klass [`ITable`](/slides/python-net/sv/aspose.slides/itable)
* modul [`aspose.slides.importing`](/slides/python-net/sv/aspose.slides.importing)
* bibliotek [`Aspose.Slides`](/slides/python-net)