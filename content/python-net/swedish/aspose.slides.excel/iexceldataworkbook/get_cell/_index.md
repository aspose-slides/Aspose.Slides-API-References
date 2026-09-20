---
title: get_cell method
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides.excel/iexceldataworkbook/get_cell/
weight: 10
---
## get_cell(self, worksheet_index, cell_name) {#int-str}
Hämtar en cell från det angivna kalkylbladet med dess index och Excel-liknande cellnamn (t.ex. "B2").

### Returnvärde

Cellen på den angivna platsen.



```python
def get_cell(self, worksheet_index, cell_name):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| worksheet_index | **int** | Nollbaserat index för kalkylbladet. |
| cell_name | **str** | Excel-liknande cellreferens (t.ex. "A1", "C5"). |


## get_cell(self, worksheet_name, cell_name) {#str-str}
Hämtar en cell från det angivna kalkylbladet med Excel-liknande cellnamn (t.ex. "B2").

### Returnvärde

Cellen på den angivna platsen.



```python
def get_cell(self, worksheet_name, cell_name):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| worksheet_name | **str** | Namnet på kalkylbladet. |
| cell_name | **str** | Excel-liknande cellreferens (t.ex. "A1", "C5"). |


## get_cell(self, worksheet_index, row, column) {#int-int-int}
Hämtar en cell från det angivna kalkylbladet med dess index och cellkoordinater.

### Returnvärde

Cellen på den angivna platsen.



```python
def get_cell(self, worksheet_index, row, column):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| worksheet_index | **int** | Nollbaserat index för kalkylbladet. |
| row | **int** | Nollbaserat radindex för cellen. |
| column | **int** | Nollbaserat kolumnindex för cellen. |


## get_cell(self, worksheet_name, row, column) {#str-int-int}
Hämtar en cell från det angivna kalkylbladet med dess namn och cellkoordinater.

### Returnvärde

Cellen på den angivna platsen.



```python
def get_cell(self, worksheet_name, row, column):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| worksheet_name | **str** | Namnet på kalkylbladet. |
| row | **int** | Nollbaserat radindex för cellen. |
| column | **int** | Nollbaserat kolumnindex för cellen. |



### Se även
* klass [`IExcelDataCell`](/slides/python-net/sv/aspose.slides.excel/iexceldatacell)
* klass [`IExcelDataWorkbook`](/slides/python-net/sv/aspose.slides.excel/iexceldataworkbook)
* modul [`aspose.slides.excel`](/slides/python-net/sv/aspose.slides.excel)
* bibliotek [`Aspose.Slides`](/slides/python-net)