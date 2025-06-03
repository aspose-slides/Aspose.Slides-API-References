---
title: Categories
second_title: Referencia de la API de Aspose.Slides para .NET
description: Obtiene las categorías primarias o tanto las categorías primarias como las secundarias si la propiedad UseSecondaryCategoriesaspose.slides.charts/ichartdata/usesecondarycategories es falsa. Solo lectura IChartCategoryCollectionaspose.slides.charts/ichartcategorycollection.
type: docs
weight: 10
url: /es/aspose.slides.charts/ichartdata/categories/
---

## Propiedad IChartData.Categories

Obtiene las categorías primarias (o tanto las categorías primarias como las secundarias si la propiedad [`UseSecondaryCategories`](../usesecondarycategories) es falsa). Solo lectura [`IChartCategoryCollection`](../../ichartcategorycollection).

```csharp
public IChartCategoryCollection Categories { get; }
```

### Observaciones

Si la propiedad [`UseSecondaryCategories`](../usesecondarycategories) es falsa, entonces la propiedad [`SecondaryCategories`](../secondarycategories) devuelve null y los datos en esta propiedad `Categories` se utilizan tanto para las series primarias como para las secundarias. Si la propiedad [`UseSecondaryCategories`](../usesecondarycategories) es verdadera, entonces los datos en la propiedad [`SecondaryCategories`](../secondarycategories) se utilizan para las series secundarias y los datos en esta propiedad `Categories` se utilizan para las series primarias.

### Ejemplos

Ejemplo. ¿Qué categorías están relacionadas con la serie - ChartData.Categories o ChartData.SecondaryCategories?

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

### Ver también

* interfaz [IChartCategoryCollection](../../ichartcategorycollection)
* interfaz [IChartData](../../ichartdata)
* espacio de nombres [Aspose.Slides.Charts](../../ichartdata)
* ensamblado [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->