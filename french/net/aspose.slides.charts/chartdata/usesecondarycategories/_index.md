---
title: UseSecondaryCategories
second_title: Référence de l'API Aspose.Slides pour .NET
description: Si faux alorsSecondaryCategoriesaspose.slides.charts/chartdata/secondarycategories la propriété renvoie null et les données dansCategoriesaspose.slides.charts/chartdata/categories la propriété est utilisée à la fois pour les séries primaires et secondaires. Si vrai alors les données dansSecondaryCategoriesaspose.slides.charts/chartdata/secondarycategories la propriété est utilisée pour les séries secondaires et les données dansCategoriesaspose.slides.charts/chartdata/categoriesla propriété est utilisée pour la série primaire. Lecture/écritureBoolean .
type: docs
weight: 80
url: /fr/net/aspose.slides.charts/chartdata/usesecondarycategories/
---
## ChartData.UseSecondaryCategories property

Si faux alors[`SecondaryCategories`](../secondarycategories) la propriété renvoie null et les données dans[`Categories`](../categories) la propriété est utilisée à la fois pour les séries primaires et secondaires. Si vrai, alors les données dans[`SecondaryCategories`](../secondarycategories) la propriété est utilisée pour les séries secondaires et les données dans[`Categories`](../categories)la propriété est utilisée pour la série primaire. Lecture/écritureBoolean .

```csharp
public bool UseSecondaryCategories { get; set; }
```

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

* class [ChartData](../../chartdata)
* espace de noms [Aspose.Slides.Charts](../../chartdata)
* Assemblée [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->