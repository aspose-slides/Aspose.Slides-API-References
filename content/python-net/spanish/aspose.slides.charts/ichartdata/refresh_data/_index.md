---
title: refresh_data method
second_title: Referencia de API de Aspose.Slides para Python vía .NET
description: 
type: docs
url: /es/aspose.slides.charts/ichartdata/refresh_data/
weight: 30
---
## refresh_data(self) {#}
Actualiza los datos del gráfico recargándolos desde el libro de trabajo origen.

```python
def refresh_data(self):
    ...
```

### Observaciones

Si el gráfico utiliza un libro de trabajo externo, el libro de trabajo debe estar accesible en el momento de la llamada.

### Excepciones

| Excepción | Descripción |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | Se lanza cuando el formato del libro de trabajo no es compatible, o cuando [`IChartData.data_source_type`](/slides/python-net/es/aspose.slides.charts/ichartdata/data_source_type) es<br/>            [`ChartDataSourceType.EXTERNAL_WORKBOOK`](/slides/python-net/es/aspose.slides.charts/chartdatasourcetype/EXTERNAL_WORKBOOK) y el libro de trabajo externo no puede ser accedido o cargado. |

### Ver también
* clase [`IChartData`](/slides/python-net/es/aspose.slides.charts/ichartdata)
* módulo [`aspose.slides.charts`](/slides/python-net/es/aspose.slides.charts)
* biblioteca [`Aspose.Slides`](/slides/python-net)