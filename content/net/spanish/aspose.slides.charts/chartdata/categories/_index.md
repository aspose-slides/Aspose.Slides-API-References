---
title: Categorías
second_title: Referencia de la API de Aspose.Sildes para .NET
description: Obtiene las categorías primarias o tanto las categorías primarias como las secundarias si la propiedad UseSecondaryCategoriesaspose.slides.charts/chartdata/usesecondarycategories es falsa. Solo de lectura IChartCategoryCollectionaspose.slides.charts/ichartcategorycollection.
type: docs
weight: 10
url: /es/aspose.slides.charts/chartdata/categories/
---

## Propiedad ChartData.Categories

Obtiene las categorías primarias (o tanto las categorías primarias como las secundarias si la propiedad [`UseSecondaryCategories`](../usesecondarycategories) es falsa). Solo de lectura [`IChartCategoryCollection`](../../ichartcategorycollection).

```csharp
public IChartCategoryCollection Categories { get; }
```

### Observaciones

Si la propiedad [`UseSecondaryCategories`](../usesecondarycategories) es falsa, entonces la propiedad [`SecondaryCategories`](../secondarycategories) devuelve nulo y los datos en esta propiedad `Categories` se utilizan tanto para las series primarias como secundarias. Si la propiedad [`UseSecondaryCategories`](../usesecondarycategories) es verdadera, entonces los datos en la propiedad [`SecondaryCategories`](../secondarycategories) se utilizan para las series secundarias y los datos en esta propiedad `Categories` se utilizan para las series primarias.

### Ejemplos

Ejemplo. ¿Qué categorías están relacionadas con las series: ChartData.Categories o ChartData.SecondaryCategories?

```csharp
if (series.PlotOnSecondAxis && series.Chart.ChartData.UseSecondaryCategories)
{
    // las categorías relacionadas son series.Chart.ChartData.SecondaryCategories
}
else
{
    // las categorías relacionadas son series.Chart.ChartData.Categories
}
```

### Ver También

* interfaz [IChartCategoryCollection](../../ichartcategorycollection)
* clase [ChartData](../../chartdata)
* espacio de nombres [Aspose.Slides.Charts](../../chartdata)
* ensamblado [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->