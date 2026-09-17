---
title: add method
second_title: Referencia de API de Aspose.Slides para Python vía .NET
description: 
type: docs
url: /es/aspose.slides.charts/ichartcellcollection/add/
weight: 10
---
## add(self, chart_data_cell) {#ichartdatacell}
Agregar nueva cell a la colección.

```python
def add(self, chart_data_cell):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| chart_data_cell | [`IChartDataCell`](/slides/python-net/es/aspose.slides.charts/ichartdatacell) | Nueva cell a agregar. |

## add(self, value) {#any}
Crea [`IChartDataCell`](/slides/python-net/es/aspose.slides.charts/ichartdatacell) a partir del valor especificado y lo agrega a la colección.

```python
def add(self, value):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| value | **any** | El valor. |

### Observaciones

Este método agrega worksheet con el nombre AUTO_DATA y agrega todos los valores allí.  Si utiliza [`IChartDataWorkbook`](/slides/python-net/es/aspose.slides.charts/ichartdataworkbook) para agregar o editar valores Cell, asegúrese de no usar este worksheet
            El número máximo de valores agregados mediante este método no debe exceder 16711680

### Excepciones

| Excepción | Descripción |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | si se supera el límite |

### Ver también
* clase [`IChartCellCollection`](/slides/python-net/es/aspose.slides.charts/ichartcellcollection)
* clase [`IChartDataCell`](/slides/python-net/es/aspose.slides.charts/ichartdatacell)
* clase [`IChartDataWorkbook`](/slides/python-net/es/aspose.slides.charts/ichartdataworkbook)
* módulo [`aspose.slides.charts`](/slides/python-net/es/aspose.slides.charts)
* biblioteca [`Aspose.Slides`](/slides/python-net)