---
title: get_cell method
second_title: Aspose.Slides para Python vía .NET Referencia de API
description: 
type: docs
url: /es/aspose.slides.excel/exceldataworkbook/get_cell/
weight: 20
---
## get_cell(self, worksheet_index, cell_name) {#int-str}
Recupera una celda de la hoja de cálculo especificada usando su índice y el nombre de celda al estilo Excel (e.g., "B2").

### Devuelve

La celda en la ubicación especificada.



```python
def get_cell(self, worksheet_index, cell_name):
    ...
```


| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| worksheet_index | **int** | Índice basado en cero de la hoja de cálculo. |
| cell_name | **str** | La referencia de celda al estilo Excel (e.g., "A1", "C5"). |


## get_cell(self, worksheet_name, cell_name) {#str-str}
Recupera una celda de la hoja de cálculo especificada usando el nombre de celda al estilo Excel (e.g., "B2").

### Devuelve

La celda en la ubicación especificada.



```python
def get_cell(self, worksheet_name, cell_name):
    ...
```


| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| worksheet_name | **str** | El nombre de la hoja de cálculo. |
| cell_name | **str** | La referencia de celda al estilo Excel (e.g., "A1", "C5"). |


## get_cell(self, worksheet_index, row, column) {#int-int-int}
Recupera una celda de la hoja de cálculo especificada usando su índice y las coordenadas de la celda.

### Devuelve

La celda en la ubicación especificada.



```python
def get_cell(self, worksheet_index, row, column):
    ...
```


| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| worksheet_index | **int** | Índice basado en cero de la hoja de cálculo. |
| row | **int** | Índice de fila basado en cero de la celda. |
| column | **int** | Índice de columna basado en cero de la celda. |


## get_cell(self, worksheet_name, row, column) {#str-int-int}
Recupera una celda de la hoja de cálculo especificada usando su nombre y las coordenadas de la celda.

### Devuelve

La celda en la ubicación especificada.



```python
def get_cell(self, worksheet_name, row, column):
    ...
```


| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| worksheet_name | **str** | El nombre de la hoja de cálculo. |
| row | **int** | Índice de fila basado en cero de la celda. |
| column | **int** | Índice de columna basado en cero de la celda. |



### Ver también
* clase [`ExcelDataWorkbook`](/slides/python-net/es/aspose.slides.excel/exceldataworkbook)
* clase [`IExcelDataCell`](/slides/python-net/es/aspose.slides.excel/iexceldatacell)
* módulo [`aspose.slides.excel`](/slides/python-net/es/aspose.slides.excel)
* biblioteca [`Aspose.Slides`](/slides/python-net)