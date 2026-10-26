---
title: add method
second_title: Riferimento API Aspose.Slides per Python via .NET
description: 
type: docs
url: /it/aspose.slides.charts/chartseriescollection/add/
weight: 10
---
## add(self, type) {#charttype}
Crea una nuova serie di grafico e la aggiunge alla collezione.

### Restituisce

Nuova serie di grafico.



```python
def add(self, type):
    ...
```


| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| type | [`ChartType`](/slides/python-net/it/aspose.slides.charts/charttype) | Tipo della serie |


## add(self, cell_with_series_name, type) {#ichartdatacell-charttype}
Crea una nuova serie di grafico da [`ChartDataCell`](/slides/python-net/it/aspose.slides.charts/chartdatacell) e la aggiunge alla collezione.

### Restituisce

Serie di grafico aggiunta o serie già presente nella collezione.



```python
def add(self, cell_with_series_name, type):
    ...
```


| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| cell_with_series_name | [`IChartDataCell`](/slides/python-net/it/aspose.slides.charts/ichartdatacell) | Cella che contiene il nome della serie. |
| type | [`ChartType`](/slides/python-net/it/aspose.slides.charts/charttype) | Tipo impostato per la serie |

### Osservazioni

Se la serie di grafico creata dalla stessa cella è già nella collezione allora il metodo non aggiunge nulla e restituisce il suo indice.


## add(self, cells_with_series_name, type) {#ichartcellcollection-charttype}
Crea una nuova serie di grafico da [`ChartCellCollection`](/slides/python-net/it/aspose.slides.charts/chartcellcollection) e la aggiunge alla collezione.

### Restituisce

Serie di grafico aggiunta o serie già presente nella collezione.



```python
def add(self, cells_with_series_name, type):
    ...
```


| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| cells_with_series_name | [`IChartCellCollection`](/slides/python-net/it/aspose.slides.charts/ichartcellcollection) | Celle che contengono il nome della serie. |
| type | [`ChartType`](/slides/python-net/it/aspose.slides.charts/charttype) | Tipo impostato per la serie |

### Osservazioni

Se la serie di grafico creata dalla stessa cella è già nella collezione allora il metodo non aggiunge nulla e restituisce il suo indice.


## add(self, name, type) {#str-charttype}
Crea una nuova serie di grafico da valore e la aggiunge alla collezione.

### Restituisce

Serie di grafico aggiunta.



```python
def add(self, name, type):
    ...
```


| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| name | **str** | Nome della serie. |
| type | [`ChartType`](/slides/python-net/it/aspose.slides.charts/charttype) | Tipo impostato per la serie |



### Vedi anche
* classe [`ChartCellCollection`](/slides/python-net/it/aspose.slides.charts/chartcellcollection)
* classe [`ChartDataCell`](/slides/python-net/it/aspose.slides.charts/chartdatacell)
* classe [`ChartSeriesCollection`](/slides/python-net/it/aspose.slides.charts/chartseriescollection)
* enumerazione [`ChartType`](/slides/python-net/it/aspose.slides.charts/charttype)
* classe [`IChartCellCollection`](/slides/python-net/it/aspose.slides.charts/ichartcellcollection)
* classe [`IChartDataCell`](/slides/python-net/it/aspose.slides.charts/ichartdatacell)
* classe [`IChartSeries`](/slides/python-net/it/aspose.slides.charts/ichartseries)
* modulo [`aspose.slides.charts`](/slides/python-net/it/aspose.slides.charts)
* libreria [`Aspose.Slides`](/slides/python-net)