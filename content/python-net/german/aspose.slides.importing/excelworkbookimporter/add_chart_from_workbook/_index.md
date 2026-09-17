---
title: add_chart_from_workbook method
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides.importing/excelworkbookimporter/add_chart_from_workbook/
weight: 10
---
## add_chart_from_workbook(shapes, x, y, workbook, worksheet_name, chart_index, embed_all_workbook) {#ishapecollection-float-float-asposeslidesexceliexceldataworkbook-str-int-bool}
Ruft ein Diagramm aus der angegebenen Excel-Arbeitsmappe ab und fügt es am Ende der angegebenen Formsammlung an den angegebenen Koordinaten ein.

### Rückgabewert

Das Diagramm, das der Formsammlung hinzugefügt wurde.



```python
@staticmethod
def add_chart_from_workbook(shapes, x, y, workbook, worksheet_name, chart_index, embed_all_workbook):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| shapes | [`IShapeCollection`](/slides/python-net/de/aspose.slides/ishapecollection) | Die Formsammlung, zu der das Diagramm hinzugefügt wird. |
| x | **float** | Die X-Koordinate für die Positionierung des Diagramms. |
| y | **float** | Die Y-Koordinate für die Positionierung des Diagramms. |
| workbook | [`IExcelDataWorkbook`](/slides/python-net/de/aspose.slides.excel/iexceldataworkbook) | Die Excel-Arbeitsmappe. |
| worksheet_name | **str** | Der Name des Arbeitsblatts, das das Diagramm enthält. |
| chart_index | **int** | Der nullbasierte Index der Diagrammform, die eingefügt werden soll. <br/><br/>            Dieser Index kann mithilfe der **Aspose.Slides.Excel.IExcelDataWorkbook.GetChartsFromWorksheet(Syste** Methode ermittelt werden. |
| embed_all_workbook | **bool** | Wenn `true`, wird die gesamte Arbeitsmappe in das Diagramm eingebettet; <br/><br/>            wenn `false`, werden nur die Diagrammdaten eingebettet. |

### Ausnahmen

| Ausnahme | Beschreibung |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Wird ausgelöst, wenn ein erforderlicher Parameter None, leer ist oder das Diagramm in der Arbeitsmappe nicht gefunden werden kann. |


## add_chart_from_workbook(shapes, x, y, workbook, worksheet_name, chart_name, embed_all_workbook) {#ishapecollection-float-float-asposeslidesexceliexceldataworkbook-str-str-bool}
Ruft ein Diagramm aus der angegebenen Excel-Arbeitsmappe ab und fügt es am Ende der angegebenen Formsammlung an den angegebenen Koordinaten ein.

### Rückgabewert

Das Diagramm, das der Formsammlung hinzugefügt wurde.



```python
@staticmethod
def add_chart_from_workbook(shapes, x, y, workbook, worksheet_name, chart_name, embed_all_workbook):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| shapes | [`IShapeCollection`](/slides/python-net/de/aspose.slides/ishapecollection) | Die Formsammlung, zu der das Diagramm hinzugefügt wird. |
| x | **float** | Die X-Koordinate für die Positionierung des Diagramms. |
| y | **float** | Die Y-Koordinate für die Positionierung des Diagramms. |
| workbook | [`IExcelDataWorkbook`](/slides/python-net/de/aspose.slides.excel/iexceldataworkbook) | Die Excel-Arbeitsmappe. |
| worksheet_name | **str** | Der Name des Arbeitsblatts, das das Diagramm enthält. |
| chart_name | **str** | Der Name des hinzuzufügenden Diagramms. |
| embed_all_workbook | **bool** | Wenn `true`, wird die gesamte Arbeitsmappe in das Diagramm eingebettet; <br/><br/>            wenn `false`, werden nur die Diagrammdaten eingebettet. |

### Ausnahmen

| Ausnahme | Beschreibung |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Wird ausgelöst, wenn ein erforderlicher Parameter None, leer ist oder das Diagramm in der Arbeitsmappe nicht gefunden werden kann. |


## add_chart_from_workbook(shapes, x, y, workbook_stream, worksheet_name, chart_name, embed_all_workbook) {#ishapecollection-float-float-iorawiobase-str-str-bool}
Ruft ein Diagramm aus der angegebenen Excel-Arbeitsmappe ab und fügt es am Ende der angegebenen Formsammlung an den angegebenen Koordinaten ein.

