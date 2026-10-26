---
title: add method
second_title: Referencia de API de Aspose.Slides para Python vía .NET
description: 
type: docs
url: /es/aspose.slides.charts/ichartcategorycollection/add/
weight: 10
---
## add(self, chart_data_cell) {#ichartdatacell}
Si la categoría existe en la colección, la devuelve. De lo contrario, crea una nueva categoría de gráfico a partir de [`IChartDataCell`](/slides/python-net/es/aspose.slides.charts/ichartdatacell) y la agrega a la colección.

### Devuelve

Categoría añadida o existente.

```python
def add(self, chart_data_cell):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| chart_data_cell | [`IChartDataCell`](/slides/python-net/es/aspose.slides.charts/ichartdatacell) | Celda utilizada para crear la categoría del gráfico. |

## add(self, value) {#any}
Crea un nuevo [`IChartCategory`](/slides/python-net/es/aspose.slides.charts/ichartcategory) a partir del valor y lo agrega a la colección.

### Devuelve

Añadido [`IChartCategory`](/slides/python-net/es/aspose.slides.charts/ichartcategory).

```python
def add(self, value):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| value | **any** | El valor. |

### Observaciones

Este método agrega una hoja de cálculo con el nombre AUTO_DATA y agrega allí todos los valores.  Si utilizas [`IChartDataWorkbook`](/slides/python-net/es/aspose.slides.charts/ichartdataworkbook) para agregar o editar valores de celdas, asegúrate de no usar esta hoja de cálculo
            El número máximo de valores agregados mediante este método no debe superar 16711680

### Excepciones

| Excepción | Descripción |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | si se supera el límite |

### Véase también
* clase [`IChartCategory`](/slides/python-net/es/aspose.slides.charts/ichartcategory)
* clase [`IChartCategoryCollection`](/slides/python-net/es/aspose.slides.charts/ichartcategorycollection)
* clase [`IChartDataCell`](/slides/python-net/es/aspose.slides.charts/ichartdatacell)
* clase [`IChartDataWorkbook`](/slides/python-net/es/aspose.slides.charts/ichartdataworkbook)
* módulo [`aspose.slides.charts`](/slides/python-net/es/aspose.slides.charts)
* biblioteca [`Aspose.Slides`](/slides/python-net)