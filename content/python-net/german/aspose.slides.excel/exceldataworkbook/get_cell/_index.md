---
title: get_cell method
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides.excel/exceldataworkbook/get_cell/
weight: 20
---
## get_cell(self, worksheet_index, cell_name) {#int-str}
Ruft eine Zelle aus dem angegebenen Arbeitsblatt über dessen Index und den Excel-ähnlichen Zellnamen (z.B. "B2") ab.

### Rückgabewert

Die Zelle an der angegebenen Position.



```python
def get_cell(self, worksheet_index, cell_name):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| worksheet_index | **int** | Nullbasierter Index des Arbeitsblatts. |
| cell_name | **str** | Der Excel-ähnliche Zellbezug (z.B. "A1", "C5"). |


## get_cell(self, worksheet_name, cell_name) {#str-str}
Ruft eine Zelle aus dem angegebenen Arbeitsblatt über den Excel-ähnlichen Zellnamen (z.B. "B2") ab.

### Rückgabewert

Die Zelle an der angegebenen Position.



```python
def get_cell(self, worksheet_name, cell_name):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| worksheet_name | **str** | Der Name des Arbeitsblatts. |
| cell_name | **str** | Der Excel-ähnliche Zellbezug (z.B. "A1", "C5"). |


## get_cell(self, worksheet_index, row, column) {#int-int-int}
Ruft eine Zelle aus dem angegebenen Arbeitsblatt über dessen Index und Zellkoordinaten ab.

### Rückgabewert

Die Zelle an der angegebenen Position.



```python
def get_cell(self, worksheet_index, row, column):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| worksheet_index | **int** | Nullbasierter Index des Arbeitsblatts. |
| row | **int** | Nullbasierter Zeilenindex der Zelle. |
| column | **int** | Nullbasierter Spaltenindex der Zelle. |


## get_cell(self, worksheet_name, row, column) {#str-int-int}
Ruft eine Zelle aus dem angegebenen Arbeitsblatt über dessen Namen und Zellkoordinaten ab.

### Rückgabewert

Die Zelle an der angegebenen Position.



```python
def get_cell(self, worksheet_name, row, column):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| worksheet_name | **str** | Der Name des Arbeitsblatts. |
| row | **int** | Nullbasierter Zeilenindex der Zelle. |
| column | **int** | Nullbasierter Spaltenindex der Zelle. |



### Siehe auch
* Klasse [`ExcelDataWorkbook`](/slides/python-net/de/aspose.slides.excel/exceldataworkbook)
* Klasse [`IExcelDataCell`](/slides/python-net/de/aspose.slides.excel/iexceldatacell)
* Modul [`aspose.slides.excel`](/slides/python-net/de/aspose.slides.excel)
* Bibliothek [`Aspose.Slides`](/slides/python-net)