### Rückgabewert

Das Diagramm, das der Formsammlung hinzugefügt wurde.



```python
@staticmethod
def add_chart_from_workbook(shapes, x, y, workbook_stream, worksheet_name, chart_name, embed_all_workbook):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| shapes | [`IShapeCollection`](/slides/python-net/de/aspose.slides/ishapecollection) | Die Formsammlung, zu der das Diagramm hinzugefügt wird. |
| x | **float** | Die X-Koordinate für die Positionierung des Diagramms. |
| y | **float** | Die Y-Koordinate für die Positionierung des Diagramms. |
| workbook_stream | **io.RawIOBase** | Ein Stream, der die Arbeitsmappendaten enthält. |
| worksheet_name | **str** | Der Name des Arbeitsblatts, das das Diagramm enthält. |
| chart_name | **str** | Der Name des hinzuzufügenden Diagramms. |
| embed_all_workbook | **bool** | Wenn `true`, wird die gesamte Arbeitsmappe in das Diagramm eingebettet; <br/><br/>            wenn `false`, werden nur die Diagrammdaten eingebettet. |

### Ausnahmen

| Ausnahme | Beschreibung |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Wird ausgelöst, wenn ein erforderlicher Parameter None, leer ist oder das Diagramm in der Arbeitsmappe nicht gefunden werden kann. |
| **RuntimeError(Proxy error(InvalidOperationException))** | Wird ausgelöst, wenn die Eingabedaten in einem nicht unterstützten Format vorliegen. |


## add_chart_from_workbook(shapes, x, y, workbook_path, worksheet_name, chart_name, embed_workbook) {#ishapecollection-float-float-str-str-str-bool}
Ruft ein Diagramm aus der angegebenen Excel-Arbeitsmappe ab und fügt es am Ende der angegebenen Formsammlung an den angegebenen Koordinaten ein.

### Rückgabewert

Das Diagramm, das der Formsammlung hinzugefügt wurde.



```python
@staticmethod
def add_chart_from_workbook(shapes, x, y, workbook_path, worksheet_name, chart_name, embed_workbook):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| shapes | [`IShapeCollection`](/slides/python-net/de/aspose.slides/ishapecollection) | Die Formsammlung, zu der das Diagramm hinzugefügt wird. |
| x | **float** | Die X-Koordinate für die Positionierung des Diagramms. |
| y | **float** | Die Y-Koordinate für die Positionierung des Diagramms. |
| workbook_path | **str** | Der Dateipfad zur Arbeitsmappe, die das Diagramm enthält. |
| worksheet_name | **str** | Der Name des Arbeitsblatts, das das Diagramm enthält. |
| chart_name | **str** | Der Name des hinzuzufügenden Diagramms. |
| embed_workbook | **bool** | Wenn `true`, wird die Arbeitsmappe in das Diagramm eingebettet; <br/><br/>            wenn `false`, wird das Diagramm mit der externen Arbeitsmappe verknüpft. |

### Ausnahmen

| Ausnahme | Beschreibung |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Wird ausgelöst, wenn ein erforderlicher Parameter None, leer ist oder das Diagramm in der Arbeitsmappe nicht gefunden werden kann. |
| **RuntimeError(Proxy error(IOException))** | Wird ausgelöst, wenn beim Zugriff auf die Datei ein I/O-Fehler auftritt. |
| **RuntimeError(Proxy error(InvalidOperationException))** | Wird ausgelöst, wenn die Eingabedaten in einem nicht unterstützten Format vorliegen. |



### Siehe auch
* Klasse [`ExcelWorkbookImporter`](/slides/python-net/de/aspose.slides.importing/excelworkbookimporter)
* Klasse [`IExcelDataWorkbook`](/slides/python-net/de/aspose.slides.excel/iexceldataworkbook)
* Klasse [`IShapeCollection`](/slides/python-net/de/aspose.slides/ishapecollection)
* Modul [`aspose.slides.importing`](/slides/python-net/de/aspose.slides.importing)
* Bibliothek [`Aspose.Slides`](/slides/python-net)