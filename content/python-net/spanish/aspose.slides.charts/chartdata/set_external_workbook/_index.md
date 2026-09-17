---
title: set_external_workbook method
second_title: Referencia de API Aspose.Slides para Python via .NET
description: 
type: docs
url: /es/aspose.slides.charts/chartdata/set_external_workbook/
weight: 30
---
## set_external_workbook(self, workbook_path) {#str}
Establece un libro de trabajo externo como fuente de datos para el gráfico. Los datos del gráfico se actualizarán desde el libro de trabajo de destino.


```python
def set_external_workbook(self, workbook_path):
    ...
```


| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| workbook_path | **str** | Ruta al libro de trabajo de destino |

### Excepciones

| Excepción | Descripción |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | El libro de trabajo externo no está disponible o no se puede cargar. |


## set_external_workbook(self, workbook_path, update_chart_data) {#str-bool}
Establece un libro de trabajo externo como fuente de datos para el gráfico.


```python
def set_external_workbook(self, workbook_path, update_chart_data):
    ...
```


| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| workbook_path | **str** | Ruta al libro de trabajo de destino |
| update_chart_data | **bool** | Si el valor es false solo se actualizará la ruta del libro de trabajo. <br/><br/>             Los datos del gráfico no se cargarán ni actualizarán desde el libro de trabajo de destino. Puede usarse cuando el libro de trabajo de destino no exista o no esté disponible.<br/><br/>             Si el valor es true los datos del gráfico se actualizarán desde el libro de trabajo de destino. |

### Excepciones

| Excepción | Descripción |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | El libro de trabajo externo no está disponible o no se puede cargar. |



### Ver también
* clase [`ChartData`](/slides/python-net/es/aspose.slides.charts/chartdata)
* módulo [`aspose.slides.charts`](/slides/python-net/es/aspose.slides.charts)
* biblioteca [`Aspose.Slides`](/slides/python-net)