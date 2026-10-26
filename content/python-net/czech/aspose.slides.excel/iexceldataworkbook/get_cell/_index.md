---
title: get_cell method
second_title: Aspose.Slides pro Python prostřednictvím .NET API Reference
description: 
type: docs
url: /cs/aspose.slides.excel/iexceldataworkbook/get_cell/
weight: 10
---
## get_cell(self, worksheet_index, cell_name) {#int-str}
Načte buňku z určeného pracovního listu pomocí jeho indexu a názvu buňky ve stylu Excel (e.g., "B2").

### Návratová hodnota

Buňka na zadaném umístění.



```python
def get_cell(self, worksheet_index, cell_name):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| worksheet_index | **int** | Index pracovního listu počítaný od nuly. |
| cell_name | **str** | Reference buňky ve stylu Excel (e.g., "A1", "C5"). |


## get_cell(self, worksheet_name, cell_name) {#str-str}
Načte buňku z určeného pracovního listu pomocí názvu buňky ve stylu Excel (e.g., "B2").

### Návratová hodnota

Buňka na zadaném umístění



```python
def get_cell(self, worksheet_name, cell_name):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| worksheet_name | **str** | Název pracovního listu. |
| cell_name | **str** | Reference buňky ve stylu Excel (e.g., "A1", "C5"). |


## get_cell(self, worksheet_index, row, column) {#int-int-int}
Načte buňku z určeného pracovního listu pomocí jeho indexu a souřadnic buňky.

### Návratová hodnota

Buňka na zadaném umístění



```python
def get_cell(self, worksheet_index, row, column):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| worksheet_index | **int** | Index pracovního listu počítaný od nuly. |
| row | **int** | Index řádku buňky počítaný od nuly. |
| column | **int** | Index sloupce buňky počítaný od nuly. |


## get_cell(self, worksheet_name, row, column) {#str-int-int}
Načte buňku z určeného pracovního listu pomocí jeho názvu a souřadnic buňky.

### Návratová hodnota

Buňka na zadaném umístění



```python
def get_cell(self, worksheet_name, row, column):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| worksheet_name | **str** | Název pracovního listu. |
| row | **int** | Index řádku buňky počítaný od nuly. |
| column | **int** | Index sloupce buňky počítaný od nuly. |



### Viz také
* třída [`IExcelDataCell`](/slides/python-net/cs/aspose.slides.excel/iexceldatacell)
* třída [`IExcelDataWorkbook`](/slides/python-net/cs/aspose.slides.excel/iexceldataworkbook)
* modul [`aspose.slides.excel`](/slides/python-net/cs/aspose.slides.excel)
* knihovna [`Aspose.Slides`](/slides/python-net)