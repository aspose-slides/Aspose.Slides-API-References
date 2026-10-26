---
title: add_chart_from_workbook method
second_title: Aspose.Slides voor Python via .NET API Referentie
description: 
type: docs
url: /nl/aspose.slides.importing/excelworkbookimporter/add_chart_from_workbook/
weight: 10
---
## add_chart_from_workbook(shapes, x, y, workbook, worksheet_name, chart_index, embed_all_workbook) {#ishapecollection-float-float-asposeslidesexceliexceldataworkbook-str-int-bool}
Haalt een diagram op uit de opgegeven Excel-werkmap en voegt het toe aan het einde van de opgegeven vormverzameling op de opgegeven coördinaten.

### Retour

Het diagram dat aan de vormverzameling is toegevoegd.



```python
@staticmethod
def add_chart_from_workbook(shapes, x, y, workbook, worksheet_name, chart_index, embed_all_workbook):
    ...
```


| Parameter | Type | Beschrijving |
| :- | :- | :- |
| shapes | [`IShapeCollection`](/slides/python-net/nl/aspose.slides/ishapecollection) | De vormverzameling waaraan het diagram zal worden toegevoegd. |
| x | **float** | De X-coördinaat voor het positioneren van het diagram. |
| y | **float** | De Y-coördinaat voor het positioneren van het diagram. |
| workbook | [`IExcelDataWorkbook`](/slides/python-net/nl/aspose.slides.excel/iexceldataworkbook) | De Excel-werkmap. |
| worksheet_name | **str** | De naam van het werkblad dat het diagram bevat. |
| chart_index | **int** | De nulgebaseerde index van de diagramvorm die moet worden ingevoegd. <br/><br/>            Deze index kan verkregen worden met de **Aspose.Slides.Excel.IExcelDataWorkbook.GetChartsFromWorksheet(Syste** methode. |
| embed_all_workbook | **bool** | Als `true`, wordt de volledige werkmap in het diagram ingebed; <br/><br/>            als `false`, worden alleen de diagramgegevens ingebed. |

### Uitzonderingen

| Exception | Beschrijving |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Gegooid wanneer een vereist parameter None, leeg is, of wanneer het diagram niet in de werkmap gevonden kan worden. |


## add_chart_from_workbook(shapes, x, y, workbook, worksheet_name, chart_name, embed_all_workbook) {#ishapecollection-float-float-asposeslidesexceliexceldataworkbook-str-str-bool}
Haalt een diagram op uit de opgegeven Excel-werkmap en voegt het toe aan het einde van de opgegeven vormverzameling op de opgegeven coördinaten.

### Retour

Het diagram dat aan de vormverzameling is toegevoegd.



```python
@staticmethod
def add_chart_from_workbook(shapes, x, y, workbook, worksheet_name, chart_name, embed_all_workbook):
    ...
```


| Parameter | Type | Beschrijving |
| :- | :- | :- |
| shapes | [`IShapeCollection`](/slides/python-net/nl/aspose.slides/ishapecollection) | De vormverzameling waaraan het diagram zal worden toegevoegd. |
| x | **float** | De X-coördinaat voor het positioneren van het diagram. |
| y | **float** | De Y-coördinaat voor het positioneren van het diagram. |
| workbook | [`IExcelDataWorkbook`](/slides/python-net/nl/aspose.slides.excel/iexceldataworkbook) | De Excel-werkmap. |
| worksheet_name | **str** | De naam van het werkblad dat het diagram bevat. |
| chart_name | **str** | De naam van het diagram dat moet worden toegevoegd. |
| embed_all_workbook | **bool** | Als `true`, wordt de volledige werkmap in het diagram ingebed; <br/><br/>            als `false`, worden alleen de diagramgegevens ingebed. |

### Uitzonderingen

| Exception | Beschrijving |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Gegooid wanneer een vereist parameter None, leeg is, of wanneer het diagram niet in de werkmap gevonden kan worden. |


## add_chart_from_workbook(shapes, x, y, workbook_stream, worksheet_name, chart_name, embed_all_workbook) {#ishapecollection-float-float-iorawiobase-str-str-bool}
Haalt een diagram op uit de opgegeven Excel-werkmap en voegt het toe aan het einde van de opgegeven vormverzameling op de opgegeven coördinaten.

### Retour

Het diagram dat aan de vormverzameling is toegevoegd.



```python
@staticmethod
def add_chart_from_workbook(shapes, x, y, workbook_stream, worksheet_name, chart_name, embed_all_workbook):
    ...
```


| Parameter | Type | Beschrijving |
| :- | :- | :- |
| shapes | [`IShapeCollection`](/slides/python-net/nl/aspose.slides/ishapecollection) | De vormverzameling waaraan het diagram zal worden toegevoegd. |
| x | **float** | De X-coördinaat voor het positioneren van het diagram. |
| y | **float** | De Y-coördinaat voor het positioneren van het diagram. |
| workbook_stream | **io.RawIOBase** | Een stream die de werkmap-data bevat. |
| worksheet_name | **str** | De naam van het werkblad dat het diagram bevat. |
| chart_name | **str** | De naam van het diagram dat moet worden toegevoegd. |
| embed_all_workbook | **bool** | Als `true`, wordt de volledige werkmap in het diagram ingebed; <br/><br/>            als `false`, worden alleen de diagramgegevens ingebed. |

### Uitzonderingen

| Exception | Beschrijving |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Gegooid wanneer een vereist parameter None, leeg is, of wanneer het diagram niet in de werkmap gevonden kan worden. |
| **RuntimeError(Proxy error(InvalidOperationException))** | Gegooid wanneer de invoergegevens in een niet-ondersteund formaat zijn. |


## add_chart_from_workbook(shapes, x, y, workbook_path, worksheet_name, chart_name, embed_workbook) {#ishapecollection-float-float-str-str-str-bool}
Haalt een diagram op uit de opgegeven Excel-werkmap en voegt het toe aan het einde van de opgegeven vormverzameling op de opgegeven coördinaten.

### Retour

Het diagram dat aan de vormverzameling is toegevoegd.



```python
@staticmethod
def add_chart_from_workbook(shapes, x, y, workbook_path, worksheet_name, chart_name, embed_workbook):
    ...
```


| Parameter | Type | Beschrijving |
| :- | :- | :- |
| shapes | [`IShapeCollection`](/slides/python-net/nl/aspose.slides/ishapecollection) | De vormverzameling waaraan het diagram zal worden toegevoegd. |
| x | **float** | De X-coördinaat voor het positioneren van het diagram. |
| y | **float** | De Y-coördinaat voor het positioneren van het diagram. |
| workbook_path | **str** | Het bestandspad naar de werkmap die het diagram bevat. |
| worksheet_name | **str** | De naam van het werkblad dat het diagram bevat. |
| chart_name | **str** | De naam van het diagram dat moet worden toegevoegd. |
| embed_workbook | **bool** | Als `true`, wordt de werkmap in het diagram ingebed; <br/><br/>            als `false`, zal het diagram linken naar de externe werkmap. |

### Uitzonderingen

| Exception | Beschrijving |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Gegooid wanneer een vereist parameter None, leeg is, of wanneer het diagram niet in de werkmap gevonden kan worden. |
| **RuntimeError(Proxy error(IOException))** | Gegooid wanneer er een I/O-fout optreedt bij het benaderen van het bestand. |
| **RuntimeError(Proxy error(InvalidOperationException))** | Gegooid wanneer de invoergegevens in een niet-ondersteund formaat zijn. |



### Zie ook
* klasse [`ExcelWorkbookImporter`](/slides/python-net/nl/aspose.slides.importing/excelworkbookimporter)
* klasse [`IExcelDataWorkbook`](/slides/python-net/nl/aspose.slides.excel/iexceldataworkbook)
* klasse [`IShapeCollection`](/slides/python-net/nl/aspose.slides/ishapecollection)
* module [`aspose.slides.importing`](/slides/python-net/nl/aspose.slides.importing)
* library [`Aspose.Slides`](/slides/python-net)