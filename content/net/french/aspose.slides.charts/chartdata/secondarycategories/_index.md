---
title: SecondaryCategories
second_title: Référence de l'API Aspose.Slides pour .NET
description: Obtient les catégories secondaires si la propriété UseSecondaryCategoriesaspose.slides.charts/chartdata/usesecondarycategories est vraie. Collection IChartCategoryCollectionaspose.slides.charts/ichartcategorycollection en lecture seule.
type: docs
weight: 50
url: /fr/aspose.slides.charts/chartdata/secondarycategories/
---

## Propriété ChartData.SecondaryCategories

Obtient les catégories secondaires si la propriété [`UseSecondaryCategories`](../usesecondarycategories) est vraie. Collection en lecture seule [`IChartCategoryCollection`](../../ichartcategorycollection).

```csharp
public IChartCategoryCollection SecondaryCategories { get; }
```

### Remarques

Si la propriété [`UseSecondaryCategories`](../usesecondarycategories) est fausse, alors cette propriété `SecondaryCategories` retourne null et les données de la propriété [`Categories`](../categories) sont utilisées à la fois pour les séries primaires et secondaires. Si la propriété [`UseSecondaryCategories`](../usesecondarycategories) est vraie, alors les données de cette propriété `SecondaryCategories` sont utilisées pour les séries secondaires et les données de la propriété [`Categories`](../categories) sont utilisées pour les séries primaires.

### Exemples

Exemple. Quelles catégories sont liées aux séries - ChartData.Categories ou ChartData.SecondaryCategories ?

```csharp
if (series.PlotOnSecondAxis && series.Chart.ChartData.UseSecondaryCategories)
{
    // les catégories associées sont series.Chart.ChartData.SecondaryCategories
}
else
{
    // les catégories associées sont series.Chart.ChartData.Categories
}
```

### Voir Aussi

* interface [IChartCategoryCollection](../../ichartcategorycollection)
* class [ChartData](../../chartdata)
* namespace [Aspose.Slides.Charts](../../chartdata)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->