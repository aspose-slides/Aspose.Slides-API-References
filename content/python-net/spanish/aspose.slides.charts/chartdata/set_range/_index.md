---
title: set_range method
second_title: Referencia de la API Aspose.Slides para Python vía .NET
description: 
type: docs
url: /es/aspose.slides.charts/chartdata/set_range/
weight: 40
---
## set_range(self, formula) {#str}
Establece el rango de datos del gráfico. Las series y categorías se actualizarán en función del nuevo rango de datos.
            Si la cantidad de series en el rango de datos es mayor que el recuento de series en los datos del gráfico, se añadirán series adicionales del mismo tipo
            que la última serie en la colección actual, al final de la colección.


```python
def set_range(self, formula):
    ...
```


| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| formula | **str** | La fórmula del rango de datos de celdas. Por ejemplo: "Sheet1!$A$1:$C$4" , "SomeSheetName!A1:B100", "Sheet1!$A$1:$B$5;Sheet1!$D$1:$D$5". |

### Excepciones

| Excepción | Descripción |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | formula es None. |
| **RuntimeError(Proxy error(InvalidOperationException))** | Tipo de gráfico no compatible |
| **RuntimeError(Proxy error(ArgumentException))** | formula tiene un formato incorrecto. |



### Ver también
* clase [`ChartData`](/slides/python-net/es/aspose.slides.charts/chartdata)
* módulo [`aspose.slides.charts`](/slides/python-net/es/aspose.slides.charts)
* biblioteca [`Aspose.Slides`](/slides/python-net)