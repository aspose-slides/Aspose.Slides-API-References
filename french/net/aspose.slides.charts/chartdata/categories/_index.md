---
title: Categories
second_title: Référence de l'API Aspose.Slides pour .NET
description: Obtient les catégories principales ou les catégories principales et secondaires siUseSecondaryCategoriesaspose.slides.charts/chartdata/usesecondarycategories propriété est fausse. Lecture seuleIChartCategoryCollectionaspose.slides.charts/ichartcategorycollection .
type: docs
weight: 10
url: /fr/net/aspose.slides.charts/chartdata/categories/
---
## ChartData.Categories property

Obtient les catégories principales (ou les catégories principales et secondaires si[`UseSecondaryCategories`](../usesecondarycategories) propriété est fausse). Lecture seule[`IChartCategoryCollection`](../../ichartcategorycollection) .

```csharp
public IChartCategoryCollection Categories { get; }
```

### Remarques

Si[`UseSecondaryCategories`](../usesecondarycategories) la propriété est fausse alors[`SecondaryCategories`](../secondarycategories) La propriété renvoie null et les données dans ce`Categories` La propriété est utilisée à la fois pour les séries primaires et secondaires. Si[`UseSecondaryCategories`](../usesecondarycategories) la propriété est vraie alors les données dans[`SecondaryCategories`](../secondarycategories) La propriété est utilisée pour les séries secondaires et les données dans ce`Categories` la propriété est utilisée pour la série primaire.

### Exemples

Exemple. Quelles catégories sont liées aux séries - ChartData.Categories ou ChartData.SecondaryCategories?

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

### Voir également

* interface [IChartCategoryCollection](../../ichartcategorycollection)
* class [ChartData](../../chartdata)
* espace de noms [Aspose.Slides.Charts](../../chartdata)
* Assemblée [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->