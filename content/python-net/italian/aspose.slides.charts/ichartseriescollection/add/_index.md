---
title: add method
second_title: Riferimento API Aspose.Slides per Python via .NET
description: 
type: docs
url: /it/aspose.slides.charts/ichartseriescollection/add/
weight: 10
---
## add(self, type) {#charttype}
Crea una nuova serie di grafico e la aggiunge alla collezione.

### Returns
Nuova serie di grafico.



```python
def add(self, type):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| type | [`ChartType`](/slides/python-net/it/aspose.slides.charts/charttype) | Tipo di serie |


## add(self, cell_with_series_name, type) {#ichartdatacell-charttype}
Crea una nuova serie di grafico da [`IChartDataCell`](/slides/python-net/it/aspose.slides.charts/ichartdatacell) e la aggiunge alla collezione.

### Returns
Serie di grafico aggiunta o serie già presente nella collezione.



```python
def add(self, cell_with_series_name, type):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| cell_with_series_name | [`IChartDataCell`](/slides/python-net/it/aspose.slides.charts/ichartdatacell) | Cella che contiene il nome della serie. |
| type | [`ChartType`](/slides/python-net/it/aspose.slides.charts/charttype) | Tipo impostato della serie |

### Remarks
Se la serie di grafico creata dalla stessa cella è già nella collezione, il metodo non aggiunge nulla e restituisce il suo indice.


## add(self, cells_with_series_name, type) {#ichartcellcollection-charttype}
Crea una nuova serie di grafico da [`IChartCellCollection`](/slides/python-net/it/aspose.slides.charts/ichartcellcollection) e la aggiunge alla collezione.

### Returns
Serie di grafico aggiunta o serie già presente nella collezione.



```python
def add(self, cells_with_series_name, type):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| cells_with_series_name | [`IChartCellCollection`](/slides/python-net/it/aspose.slides.charts/ichartcellcollection) | Celle che contengono il nome della serie. |
| type | [`ChartType`](/slides/python-net/it/aspose.slides.charts/charttype) | Tipo impostato della serie |

### Remarks
Se la serie di grafico creata dalla stessa cella è già nella collezione, il metodo non aggiunge nulla e restituisce il suo indice.


## add(self, name, type) {#str-charttype}
Crea una nuova serie di grafico dal valore e la aggiunge alla collezione.

### Returns
Serie di grafico aggiunta.



```python
def add(self, name, type):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| name | **str** | Nome della serie. |
| type | [`ChartType`](/slides/python-net/it/aspose.slides.charts/charttype) | Tipo impostato della serie |



### Vedi anche
* enumerazione [`ChartType`](/slides/python-net/it/aspose.slides.charts/charttype)
* classe [`IChartCellCollection`](/slides/python-net/it/aspose.slides.charts/ichartcellcollection)
* classe [`IChartDataCell`](/slides/python-net/it/aspose.slides.charts/ichartdatacell)
* classe [`IChartSeries`](/slides/python-net/it/aspose.slides.charts/ichartseries)
* classe [`IChartSeriesCollection`](/slides/python-net/it/aspose.slides.charts/ichartseriescollection)
* modulo [`aspose.slides.charts`](/slides/python-net/it/aspose.slides.charts)
* libreria [`Aspose.Slides`](/slides/python-net)