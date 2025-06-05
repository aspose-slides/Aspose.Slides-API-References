---
title: SecondaryCategories
second_title: Referencia de API de Aspose.Slides para .NET
description: Obtiene las categorías secundarias si la propiedad UseSecondaryCategoriesaspose.slides.charts/chartdata/usesecondarycategories es verdadera. Solo lectura IChartCategoryCollectionaspose.slides.charts/ichartcategorycollection.
type: docs
weight: 50
url: /es/aspose.slides.charts/chartdata/secondarycategories/
---

## Propiedad ChartData.SecondaryCategories

Obtiene las categorías secundarias si la propiedad [`UseSecondaryCategories`](../usesecondarycategories) es verdadera. Solo lectura [`IChartCategoryCollection`](../../ichartcategorycollection).

```csharp
public IChartCategoryCollection SecondaryCategories { get; }
```

### Observaciones

Si la propiedad [`UseSecondaryCategories`](../usesecondarycategories) es falsa, entonces la propiedad `SecondaryCategories` retorna null y los datos en la propiedad [`Categories`](../categories) se utilizan tanto para las series primarias como para las secundarias. Si la propiedad [`UseSecondaryCategories`](../usesecondarycategories) es verdadera, entonces los datos en esta propiedad `SecondaryCategories` se utilizan para las series secundarias y los datos en la propiedad [`Categories`](../categories) se utilizan para las series primarias.

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

### Ver También

* interfaz [IChartCategoryCollection](../../ichartcategorycollection)
* clase [ChartData](../../chartdata)
* espacio de nombres [Aspose.Slides.Charts](../../chartdata)
* ensamblaje [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->