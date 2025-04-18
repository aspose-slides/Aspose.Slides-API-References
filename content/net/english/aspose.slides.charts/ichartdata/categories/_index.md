---
title: Categories
second_title: Aspose.Sildes for .NET API Reference
description: Gets the primary categories or both primary and secondary categories if UseSecondaryCategoriesaspose.slides.charts/ichartdata/usesecondarycategories property is false. Read-only IChartCategoryCollectionaspose.slides.charts/ichartcategorycollection.
type: docs
weight: 10
url: /aspose.slides.charts/ichartdata/categories/
---

## IChartData.Categories property

Gets the primary categories (or both primary and secondary categories if [`UseSecondaryCategories`](../usesecondarycategories) property is false). Read-only [`IChartCategoryCollection`](../../ichartcategorycollection).

```csharp
public IChartCategoryCollection Categories { get; }
```

### Remarks

If [`UseSecondaryCategories`](../usesecondarycategories) property is false then [`SecondaryCategories`](../secondarycategories) property return null and data in this `Categories` property is used both for primary and secondary series. If [`UseSecondaryCategories`](../usesecondarycategories) property is true then data in [`SecondaryCategories`](../secondarycategories) property is used for secondary series and data in this `Categories` property is used for primary series.

### Examples

Example. What categories are related to series - ChartData.Categories or ChartData.SecondaryCategories?

```csharp
if (series.PlotOnSecondAxis && series.Chart.ChartData.UseSecondaryCategories)
{
    // related categories are series.Chart.ChartData.SecondaryCategories
}
else
{
    // related categories are series.Chart.ChartData.Categories
}
```

### See Also

* interface [IChartCategoryCollection](../../ichartcategorycollection)
* interface [IChartData](../../ichartdata)
* namespace [Aspose.Slides.Charts](../../ichartdata)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
