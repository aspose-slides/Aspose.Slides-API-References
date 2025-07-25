---
title: UseSecondaryCategories
second_title: Aspose.Sildes para referencia de la API de .NET
description: Si es falso, entonces la propiedad SecondaryCategoriesaspose.slides.charts/chartdata/secondarycategories devuelve null y los datos en la propiedad Categoriesaspose.slides.charts/chartdata/categories se utilizan tanto para las series primarias como secundarias. Si es verdadero, entonces los datos en la propiedad SecondaryCategoriesaspose.slides.charts/chartdata/secondarycategories se utilizan para las series secundarias y los datos en la propiedad Categoriesaspose.slides.charts/chartdata/categories se utilizan para las series primarias. Booleano de lectura/escritura.
type: docs
weight: 80
url: /es/aspose.slides.charts/chartdata/usesecondarycategories/
---

## ChartData.UseSecondaryCategories property

Si es falso, entonces la propiedad [`SecondaryCategories`](../secondarycategories) devuelve null y los datos en la propiedad [`Categories`](../categories) se utilizan tanto para las series primarias como secundarias. Si es verdadero, entonces los datos en la propiedad [`SecondaryCategories`](../secondarycategories) se utilizan para las series secundarias y los datos en la propiedad [`Categories`](../categories) se utilizan para las series primarias. Booleano de lectura/escritura.

```csharp
public bool UseSecondaryCategories { get; set; }
```

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

* clase [ChartData](../../chartdata)
* espacio de nombres [Aspose.Slides.Charts](../../chartdata)
* ensamblado [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
