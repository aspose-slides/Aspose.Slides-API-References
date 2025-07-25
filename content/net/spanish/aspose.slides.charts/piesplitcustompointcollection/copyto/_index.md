---
title: CopyTo
second_title: Aspose.Slides para .NET Referencia de API
description: Copia los elementos de ICollection a un Array comenzando en un índice particular del Array.
type: docs
weight: 90
url: /es/aspose.slides.charts/piesplitcustompointcollection/copyto/
---

## PieSplitCustomPointCollection.CopyTo método

Copia los elementos de ICollection a un Array, comenzando en un índice particular del Array.

```csharp
public void CopyTo(IChartDataPoint[] array, int arrayIndex)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| array | IChartDataPoint[] | El Array unidimensional que es el destino de los elementos copiados de ICollection. El Array debe tener índices basados en cero. |
| arrayIndex | Int32 | El índice basado en cero en *array* en el que comienza la copia. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentNullException | *array* es nulo. |
| ArgumentOutOfRangeException | *arrayIndex* es menor que 0. |
| ArgumentException | El número de elementos en la ICollection de origen es mayor que el espacio disponible desde *arrayIndex* hasta el final del *array* de destino. |

### Véase También

* interface [IChartDataPoint](../../ichartdatapoint)
* class [PieSplitCustomPointCollection](../../piesplitcustompointcollection)
* namespace [Aspose.Slides.Charts](../../piesplitcustompointcollection)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->