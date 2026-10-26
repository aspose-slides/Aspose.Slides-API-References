---
title: add_table_from_workbook method
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides.importing/excelworkbookimporter/add_table_from_workbook/
weight: 20
---
## add_table_from_workbook(shapes, x, y, workbook, worksheet_name, cell_range) {#ishapecollection-float-float-asposeslidesexceliexceldataworkbook-str-str}
Ruft eine Tabelle aus der angegebenen Excel-Arbeitsmappe ab und fügt sie am Ende der angegebenen Formsammlung an den angegebenen Koordinaten ein.

### Rückgabewert

Die Tabelle, die der Formsammlung hinzugefügt wurde.



```python
@staticmethod
def add_table_from_workbook(shapes, x, y, workbook, worksheet_name, cell_range):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| shapes | [`IShapeCollection`](/slides/python-net/de/aspose.slides/ishapecollection) | Die Formsammlung, zu der die Tabelle hinzugefügt wird. |
| x | **float** | Die X-Koordinate zur Positionierung der Tabelle. |
| y | **float** | Die Y-Koordinate zur Positionierung der Tabelle. |
| workbook | [`IExcelDataWorkbook`](/slides/python-net/de/aspose.slides.excel/iexceldataworkbook) | Die Excel-Arbeitsmappe. |
| worksheet_name | **str** | Der Name des Arbeitsblatts, das die Tabelle enthält. |
| cell_range | **str** | Der Zellenbereich, der die Tabelle definiert (z. B. "A1:D10"). |

### Ausnahmen

| Ausnahme | Beschreibung |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Ausgelöst, wenn ein erforderlicher Parameter None oder leer ist oder wenn das angegebene Arbeitsblatt oder der Zellenbereich ungültig ist. |
| **RuntimeError(Proxy error(InvalidOperationException))** | Ausgelöst, wenn die Eingabedaten in einem nicht unterstützten Format vorliegen. |


## add_table_from_workbook(shapes, x, y, workbook_path, worksheet_name, cell_range) {#ishapecollection-float-float-str-str-str}
Ruft eine Tabelle aus der angegebenen Excel-Arbeitsmappe-Datei ab und fügt sie am Ende der angegebenen Formsammlung an den angegebenen Koordinaten ein.

### Rückgabewert

Die Tabelle, die der Formsammlung hinzugefügt wurde.



```python
@staticmethod
def add_table_from_workbook(shapes, x, y, workbook_path, worksheet_name, cell_range):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| shapes | [`IShapeCollection`](/slides/python-net/de/aspose.slides/ishapecollection) | Die Formsammlung, zu der die Tabelle hinzugefügt wird. |
| x | **float** | Die X-Koordinate zur Positionierung der Tabelle. |
| y | **float** | Die Y-Koordinate zur Positionierung der Tabelle. |
| workbook_path | **str** | Der Pfad zur Excel-Arbeitsmappe-Datei. |
| worksheet_name | **str** | Der Name des Arbeitsblatts, das die Tabelle enthält. |
| cell_range | **str** | Der Zellenbereich, der die Tabelle definiert (z. B. "A1:D10"). |

### Ausnahmen

| Ausnahme | Beschreibung |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Ausgelöst, wenn ein erforderlicher Parameter None oder leer ist oder wenn das angegebene Arbeitsblatt oder der Zellenbereich ungültig ist. |
| **RuntimeError(Proxy error(IOException))** | Ausgelöst, wenn beim Zugriff auf die Arbeitsmappendatei ein Ein-/Ausgabefehler auftritt. |
| **RuntimeError(Proxy error(InvalidOperationException))** | Ausgelöst, wenn die Eingabedaten in einem nicht unterstützten Format vorliegen. |


## add_table_from_workbook(shapes, x, y, workbook_stream, worksheet_name, cell_range) {#ishapecollection-float-float-iorawiobase-str-str}
Ruft eine Tabelle aus der angegebenen Excel-Arbeitsmappe-Datei ab und fügt sie am Ende der angegebenen Formsammlung an den angegebenen Koordinaten ein.

### Rückgabewert

Die Tabelle, die der Formsammlung hinzugefügt wurde.



```python
@staticmethod
def add_table_from_workbook(shapes, x, y, workbook_stream, worksheet_name, cell_range):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| shapes | [`IShapeCollection`](/slides/python-net/de/aspose.slides/ishapecollection) | Die Formsammlung, zu der die Tabelle hinzugefügt wird. |
| x | **float** | Die X-Koordinate zur Positionierung der Tabelle. |
| y | **float** | Die Y-Koordinate zur Positionierung der Tabelle. |
| workbook_stream | **io.RawIOBase** | Ein Stream, der die Arbeitsmappendaten enthält. |
| worksheet_name | **str** | Der Name des Arbeitsblatts, das die Tabelle enthält. |
| cell_range | **str** | Der Zellenbereich, der die Tabelle definiert (z. B. "A1:D10"). |

### Ausnahmen

| Ausnahme | Beschreibung |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Ausgelöst, wenn ein erforderlicher Parameter None oder leer ist oder wenn das angegebene Arbeitsblatt oder der Zellenbereich ungültig ist. |
| **RuntimeError(Proxy error(InvalidOperationException))** | Ausgelöst, wenn die Eingabedaten in einem nicht unterstützten Format vorliegen. |



### Siehe auch
* Klasse [`ExcelWorkbookImporter`](/slides/python-net/de/aspose.slides.importing/excelworkbookimporter)
* Klasse [`IExcelDataWorkbook`](/slides/python-net/de/aspose.slides.excel/iexceldataworkbook)
* Klasse [`IShapeCollection`](/slides/python-net/de/aspose.slides/ishapecollection)
* Klasse [`ITable`](/slides/python-net/de/aspose.slides/itable)
* Modul [`aspose.slides.importing`](/slides/python-net/de/aspose.slides.importing)
* library [`Aspose.Slides`](/slides/python-net)