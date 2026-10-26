---
title: add method
second_title: Referencia de API de Aspose.Slides para Python a través de .NET
description: 
type: docs
url: /es/aspose.slides.charts/chartcellcollection/add/
weight: 10
---
## add(self, cell) {#ichartdatacell}
Agregar una nueva celda a la colección.


```python
def add(self, cell):
    ...
```


| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| cell | [`IChartDataCell`](/slides/python-net/es/aspose.slides.charts/ichartdatacell) | Nueva celda a agregar. |


## add(self, value) {#any}
Crea [`ChartDataCell`](/slides/python-net/es/aspose.slides.charts/chartdatacell) a partir del valor especificado y lo agrega a la colección.


```python
def add(self, value):
    ...
```


| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| value | **any** | El valor. |

### Observaciones

Este método agrega una hoja de cálculo con el nombre AUTO_DATA y agrega allí todos los valores.  Si utiliza [`ChartDataWorkbook`](/slides/python-net/es/aspose.slides.charts/chartdataworkbook) para agregar o editar valores de Cell, asegúrese de no usar esta hoja de cálculo
            El número máximo de valores agregados con este método no debe exceder 16711680

### Excepciones

| Excepción | Descripción |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | si se supera el límite |



### Ver también
* clase [`ChartCellCollection`](/slides/python-net/es/aspose.slides.charts/chartcellcollection)
* clase [`ChartDataCell`](/slides/python-net/es/aspose.slides.charts/chartdatacell)
* clase [`ChartDataWorkbook`](/slides/python-net/es/aspose.slides.charts/chartdataworkbook)
* clase [`IChartDataCell`](/slides/python-net/es/aspose.slides.charts/ichartdatacell)
* módulo [`aspose.slides.charts`](/slides/python-net/es/aspose.slides.charts)
* biblioteca [`Aspose.Slides`](/slides/python-net)