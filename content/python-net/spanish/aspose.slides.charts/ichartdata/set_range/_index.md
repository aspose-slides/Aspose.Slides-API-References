---
title: set_range method
second_title: Referencia API de Aspose.Slides para Python vía .NET
description: 
type: docs
url: /es/aspose.slides.charts/ichartdata/set_range/
weight: 40
---
## set_range(self, formula) {#str}
Establece el rango de datos del gráfico. Las series y categorías se actualizarán en función del nuevo rango de datos.
            Si la cantidad de series en el rango de datos es mayor que el número de series en los datos del gráfico, entonces se agregarán series adicionales del mismo tipo que la última serie de la colección actual al final de la colección.


```python
def set_range(self, formula):
    ...
```


| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| formula | **str** | El rango de datos de celdas formula. Por ejemplo: "Sheet1!$A$1:$C$4" , "SomeSheetName!A1:B100", "Sheet1!$A$1:$B$5;Sheet1!$D$1:$D$5". |

### Excepciones

| Excepción | Descripción |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | formula es None. |
| **RuntimeError(Proxy error(ArgumentException))** | formula tiene un formato incorrecto. |



### Ver también
* clase [`IChartData`](/slides/python-net/es/aspose.slides.charts/ichartdata)
* módulo [`aspose.slides.charts`](/slides/python-net/es/aspose.slides.charts)
* biblioteca [`Aspose.Slides`](/slides/python-net)