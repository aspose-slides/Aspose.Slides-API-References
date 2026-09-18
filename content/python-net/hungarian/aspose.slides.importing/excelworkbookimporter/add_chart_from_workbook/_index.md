---
title: add_chart_from_workbook method
second_title: Aspose.Slides for Python via .NET API referenciája
description: 
type: docs
url: /hu/aspose.slides.importing/excelworkbookimporter/add_chart_from_workbook/
weight: 10
---
## add_chart_from_workbook(shapes, x, y, workbook, worksheet_name, chart_index, embed_all_workbook) {#ishapecollection-float-float-asposeslidesexceliexceldataworkbook-str-int-bool}
Lekér egy diagramot a megadott Excel munkafüzetből, és hozzáadja a megadott alakgyűjtemény végéhez a megadott koordinátákon.

### Visszatérési érték

A diagram, amely hozzá lett adva az alakgyűjteményhez.



```python
@staticmethod
def add_chart_from_workbook(shapes, x, y, workbook, worksheet_name, chart_index, embed_all_workbook):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| shapes | [`IShapeCollection`](/slides/python-net/hu/aspose.slides/ishapecollection) | Az alakgyűjtemény, amelyhez a diagram hozzá lesz adva. |
| x | **float** | Az X koordináta a diagram elhelyezéséhez. |
| y | **float** | Az Y koordináta a diagram elhelyezéséhez. |
| workbook | [`IExcelDataWorkbook`](/slides/python-net/hu/aspose.slides.excel/iexceldataworkbook) | Az Excel munkafüzet. |
| worksheet_name | **str** | A munkalap neve, amely a diagramot tartalmazza. |
| chart_index | **int** | A beszúrandó diagram alak nullától indexelt száma. <br/><br/>            Ez az index lekérhető a **Aspose.Slides.Excel.IExcelDataWorkbook.GetChartsFromWorksheet(Syste** metódussal. |
| embed_all_workbook | **bool** | Ha `true`, a teljes munkafüzet beágyazásra kerül a diagramba; <br/><br/>            ha `false`, csak a diagram adatai lesznek beágyazva. |

### Kivételek

| Kivétel | Leírás |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Akkor dobásra kerül, ha bármely kötelező paraméter None vagy üres, vagy ha a diagram nem található a munkafüzetben. |


## add_chart_from_workbook(shapes, x, y, workbook, worksheet_name, chart_name, embed_all_workbook) {#ishapecollection-float-float-asposeslidesexceliexceldataworkbook-str-str-bool}
Lekér egy diagramot a megadott Excel munkafüzetből, és hozzáadja a megadott alakgyűjtemény végéhez a megadott koordinátákon.

### Visszatérési érték

A diagram, amely hozzá lett adva az alakgyűjteményhez.



```python
@staticmethod
def add_chart_from_workbook(shapes, x, y, workbook, worksheet_name, chart_name, embed_all_workbook):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| shapes | [`IShapeCollection`](/slides/python-net/hu/aspose.slides/ishapecollection) | Az alakgyűjtemény, amelyhez a diagram hozzá lesz adva. |
| x | **float** | Az X koordináta a diagram elhelyezéséhez. |
| y | **float** | Az Y koordináta a diagram elhelyezéséhez. |
| workbook | [`IExcelDataWorkbook`](/slides/python-net/hu/aspose.slides.excel/iexceldataworkbook) | Az Excel munkafüzet. |
| worksheet_name | **str** | A munkalap neve, amely a diagramot tartalmazza. |
| chart_name | **str** | A hozzáadandó diagram neve. |
| embed_all_workbook | **bool** | Ha `true`, a teljes munkafüzet beágyazásra kerül a diagramba; <br/><br/>            ha `false`, csak a diagram adatai lesznek beágyazva. |

### Kivételek

| Kivétel | Leírás |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Akkor dobásra kerül, ha bármely kötelező paraméter None vagy üres, vagy ha a diagram nem található a munkafüzetben. |


