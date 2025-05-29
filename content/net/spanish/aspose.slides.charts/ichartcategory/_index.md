---
title: IChartCategory
second_title: Referencia de API de Aspose.Slides para .NET
description: Representa categorías de gráficos.
type: docs
weight: 1670
url: /es/aspose.slides.charts/ichartcategory/
---

## Interfaz IChartCategory

Representa categorías de gráficos.

```csharp
public interface IChartCategory
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [AsCell](../../aspose.slides.charts/ichartcategory/ascell) { get; set; } | Devuelve o establece el objeto IChartDataCell. Si la categoría es de múltiples niveles, entonces se utiliza el objeto IChartDataCell para el nivel "0". Lectura/escritura [`IChartDataCell`](../ichartdatacell). |
| [AsLiteral](../../aspose.slides.charts/ichartcategory/asliteral) { get; set; } | Devuelve o establece AsLiteral si UseCell es falso. Lectura/escritura Objeto. |
| [GroupingLevels](../../aspose.slides.charts/ichartcategory/groupinglevels) { get; } | Contenedor administrado de los valores de los niveles de agrupación de la categoría del gráfico. Las categorías de múltiples niveles contienen más de un nivel de agrupación. La indexación de los niveles de agrupación es basada en cero. Solo lectura [`IChartCategoryLevelsManager`](../ichartcategorylevelsmanager). |
| [UseCell](../../aspose.slides.charts/ichartcategory/usecell) { get; } | Si es verdadero, entonces la propiedad AsCell es actual. En otras palabras, la hoja de cálculo se utiliza para almacenar la categoría (este caso admite una categoría de múltiples niveles). Si es falso, entonces la propiedad AsLiteral es actual. En otras palabras, la hoja de cálculo NO se utiliza para almacenar la categoría (y este caso no admite categorías de múltiples niveles). Solo lectura Booleano. |
| [Value](../../aspose.slides.charts/ichartcategory/value) { get; set; } | Si UseCell es verdadero, entonces esta propiedad representa la propiedad AsCell.Value. Si UseCell es falso, entonces esta propiedad representa la propiedad AsLiteral. Lectura/escritura Objeto. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [Remove](../../aspose.slides.charts/ichartcategory/remove)() | Elimina la categoría del gráfico. |

### Ve también

* namespace [Aspose.Slides.Charts](../../aspose.slides.charts)
* assembly [Aspose.Slides](../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->