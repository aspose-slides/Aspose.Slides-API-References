---
title: get_cell method
second_title: Riferimento API Aspose.Slides per Python via .NET
description: 
type: docs
url: /it/aspose.slides.excel/iexceldataworkbook/get_cell/
weight: 10
---
## get_cell(self, worksheet_index, cell_name) {#int-str}
Recupera una cella dal foglio di lavoro specificato usando il suo indice e il nome della cella in stile Excel (ad esempio, "B2").

### Restituisce

La cella nella posizione specificata.



```python
def get_cell(self, worksheet_index, cell_name):
    ...
```


| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| worksheet_index | **int** | Indice a base zero del foglio di lavoro. |
| cell_name | **str** | Il riferimento di cella in stile Excel (ad esempio, "A1", "C5"). |


## get_cell(self, worksheet_name, cell_name) {#str-str}
Recupera una cella dal foglio di lavoro specificato usando il nome della cella in stile Excel (ad esempio, "B2").

### Restituisce

La cella nella posizione specificata.



```python
def get_cell(self, worksheet_name, cell_name):
    ...
```


| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| worksheet_name | **str** | Il nome del foglio di lavoro. |
| cell_name | **str** | Il riferimento di cella in stile Excel (ad esempio, "A1", "C5"). |


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
| worksheet_index | **int** | Indice a base zero del foglio di lavoro. |
| row | **int** | Indice di riga a base zero della cella. |
| column | **int** | Indice di colonna a base zero della cella. |


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
| worksheet_name | **str** | Il nome del foglio di lavoro. |
| row | **int** | Indice di riga a base zero della cella. |
| column | **int** | Indice di colonna a base zero della cella. |



### Vedi anche
* classe [`IExcelDataCell`](/slides/python-net/it/aspose.slides.excel/iexceldatacell)
* classe [`IExcelDataWorkbook`](/slides/python-net/it/aspose.slides.excel/iexceldataworkbook)
* modulo [`aspose.slides.excel`](/slides/python-net/it/aspose.slides.excel)
* libreria [`Aspose.Slides`](/slides/python-net)