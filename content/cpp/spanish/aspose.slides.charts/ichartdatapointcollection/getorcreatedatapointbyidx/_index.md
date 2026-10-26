---
title: GetOrCreateDataPointByIdx()
second_title: Referencia de la API de Aspose.Slides para C++
description: "Si la colección ya contiene un punto de datos con el índice *index* entonces devuelve este punto de datos. Si la colección no contiene un punto de datos con el índice *index* ==N (cuando el número de puntos de datos en esta colección es menor o igual que N) entonces agrega puntos de datos deficientes y devuelve el último (que tiene el índice solicitado). Por ejemplo, los índices de la colección son {0, 1, 2}, y el índice solicitado es 5. Entonces el método agrega puntos de datos deficientes: {0, 1, 2, 3, 4, 5}. Y devuelve el punto de datos con el índice 5."
type: docs
weight: 131
url: /es/aspose.slides.charts/ichartdatapointcollection/getorcreatedatapointbyidx/
---
## IChartDataPointCollection::GetOrCreateDataPointByIdx(uint32_t) method


Si la colección ya contiene un punto de datos con el índice *index* entonces devuelve este punto de datos. Si la colección no contiene un punto de datos con el índice *index* ==N (cuando el número de puntos de datos en esta colección es menor o igual que N) entonces agrega los puntos de datos deficientes y devuelve el último (que tiene el índice solicitado). Por ejemplo, los índices de la colección son {0, 1, 2}, y el índice solicitado es 5. Entonces el método agrega los puntos de datos deficientes: {0, 1, 2, 3, 4, 5}. Y devuelve el punto de datos con el índice 5.

```cpp
virtual System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::IChartDataPointCollection::GetOrCreateDataPointByIdx(uint32_t index)=0
```


### Arguments

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | **uint32_t** | Índice. |

### Return Value

Devuelve el punto de datos con el índice solicitado.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IChartDataPoint](../../ichartdatapoint/)
* Class [IChartDataPointCollection](../)
* Namespace [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)