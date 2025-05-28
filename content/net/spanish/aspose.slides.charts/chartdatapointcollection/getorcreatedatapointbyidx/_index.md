---
title: GetOrCreateDataPointByIdx
second_title: Referencia de la API de Aspose.Slides para .NET
description: Si la colección ya contiene un punto de datos con el índice index, entonces devuelve este punto de datos. Si la colección no contiene un punto de datos con el índice indexN cuando el número de puntos de datos en esta colección es menor o igual a N, entonces agrega los puntos de datos deficientes y devuelve el último que tiene el índice solicitado. Por ejemplo, los índices de la colección son 0, 1, 2 y el índice solicitado es 5. Entonces el método agrega puntos de datos deficientes 0, 1, 2, 3, 4, 5. Y devuelve el punto de datos con el índice 5.
type: docs
weight: 300
url: /es/aspose.slides.charts/chartdatapointcollection/getorcreatedatapointbyidx/
---

## Método ChartDataPointCollection.GetOrCreateDataPointByIdx

Si la colección ya contiene un punto de datos con el índice *index*, entonces devuelve este punto de datos. Si la colección no contiene un punto de datos con el índice *index*==N (cuando el número de puntos de datos en esta colección es menor o igual a N), entonces agrega los puntos de datos deficientes y devuelve el último (que tiene el índice solicitado). Por ejemplo, los índices de la colección son {0, 1, 2} y el índice solicitado es 5. Entonces el método agrega puntos de datos deficientes: {0, 1, 2, 3, 4, 5}. Y devuelve el punto de datos con el índice 5.

```csharp
public IChartDataPoint GetOrCreateDataPointByIdx(uint index)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | UInt32 | Índice. |

### Valor de Retorno

Devuelve el punto de datos con el índice solicitado.

### Véase También

* interfaz [IChartDataPoint](../../ichartdatapoint)
* clase [ChartDataPointCollection](../../chartdatapointcollection)
* espacio de nombres [Aspose.Slides.Charts](../../chartdatapointcollection)
* ensamblaje [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->