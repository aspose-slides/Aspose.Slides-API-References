---
title: add_table_from_workbook method
second_title: Aspose.Slides Pythonhoz .NET-en keresztül API Referencia
description: 
type: docs
url: /hu/aspose.slides.importing/excelworkbookimporter/add_table_from_workbook/
weight: 20
---
## add_table_from_workbook(shapes, x, y, workbook, worksheet_name, cell_range) {#ishapecollection-float-float-asposeslidesexceliexceldataworkbook-str-str}
Lekéri a táblázatot a megadott Excel munkafüzetből, és a megadott koordinátákon a megadott alakzatgyűjtemény végéhez adja hozzá.

### Visszatér

A táblázat, amelyet hozzáadtak az alakzatgyűjteményhez.



```python
@staticmethod
def add_table_from_workbook(shapes, x, y, workbook, worksheet_name, cell_range):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| shapes | [`IShapeCollection`](/slides/python-net/hu/aspose.slides/ishapecollection) | The shape collection to which the table will be added. |
| x | **float** | The X coordinate for positioning the table. |
| y | **float** | The Y coordinate for positioning the table. |
| workbook | [`IExcelDataWorkbook`](/slides/python-net/hu/aspose.slides.excel/iexceldataworkbook) | The Excel workbook. |
| worksheet_name | **str** | The name of the worksheet that contains the table. |
| cell_range | **str** | The cell range that defines the table (for example, "A1:D10"). |

### Kivételek

| Kivétel | Leírás |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Kivétel keletkezik, ha bármely kötelező paraméter None vagy üres, vagy ha a megadott munkalap vagy cellatartomány érvénytelen. |
| **RuntimeError(Proxy error(InvalidOperationException))** | Kivétel keletkezik, ha a bemeneti adat egy nem támogatott formátumban van. |


## add_table_from_workbook(shapes, x, y, workbook_path, worksheet_name, cell_range) {#ishapecollection-float-float-str-str-str}
Lekéri a táblázatot a megadott Excel munkafüzetfájlból, és a megadott koordinátákon a megadott alakzatgyűjtemény végéhez adja hozzá.

### Visszatér

A táblázat, amelyet hozzáadtak az alakzatgyűjteményhez.



```python
@staticmethod
def add_table_from_workbook(shapes, x, y, workbook_path, worksheet_name, cell_range):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| shapes | [`IShapeCollection`](/slides/python-net/hu/aspose.slides/ishapecollection) | The shape collection to which the table will be added. |
| x | **float** | The X coordinate for positioning the table. |
| y | **float** | The Y coordinate for positioning the table. |
| workbook_path | **str** | The path to the Excel workbook file. |
| worksheet_name | **str** | The name of the worksheet that contains the table. |
| cell_range | **str** | The cell range that defines the table (for example, "A1:D10"). |

### Kivételek

| Kivétel | Leírás |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Kivétel keletkezik, ha bármely kötelező paraméter None vagy üres, vagy ha a megadott munkalap vagy cellatartomány érvénytelen. |
| **RuntimeError(Proxy error(IOException))** | Kivétel keletkezik, ha I/O hiba történik a munkafüzetfájl elérése közben. |
| **RuntimeError(Proxy error(InvalidOperationException))** | Kivétel keletkezik, ha a bemeneti adat egy nem támogatott formátumban van. |


## add_table_from_workbook(shapes, x, y, workbook_stream, worksheet_name, cell_range) {#ishapecollection-float-float-iorawiobase-str-str}
Lekéri a táblázatot a megadott Excel workbook streamből, és a megadott koordinátákon a megadott alakzatgyűjtemény végéhez adja hozzá.

### Visszatér

A táblázat, amelyet hozzáadtak az alakzatgyűjteményhez.



```python
@staticmethod
def add_table_from_workbook(shapes, x, y, workbook_stream, worksheet_name, cell_range):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| shapes | [`IShapeCollection`](/slides/python-net/hu/aspose.slides/ishapecollection) | The shape collection to which the table will be added. |
| x | **float** | The X coordinate for positioning the table. |
| y | **float** | The Y coordinate for positioning the table. |
| workbook_stream | **io.RawIOBase** | A stream containing the workbook data. |
| worksheet_name | **str** | The name of the worksheet that contains the table. |
| cell_range | **str** | The cell range that defines the table (for example, "A1:D10"). |

### Kivételek

| Kivétel | Leírás |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Kivétel keletkezik, ha bármely kötelező paraméter None vagy üres, vagy ha a megadott munkalap vagy cellatartomány érvénytelen. |
| **RuntimeError(Proxy error(InvalidOperationException))** | Kivétel keletkezik, ha a bemeneti adat egy nem támogatott formátumban van. |



### Lásd még
* osztály [`ExcelWorkbookImporter`](/slides/python-net/hu/aspose.slides.importing/excelworkbookimporter)
* osztály [`IExcelDataWorkbook`](/slides/python-net/hu/aspose.slides.excel/iexceldataworkbook)
* osztály [`IShapeCollection`](/slides/python-net/hu/aspose.slides/ishapecollection)
* osztály [`ITable`](/slides/python-net/hu/aspose.slides/itable)
* modul [`aspose.slides.importing`](/slides/python-net/hu/aspose.slides.importing)
* könyvtár [`Aspose.Slides`](/slides/python-net)