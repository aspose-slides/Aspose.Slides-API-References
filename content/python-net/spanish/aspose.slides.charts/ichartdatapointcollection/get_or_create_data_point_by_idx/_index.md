---
title: get_or_create_data_point_by_idx method
second_title: Referencia de API de Aspose.Slides para Python vía .NET
description: 
type: docs
url: /es/aspose.slides.charts/ichartdatapointcollection/get_or_create_data_point_by_idx/
weight: 190
---
## get_or_create_data_point_by_idx(self, index) {#int}
If collection already contains data point with index `index` then returns this data point.
            Si la colección no contiene un punto de datos con el índice `index`==N
            (cuando el número de puntos de datos en esta colección es menor o igual que N)
            entonces añade puntos de datos deficientes y devuelve el último (que tiene el índice solicitado).
            Por ejemplo, los índices de la colección son {0, 1, 2}, y el índice solicitado es 5.
            Entonces el método añade puntos de datos deficientes: {0, 1, 2, 3, 4, 5}. Y devuelve el punto de datos con el índice 5.

### Devuelve

Devuelve el punto de datos con el índice solicitado.



```python
def get_or_create_data_point_by_idx(self, index):
    ...
```


| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| index | **int** | Índice. |



### Ver también
* clase [`IChartDataPoint`](/slides/python-net/es/aspose.slides.charts/ichartdatapoint)
* clase [`IChartDataPointCollection`](/slides/python-net/es/aspose.slides.charts/ichartdatapointcollection)
* módulo [`aspose.slides.charts`](/slides/python-net/es/aspose.slides.charts)
* biblioteca [`Aspose.Slides`](/slides/python-net)