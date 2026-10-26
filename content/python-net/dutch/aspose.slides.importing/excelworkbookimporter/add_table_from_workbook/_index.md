---
title: add_table_from_workbook method
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides.importing/excelworkbookimporter/add_table_from_workbook/
weight: 20
---
## add_table_from_workbook(shapes, x, y, workbook, worksheet_name, cell_range) {#ishapecollection-float-float-asposeslidesexceliexceldataworkbook-str-str}
Haalt een tabel op uit de opgegeven Excel-werkmap en voegt deze toe aan het einde van de opgegeven vormverzameling op de opgegeven coördinaten.

### Retour

De tabel die aan de vormverzameling is toegevoegd.



```python
@staticmethod
def add_table_from_workbook(shapes, x, y, workbook, worksheet_name, cell_range):
    ...
```


| Parameter | Type | Beschrijving |
| :- | :- | :- |
| shapes | [`IShapeCollection`](/slides/python-net/nl/aspose.slides/ishapecollection) | De vormverzameling waaraan de tabel wordt toegevoegd. |
| x | **float** | De X-coördinaat voor het positioneren van de tabel. |
| y | **float** | De Y-coördinaat voor het positioneren van de tabel. |
| workbook | [`IExcelDataWorkbook`](/slides/python-net/nl/aspose.slides.excel/iexceldataworkbook) | De Excel-werkmap. |
| worksheet_name | **str** | De naam van het werkblad dat de tabel bevat. |
| cell_range | **str** | Het celbereik dat de tabel definieert (bijvoorbeeld, "A1:D10"). |

### Uitzonderingen

| Uitzondering | Beschrijving |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Geboden wanneer een vereist parameter None of leeg is, of wanneer het opgegeven werkblad of celbereik ongeldig is. |
| **RuntimeError(Proxy error(InvalidOperationException))** | Geboden wanneer de invoergegevens in een niet-ondersteund formaat zijn. |


## add_table_from_workbook(shapes, x, y, workbook_path, worksheet_name, cell_range) {#ishapecollection-float-float-str-str-str}
Haalt een tabel op uit het opgegeven Excel-werkmapbestand en voegt deze toe aan het einde van de opgegeven vormverzameling op de opgegeven coördinaten.

### Retour

De tabel die aan de vormverzameling is toegevoegd.



```python
@staticmethod
def add_table_from_workbook(shapes, x, y, workbook_path, worksheet_name, cell_range):
    ...
```


| Parameter | Type | Beschrijving |
| :- | :- | :- |
| shapes | [`IShapeCollection`](/slides/python-net/nl/aspose.slides/ishapecollection) | De vormverzameling waaraan de tabel wordt toegevoegd. |
| x | **float** | De X-coördinaat voor het positioneren van de tabel. |
| y | **float** | De Y-coördinaat voor het positioneren van de tabel. |
| workbook_path | **str** | Het pad naar het Excel-werkmapbestand. |
| worksheet_name | **str** | De naam van het werkblad dat de tabel bevat. |
| cell_range | **str** | Het celbereik dat de tabel definieert (bijvoorbeeld, "A1:D10"). |

### Uitzonderingen

| Uitzondering | Beschrijving |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Geboden wanneer een vereist parameter None of leeg is, of wanneer het opgegeven werkblad of celbereik ongeldig is. |
| **RuntimeError(Proxy error(IOException))** | Geboden wanneer er een I/O-fout optreedt bij het benaderen van het werkmapbestand. |
| **RuntimeError(Proxy error(InvalidOperationException))** | Geboden wanneer de invoergegevens in een niet-ondersteund formaat zijn. |


## add_table_from_workbook(shapes, x, y, workbook_stream, worksheet_name, cell_range) {#ishapecollection-float-float-iorawiobase-str-str}
Haalt een tabel op uit het opgegeven Excel-werkmapbestand en voegt deze toe aan het einde van de opgegeven vormverzameling op de opgegeven coördinaten.

### Retour

De tabel die aan de vormverzameling is toegevoegd.



```python
@staticmethod
def add_table_from_workbook(shapes, x, y, workbook_stream, worksheet_name, cell_range):
    ...
```


| Parameter | Type | Beschrijving |
| :- | :- | :- |
| shapes | [`IShapeCollection`](/slides/python-net/nl/aspose.slides/ishapecollection) | De vormverzameling waaraan de tabel wordt toegevoegd. |
| x | **float** | De X-coördinaat voor het positioneren van de tabel. |
| y | **float** | De Y-coördinaat voor het positioneren van de tabel. |
| workbook_stream | **io.RawIOBase** | Een stream die de werkmapgegevens bevat. |
| worksheet_name | **str** | De naam van het werkblad dat de tabel bevat. |
| cell_range | **str** | Het celbereik dat de tabel definieert (bijvoorbeeld, "A1:D10"). |

### Uitzonderingen

| Uitzondering | Beschrijving |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Geboden wanneer een vereist parameter None of leeg is, of wanneer het opgegeven werkblad of celbereik ongeldig is. |
| **RuntimeError(Proxy error(InvalidOperationException))** | Geboden wanneer de invoergegevens in een niet-ondersteund formaat zijn. |



### Zie ook
* klasse [`ExcelWorkbookImporter`](/slides/python-net/nl/aspose.slides.importing/excelworkbookimporter)
* klasse [`IExcelDataWorkbook`](/slides/python-net/nl/aspose.slides.excel/iexceldataworkbook)
* klasse [`IShapeCollection`](/slides/python-net/nl/aspose.slides/ishapecollection)
* klasse [`ITable`](/slides/python-net/nl/aspose.slides/itable)
* module [`aspose.slides.importing`](/slides/python-net/nl/aspose.slides.importing)
* bibliotheek [`Aspose.Slides`](/slides/python-net)