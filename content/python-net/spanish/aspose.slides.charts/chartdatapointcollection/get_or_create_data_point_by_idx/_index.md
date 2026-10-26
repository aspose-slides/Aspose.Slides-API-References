---
title: get_or_create_data_point_by_idx method
second_title: Referencia de API de Aspose.Slides para Python a través de .NET
description: 
type: docs
url: /es/aspose.slides.charts/chartdatapointcollection/get_or_create_data_point_by_idx/
weight: 190
---
## get_or_create_data_point_by_idx(self, index) {#int}
Si la colección ya contiene un punto de datos con el índice `index`, devuelve ese punto de datos.
            Si la colección no contiene un punto de datos con el índice `index`==N
            (cuando el número de puntos de datos en esta colección es menor o igual que N)
            entonces añade los puntos de datos faltantes y devuelve el último (que tiene el índice solicitado).
            Por ejemplo, los índices de la colección son {0, 1, 2}, y el índice solicitado es 5.
            Entonces el método añade los puntos de datos faltantes: {0, 1, 2, 3, 4, 5}. Y devuelve el punto de datos con el índice 5.

### Devuelve

Devuelve el punto de datos con el índice solicitado.



```python
def get_or_create_data_point_by_idx(self, index):
    ...
```


| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| index | **int** | Índice. |



### Véase también
* clase [`ChartDataPointCollection`](/slides/python-net/es/aspose.slides.charts/chartdatapointcollection)
* clase [`IChartDataPoint`](/slides/python-net/es/aspose.slides.charts/ichartdatapoint)
* módulo [`aspose.slides.charts`](/slides/python-net/es/aspose.slides.charts)
* biblioteca [`Aspose.Slides`](/slides/python-net)