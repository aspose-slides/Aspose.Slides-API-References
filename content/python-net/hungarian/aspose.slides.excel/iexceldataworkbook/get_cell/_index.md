---
title: get_cell method
second_title: Aspose.Slides for Python via .NET API Referencia
description: 
type: docs
url: /hu/aspose.slides.excel/iexceldataworkbook/get_cell/
weight: 10
---
## get_cell(self, worksheet_index, cell_name) {#int-str}
Lekéri a cellát a megadott munkalapról az indexe és az Excel-stílusú cellanév (például "B2") segítségével.

### Returns
A cella a megadott helyen.



```python
def get_cell(self, worksheet_index, cell_name):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| worksheet_index | **int** | Nulláralapú index a munkalaphoz. |
| cell_name | **str** | Az Excel-stílusú cellahivatkozás (például "A1", "C5"). |


## get_cell(self, worksheet_name, cell_name) {#str-str}
Lekéri a cellát a megadott munkalapról az Excel-stílusú cellanév (például "B2") segítségével.

### Returns
A cella a megadott helyen.



```python
def get_cell(self, worksheet_name, cell_name):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| worksheet_name | **str** | A munkalap neve. |
| cell_name | **str** | Az Excel-stílusú cellahivatkozás (például "A1", "C5"). |


## get_cell(self, worksheet_index, row, column) {#int-int-int}
Lekéri a cellát a megadott munkalapról az indexe és a cellakoordináták segítségével.

### Returns
A cella a megadott helyen.



```python
def get_cell(self, worksheet_index, row, column):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| worksheet_index | **int** | Nulláralapú index a munkalaphoz. |
| row | **int** | Nulláralapú sorindex a cellához. |
| column | **int** | Nulláralapú oszlopindex a cellához. |


## get_cell(self, worksheet_name, row, column) {#str-int-int}
Lekéri a cellát a megadott munkalapról a neve és a cellakoordináták alapján.

### Returns
A cella a megadott helyen.



```python
def get_cell(self, worksheet_name, row, column):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| worksheet_name | **str** | A munkalap neve. |
| row | **int** | Nulláralapú sorindex a cellához. |
| column | **int** | Nulláralapú oszlopindex a cellához. |



### See Also
* osztály [`IExcelDataCell`](/slides/python-net/hu/aspose.slides.excel/iexceldatacell)
* osztály [`IExcelDataWorkbook`](/slides/python-net/hu/aspose.slides.excel/iexceldataworkbook)
* modul [`aspose.slides.excel`](/slides/python-net/hu/aspose.slides.excel)
* könyvtár [`Aspose.Slides`](/slides/python-net)