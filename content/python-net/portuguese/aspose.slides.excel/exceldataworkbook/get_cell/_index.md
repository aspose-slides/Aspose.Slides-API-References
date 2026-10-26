---
title: get_cell method
second_title: Referência da API Aspose.Slides for Python via .NET
description: 
type: docs
url: /pt/aspose.slides.excel/exceldataworkbook/get_cell/
weight: 20
---
## get_cell(self, worksheet_index, cell_name) {#int-str}
Recupera uma célula da planilha especificada usando seu índice e o nome da célula no estilo Excel (por exemplo, "B2").

### Retorna

A célula na localização especificada.



```python
def get_cell(self, worksheet_index, cell_name):
    ...
```


| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| worksheet_index | **int** | Índice baseado em zero da planilha. |
| cell_name | **str** | A referência de célula no estilo Excel (por exemplo, "A1", "C5"). |


## get_cell(self, worksheet_name, cell_name) {#str-str}
Recupera uma célula da planilha especificada usando o nome da célula no estilo Excel (por exemplo, "B2").

### Retorna

A célula na localização especificada.



```python
def get_cell(self, worksheet_name, cell_name):
    ...
```


| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| worksheet_name | **str** | O nome da planilha. |
| cell_name | **str** | A referência de célula no estilo Excel (por exemplo, "A1", "C5"). |


## get_cell(self, worksheet_index, row, column) {#int-int-int}
Recupera uma célula da planilha especificada usando seu índice e as coordenadas da célula.

### Retorna

A célula na localização especificada.



```python
def get_cell(self, worksheet_index, row, column):
    ...
```


| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| worksheet_index | **int** | Índice baseado em zero da planilha. |
| row | **int** | Índice da linha da célula, baseado em zero. |
| column | **int** | Índice da coluna da célula, baseado em zero. |


## get_cell(self, worksheet_name, row, column) {#str-int-int}
Recupera uma célula da planilha especificada usando seu nome e as coordenadas da célula.

### Retorna

A célula na localização especificada.



```python
def get_cell(self, worksheet_name, row, column):
    ...
```


| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| worksheet_name | **str** | O nome da planilha. |
| row | **int** | Índice da linha da célula, baseado em zero. |
| column | **int** | Índice da coluna da célula, baseado em zero. |



### Veja Também
* classe [`ExcelDataWorkbook`](/slides/python-net/pt/aspose.slides.excel/exceldataworkbook)
* classe [`IExcelDataCell`](/slides/python-net/pt/aspose.slides.excel/iexceldatacell)
* módulo [`aspose.slides.excel`](/slides/python-net/pt/aspose.slides.excel)
* biblioteca [`Aspose.Slides`](/slides/python-net)