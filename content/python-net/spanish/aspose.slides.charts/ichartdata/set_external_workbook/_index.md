---
title: set_external_workbook method
second_title: Referencia de la API Aspose.Slides para Python vía .NET
description: 
type: docs
url: /es/aspose.slides.charts/ichartdata/set_external_workbook/
weight: 30
---
## set_external_workbook(self, workbook_path) {#str}
Establece el libro de trabajo externo como fuente de datos para el gráfico. Los datos del gráfico se actualizarán a partir del libro de trabajo objetivo.


```python
def set_external_workbook(self, workbook_path):
    ...
```


| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| workbook_path | **str** | Ruta al libro de trabajo objetivo |

### Excepciones

| Excepción | Descripción |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | El libro de trabajo externo no está disponible o no se puede cargar. |


## set_external_workbook(self, workbook_path, update_chart_data) {#str-bool}
Establece el libro de trabajo externo como fuente de datos para el gráfico.


```python
def set_external_workbook(self, workbook_path, update_chart_data):
    ...
```


| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| workbook_path | **str** | Ruta al libro de trabajo objetivo |
| update_chart_data | **bool** | Si el valor es false solo se actualizará la ruta del libro de trabajo. <br/><br/>             Los datos del gráfico no se cargarán ni actualizarán a partir del libro de trabajo objetivo. Puede usarse cuando el libro de trabajo objetivo no existe o no está disponible.<br/><br/>             Si el valor es true los datos del gráfico se actualizarán a partir del libro de trabajo objetivo. |

### Excepciones

| Excepción | Descripción |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | El libro de trabajo externo no está disponible o no se puede cargar. |



### Ver también
* clase [`IChartData`](/slides/python-net/es/aspose.slides.charts/ichartdata)
* módulo [`aspose.slides.charts`](/slides/python-net/es/aspose.slides.charts)
* biblioteca [`Aspose.Slides`](/slides/python-net)