## add_chart_from_workbook(shapes, x, y, workbook_stream, worksheet_name, chart_name, embed_all_workbook) {#ishapecollection-float-float-iorawiobase-str-str-bool}
Lekér egy diagramot a megadott Excel munkafüzetből, és hozzáadja a megadott alakgyűjtemény végéhez a megadott koordinátákon.

### Visszatérési érték

A diagram, amely hozzá lett adva az alakgyűjteményhez.



```python
@staticmethod
def add_chart_from_workbook(shapes, x, y, workbook_stream, worksheet_name, chart_name, embed_all_workbook):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| shapes | [`IShapeCollection`](/slides/python-net/hu/aspose.slides/ishapecollection) | Az alakgyűjtemény, amelyhez a diagram hozzá lesz adva. |
| x | **float** | Az X koordináta a diagram elhelyezéséhez. |
| y | **float** | Az Y koordináta a diagram elhelyezéséhez. |
| workbook_stream | **io.RawIOBase** | Egy adatfolyam, amely a munkafüzet adatát tartalmazza. |
| worksheet_name | **str** | A munkalap neve, amely a diagramot tartalmazza. |
| chart_name | **str** | A hozzáadandó diagram neve. |
| embed_all_workbook | **bool** | Ha `true`, a teljes munkafüzet beágyazásra kerül a diagramba; <br/><br/>            ha `false`, csak a diagram adatai lesznek beágyazva. |

### Kivételek

| Kivétel | Leírás |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Akkor dobásra kerül, ha bármely kötelező paraméter None vagy üres, vagy ha a diagram nem található a munkafüzetben. |
| **RuntimeError(Proxy error(InvalidOperationException))** | Akkor dobásra kerül, ha a bemeneti adat egy nem támogatott formátumban van. |


## add_chart_from_workbook(shapes, x, y, workbook_path, worksheet_name, chart_name, embed_workbook) {#ishapecollection-float-float-str-str-str-bool}
Lekér egy diagramot a megadott Excel munkafüzetből, és hozzáadja a megadott alakgyűjtemény végéhez a megadott koordinátákon.

### Visszatérési érték

A diagram, amely hozzá lett adva az alakgyűjteményhez.



```python
@staticmethod
def add_chart_from_workbook(shapes, x, y, workbook_path, worksheet_name, chart_name, embed_workbook):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| shapes | [`IShapeCollection`](/slides/python-net/hu/aspose.slides/ishapecollection) | Az alakgyűjtemény, amelyhez a diagram hozzá lesz adva. |
| x | **float** | Az X koordináta a diagram elhelyezéséhez. |
| y | **float** | Az Y koordináta a diagram elhelyezéséhez. |
| workbook_path | **str** | A fájl útvonala, amely a diagramot tartalmazó munkafüzetet tartalmazza. |
| worksheet_name | **str** | A munkalap neve, amely a diagramot tartalmazza. |
| chart_name | **str** | A hozzáadandó diagram neve. |
| embed_workbook | **bool** | Ha `true`, a munkafüzet be lesz ágyazva a diagramba; <br/><br/>            ha `false`, a diagram külső munkafüzetre hivatkozik. |

### Kivételek

| Kivétel | Leírás |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Akkor dobásra kerül, ha bármely kötelező paraméter None vagy üres, vagy ha a diagram nem található a munkafüzetben. |
| **RuntimeError(Proxy error(IOException))** | Akkor dobásra kerül, ha I/O hiba történik a fájl elérése közben. |
| **RuntimeError(Proxy error(InvalidOperationException))** | Akkor dobásra kerül, ha a bemeneti adat egy nem támogatott formátumban van. |



### Lásd még
* osztály [`ExcelWorkbookImporter`](/slides/python-net/hu/aspose.slides.importing/excelworkbookimporter)
* osztály [`IExcelDataWorkbook`](/slides/python-net/hu/aspose.slides.excel/iexceldataworkbook)
* osztály [`IShapeCollection`](/slides/python-net/hu/aspose.slides/ishapecollection)
* modul [`aspose.slides.importing`](/slides/python-net/hu/aspose.slides.importing)
* könyvtár [`Aspose.Slides`](/slides/python-net)