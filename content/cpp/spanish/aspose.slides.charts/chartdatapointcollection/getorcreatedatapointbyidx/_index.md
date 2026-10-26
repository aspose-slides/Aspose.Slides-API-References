---
title: GetOrCreateDataPointByIdx()
second_title: Referencia de API de Aspose.Slides para C++
description: "Si la colección ya contiene un punto de datos con el índice index, entonces devuelve ese punto de datos. Si la colección no contiene un punto de datos con el índice index ==N (cuando el número de puntos de datos en esta colección es menor o igual que N), entonces agrega los puntos de datos deficientes y devuelve el último (que tiene el índice solicitado). Por ejemplo, los índices de la colección son {0, 1, 2} y el índice solicitado es 5. Entonces el método agrega los puntos de datos deficientes: {0, 1, 2, 3, 4, 5}. Y devuelve el punto de datos con el índice 5."
type: docs
weight: 170
url: /es/aspose.slides.charts/chartdatapointcollection/getorcreatedatapointbyidx/
---
## ChartDataPointCollection::GetOrCreateDataPointByIdx(uint32_t) método

Si la colección ya contiene un punto de datos con el índice *index* entonces devuelve ese punto de datos. Si la colección no contiene un punto de datos con el índice *index* ==N (cuando el número de puntos de datos en esta colección es menor o igual que N) entonces añade los puntos de datos deficientes y devuelve el último (que tiene el índice solicitado). Por ejemplo, los índices de la colección son {0, 1, 2}, y el índice solicitado es 5. Entonces el método añade los puntos de datos deficientes: {0, 1, 2, 3, 4, 5}. Y devuelve el punto de datos con el índice 5.

```cpp
System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::ChartDataPointCollection::GetOrCreateDataPointByIdx(uint32_t index) override
```

### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| index | **uint32_t** | Índice. |

### Valor devuelto

Devuelve el punto de datos con el índice solicitado.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IChartDataPoint](../../ichartdatapoint/)
* Class [ChartDataPointCollection](../)
* Namespace [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)