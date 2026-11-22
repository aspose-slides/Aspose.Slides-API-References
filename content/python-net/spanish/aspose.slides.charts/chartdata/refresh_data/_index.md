---
title: refresh_data method
second_title: Referencia de la API de Aspose.Slides para Python vía .NET
description: 
type: docs
url: /es/aspose.slides.charts/chartdata/refresh_data/
weight: 30
---
## refresh_data(self) {#}
Actualiza los datos del gráfico recargándolos desde el libro de origen.


```python
def refresh_data(self):
    ...
```


### Observaciones

Si el gráfico usa un libro externo, el libro debe estar accesible en el momento de la llamada.

### Excepciones

| Excepción | Descripción |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | Lanzado cuando el formato del libro no es compatible, o cuando [`ChartData.data_source_type`](/slides/python-net/es/aspose.slides.charts/chartdata/data_source_type) is<br/>            [`ChartDataSourceType.EXTERNAL_WORKBOOK`](/slides/python-net/es/aspose.slides.charts/chartdatasourcetype/EXTERNAL_WORKBOOK) y el libro externo no puede ser accedido o cargado. |



### Ver también
* clase [`ChartData`](/slides/python-net/es/aspose.slides.charts/chartdata)
* módulo [`aspose.slides.charts`](/slides/python-net/es/aspose.slides.charts)
* biblioteca [`Aspose.Slides`](/slides/python-net)