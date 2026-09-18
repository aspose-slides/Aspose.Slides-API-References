---
title: get_cell method
second_title: Aspose.Slides a Pythonhoz .NET-en keresztül API referencia
description: 
type: docs
url: /hu/aspose.slides.excel/exceldataworkbook/get_cell/
weight: 20
---
## get_cell(self, worksheet_index, cell_name) {#int-str}
Lekéri a cellát a megadott munkalapból az index és az Excel-stílusú cellanév (pl. "B2") alapján.

### Visszatérési érték

A megadott helyen lévő cella.



```python
def get_cell(self, worksheet_index, cell_name):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| worksheet_index | **int** | Nulla alapú index a munkalaphoz. |
| cell_name | **str** | Az Excel-stílusú cellahivatkozás (pl. "A1", "C5"). |


## get_cell(self, worksheet_name, cell_name) {#str-str}
Lekéri a cellát a megadott munkalapból az Excel-stílusú cellanév (pl. "B2") alapján.

### Visszatérési érték

A megadott helyen lévő cella.



```python
def get_cell(self, worksheet_name, cell_name):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| worksheet_name | **str** | A munkalap neve. |
| cell_name | **str** | Az Excel-stílusú cellahivatkozás (pl. "A1", "C5"). |


## get_cell(self, worksheet_index, row, column) {#int-int-int}
Lekéri a cellát a megadott munkalapból az index és a cellakoordináták alapján.

### Visszatérési érték

A megadott helyen lévő cella.



```python
def get_cell(self, worksheet_index, row, column):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| worksheet_index | **int** | Nulla alapú index a munkalaphoz. |
| row | **int** | Nulla alapú sorindex a cellához. |
| column | **int** | Nulla alapú oszlopindex a cellához. |


## get_cell(self, worksheet_name, row, column) {#str-int-int}
Lekéri a cellát a megadott munkalapból a neve és a cellakoordináták alapján.

### Visszatérési érték

A megadott helyen lévő cella.



```python
def get_cell(self, worksheet_name, row, column):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| worksheet_name | **str** | A munkalap neve. |
| row | **int** | Nulla alapú sorindex a cellához. |
| column | **int** | Nulla alapú oszlopindex a cellához. |



### Lásd még
* osztály [`ExcelDataWorkbook`](/slides/python-net/hu/aspose.slides.excel/exceldataworkbook)
* osztály [`IExcelDataCell`](/slides/python-net/hu/aspose.slides.excel/iexceldatacell)
* modul [`aspose.slides.excel`](/slides/python-net/hu/aspose.slides.excel)
* library [`Aspose.Slides`](/slides/python-net)