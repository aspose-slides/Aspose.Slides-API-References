---
title: get_cell method
second_title: Riferimento API Aspose.Slides per Python via .NET
description: 
type: docs
url: /it/aspose.slides.excel/exceldataworkbook/get_cell/
weight: 20
---
## get_cell(self, worksheet_index, cell_name) {#int-str}
Recupera una cella dal foglio di lavoro specificato usando il suo indice e il nome della cella in stile Excel (ad es., "B2").

### Restituisce

La cella nella posizione specificata.



```python
def get_cell(self, worksheet_index, cell_name):
    ...
```


| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| worksheet_index | **int** | Zero-based index of the worksheet. |
| cell_name | **str** | The Excel-style cell reference (e.g., "A1", "C5"). |


## get_cell(self, worksheet_name, cell_name) {#str-str}
Recupera una cella dal foglio di lavoro specificato usando il nome della cella in stile Excel (ad es., "B2").

### Restituisce

La cella nella posizione specificata.



```python
def get_cell(self, worksheet_name, cell_name):
    ...
```


| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| worksheet_name | **str** | The name of the worksheet. |
| cell_name | **str** | The Excel-style cell reference (e.g., "A1", "C5"). |


## get_cell(self, worksheet_index, row, column) {#int-int-int}
Recupera una cella dal foglio di lavoro specificato usando il suo indice e le coordinate della cella.

### Restituisce

La cella nella posizione specificata.



```python
def get_cell(self, worksheet_index, row, column):
    ...
```


| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| worksheet_index | **int** | Zero-based index of the worksheet. |
| row | **int** | Zero-based row index of the cell. |
| column | **int** | Zero-based column index of the cell. |


## get_cell(self, worksheet_name, row, column) {#str-int-int}
Recupera una cella dal foglio di lavoro specificato usando il suo nome e le coordinate della cella.

### Restituisce

La cella nella posizione specificata.



```python
def get_cell(self, worksheet_name, row, column):
    ...
```


| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| worksheet_name | **str** | The name of the worksheet. |
| row | **int** | Zero-based row index of the cell. |
| column | **int** | Zero-based column index of the cell. |



### Vedi anche
* classe [`ExcelDataWorkbook`](/slides/python-net/it/aspose.slides.excel/exceldataworkbook)
* classe [`IExcelDataCell`](/slides/python-net/it/aspose.slides.excel/iexceldatacell)
* modulo [`aspose.slides.excel`](/slides/python-net/it/aspose.slides.excel)
* libreria [`Aspose.Slides`](/slides/python-net)