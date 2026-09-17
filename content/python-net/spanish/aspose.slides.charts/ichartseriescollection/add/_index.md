---
title: add method
second_title: Referencia de API de Aspose.Slides para Python vía .NET
description: 
type: docs
url: /es/aspose.slides.charts/ichartseriescollection/add/
weight: 10
---
## add(self, type) {#charttype}
Crea una nueva serie de gráfico y la agrega a la colección.

### Returns
Nueva serie de gráfico.



```python
def add(self, type):
    ...
```


| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| type | [`ChartType`](/slides/python-net/es/aspose.slides.charts/charttype) | Tipo de serie |


## add(self, cell_with_series_name, type) {#ichartdatacell-charttype}
Crea una nueva serie de gráfico a partir de [`IChartDataCell`](/slides/python-net/es/aspose.slides.charts/ichartdatacell) y la agrega a la colección.

### Returns
Serie de gráfico agregada o serie que ya está en la colección.



```python
def add(self, cell_with_series_name, type):
    ...
```


| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| cell_with_series_name | [`IChartDataCell`](/slides/python-net/es/aspose.slides.charts/ichartdatacell) | Celda que contiene el nombre de la serie. |
| type | [`ChartType`](/slides/python-net/es/aspose.slides.charts/charttype) | Tipo establecido para la serie |

### Remarks
Si la serie de gráfico creada a partir de la misma celda ya está en la colección, entonces el método no agrega nada y devuelve su índice.


## add(self, cells_with_series_name, type) {#ichartcellcollection-charttype}
Crea una nueva serie de gráfico a partir de [`IChartCellCollection`](/slides/python-net/es/aspose.slides.charts/ichartcellcollection) y la agrega a la colección.

### Returns
Serie de gráfico agregada o serie que ya está en la colección.



```python
def add(self, cells_with_series_name, type):
    ...
```


| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| cells_with_series_name | [`IChartCellCollection`](/slides/python-net/es/aspose.slides.charts/ichartcellcollection) | Celdas que contienen el nombre de la serie. |
| type | [`ChartType`](/slides/python-net/es/aspose.slides.charts/charttype) | Tipo establecido para la serie |

### Remarks
Si la serie de gráfico creada a partir de la misma celda ya está en la colección, entonces el método no agrega nada y devuelve su índice.


## add(self, name, type) {#str-charttype}
Crea una nueva serie de gráfico a partir del valor y la agrega a la colección.

### Returns
Serie de gráfico agregada.



```python
def add(self, name, type):
    ...
```


| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| name | **str** | Nombre de la serie. |
| type | [`ChartType`](/slides/python-net/es/aspose.slides.charts/charttype) | Tipo establecido para la serie |



### See Also
* enumeración [`ChartType`](/slides/python-net/es/aspose.slides.charts/charttype)
* clase [`IChartCellCollection`](/slides/python-net/es/aspose.slides.charts/ichartcellcollection)
* clase [`IChartDataCell`](/slides/python-net/es/aspose.slides.charts/ichartdatacell)
* clase [`IChartSeries`](/slides/python-net/es/aspose.slides.charts/ichartseries)
* clase [`IChartSeriesCollection`](/slides/python-net/es/aspose.slides.charts/ichartseriescollection)
* módulo [`aspose.slides.charts`](/slides/python-net/es/aspose.slides.charts)
* biblioteca [`Aspose.Slides`](/slides/python-net)