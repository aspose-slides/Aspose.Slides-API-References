---
title: add method
second_title: Referência da API Aspose.Slides para Python via .NET
description: 
type: docs
url: /pt/aspose.slides.charts/ichartseriescollection/add/
weight: 10
---
## add(self, type) {#charttype}
Cria uma nova série de gráfico e a adiciona à coleção.

### Retorna

Nova série de gráfico.



```python
def add(self, type):
    ...
```


| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| type | [`ChartType`](/slides/python-net/pt/aspose.slides.charts/charttype) | Tipo da série |


## add(self, cell_with_series_name, type) {#ichartdatacell-charttype}
Cria uma nova série de gráfico a partir de [`IChartDataCell`](/slides/python-net/pt/aspose.slides.charts/ichartdatacell) e a adiciona à coleção.

### Retorna

Série de gráfico adicionada ou série que já está na coleção.



```python
def add(self, cell_with_series_name, type):
    ...
```


| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| cell_with_series_name | [`IChartDataCell`](/slides/python-net/pt/aspose.slides.charts/ichartdatacell) | Célula que contém o nome da série. |
| type | [`ChartType`](/slides/python-net/pt/aspose.slides.charts/charttype) | Tipo definido da série |

### Observações

Se a série de gráfico criada a partir da mesma célula já estiver na coleção, o método não adiciona nada e retorna seu índice.


## add(self, cells_with_series_name, type) {#ichartcellcollection-charttype}
Cria uma nova série de gráfico a partir de [`IChartCellCollection`](/slides/python-net/pt/aspose.slides.charts/ichartcellcollection) e a adiciona à coleção.

### Retorna

Série de gráfico adicionada ou série que já está na coleção.



```python
def add(self, cells_with_series_name, type):
    ...
```


| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| cells_with_series_name | [`IChartCellCollection`](/slides/python-net/pt/aspose.slides.charts/ichartcellcollection) | Células que contêm o nome da série. |
| type | [`ChartType`](/slides/python-net/pt/aspose.slides.charts/charttype) | Tipo definido da série |

### Observações

Se a série de gráfico criada a partir da mesma célula já estiver na coleção, o método não adiciona nada e retorna seu índice.


## add(self, name, type) {#str-charttype}
Cria uma nova série de gráfico a partir do valor e a adiciona à coleção.

### Retorna

Série de gráfico adicionada.



```python
def add(self, name, type):
    ...
```


| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| name | **str** | Nome da série. |
| type | [`ChartType`](/slides/python-net/pt/aspose.slides.charts/charttype) | Tipo definido da série |



### Veja também
* enumeração [`ChartType`](/slides/python-net/pt/aspose.slides.charts/charttype)
* classe [`IChartCellCollection`](/slides/python-net/pt/aspose.slides.charts/ichartcellcollection)
* classe [`IChartDataCell`](/slides/python-net/pt/aspose.slides.charts/ichartdatacell)
* classe [`IChartSeries`](/slides/python-net/pt/aspose.slides.charts/ichartseries)
* classe [`IChartSeriesCollection`](/slides/python-net/pt/aspose.slides.charts/ichartseriescollection)
* módulo [`aspose.slides.charts`](/slides/python-net/pt/aspose.slides.charts)
* biblioteca [`Aspose.Slides`](/slides/python-net)