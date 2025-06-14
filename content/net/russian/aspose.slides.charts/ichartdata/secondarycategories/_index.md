---
title: SecondaryCategories
second_title: Aspose.Sildes для .NET API Reference
description: Получает вторичные категории, если свойство UseSecondaryCategoriesaspose.slides.charts/ichartdata/usesecondarycategories истинно. Только для чтения IChartCategoryCollectionaspose.slides.charts/ichartcategorycollection.
type: docs
weight: 50
url: /ru/aspose.slides.charts/ichartdata/secondarycategories/
---

## IChartData.SecondaryCategories property

Получает вторичные категории, если свойство [`UseSecondaryCategories`](../usesecondarycategories) истинно. Только для чтения [`IChartCategoryCollection`](../../ichartcategorycollection).

```csharp
public IChartCategoryCollection SecondaryCategories { get; }
```

### Remarks

Если свойство [`UseSecondaryCategories`](../usesecondarycategories) ложно, то это свойство `SecondaryCategories` возвращает null, и данные в свойстве [`Categories`](../categories) используются как для первичных, так и для вторичных серий. Если свойство [`UseSecondaryCategories`](../usesecondarycategories) истинно, то данные в этом свойстве `SecondaryCategories` используются для вторичных серий, а данные в свойстве [`Categories`](../categories) используются для первичных серий.

### Examples

Пример. Какие категории относятся к серии - ChartData.Categories или ChartData.SecondaryCategories?

```csharp
if (series.PlotOnSecondAxis && series.Chart.ChartData.UseSecondaryCategories)
{
    // связанные категории - series.Chart.ChartData.SecondaryCategories
}
else
{
    // связанные категории - series.Chart.ChartData.Categories
}
```

### See Also

* интерфейс [IChartCategoryCollection](../../ichartcategorycollection)
* интерфейс [IChartData](../../ichartdata)
* пространство имен [Aspose.Slides.Charts](../../ichartdata)
* сборка [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->