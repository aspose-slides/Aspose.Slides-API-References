---
title: ChartCategory
second_title: Referencia de API de Aspose.Slides para .NET
description: Representa categorías de gráficos.
type: docs
weight: 1190
url: /es/aspose.slides.charts/chartcategory/
---

## Clase ChartCategory

Representa categorías de gráficos.

```csharp
public class ChartCategory : IChartCategory
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [AsCell](../../aspose.slides.charts/chartcategory/ascell) { get; set; } | Devuelve o establece el objeto IChartDataCell. Si la categoría es de varios niveles, se utiliza el objeto IChartDataCell para el nivel "0". Lectura/escritura [`IChartDataCell`](../ichartdatacell). |
| [AsLiteral](../../aspose.slides.charts/chartcategory/asliteral) { get; set; } | Devuelve o establece el objeto AsLiteral. Lectura/escritura Objeto. |
| [GroupingLevels](../../aspose.slides.charts/chartcategory/groupinglevels) { get; } | Contenedor administrado de los valores de los niveles de agrupación de categorías del gráfico. Las categorías de varios niveles contienen más de un nivel de agrupación. La indexación de los niveles de agrupación es basada en cero. Solo lectura [`IChartCategoryLevelsManager`](../ichartcategorylevelsmanager). |
| [UseCell](../../aspose.slides.charts/chartcategory/usecell) { get; } | Si es verdadero, la propiedad AsCell es actual. En otras palabras, se utiliza la hoja de trabajo para almacenar la categoría (este caso admite una categoría de varios niveles). Si es falso, la propiedad AsLiteral es actual. En otras palabras, NO se utiliza la hoja de trabajo para almacenar la categoría (y este caso no admite categorías de varios niveles). Solo lectura Booleano. |
| [Value](../../aspose.slides.charts/chartcategory/value) { get; set; } | Si UseCell es verdadero, esta propiedad representa la propiedad AsCell.Value. Si UseCell es falso, esta propiedad representa la propiedad AsLiteral. Lectura/escritura Objeto. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [Remove](../../aspose.slides.charts/chartcategory/remove)() | Elimina la categoría del gráfico. |

### Ver También

* interfaz [IChartCategory](../ichartcategory)
* espacio de nombres [Aspose.Slides.Charts](../../aspose.slides.charts)
* ensamblaje [Aspose.Slides](../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->