---
title: get_SecondaryCategories()
second_title: Référence de l'API Aspose.Slides pour C++
description: "Obtient les catégories secondaires si IChartData::get_UseSecondaryCategories est vrai. Lecture seule IChartCategoryCollection."
type: docs
weight: 79
url: /fr/aspose.slides.charts/ichartdata/get_secondarycategories/
---
## IChartData::get_SecondaryCategories() méthode

Obtient les catégories secondaires si [IChartData::get_UseSecondaryCategories](../get_usesecondarycategories/) est vrai. Lecture seule [IChartCategoryCollection](../../ichartcategorycollection/).

```cpp
virtual System::SharedPtr<IChartCategoryCollection> Aspose::Slides::Charts::IChartData::get_SecondaryCategories()=0
```

## Remarques

Si [IChartData::set_UseSecondaryCategories](../set_usesecondarycategories/) est défini sur false alors [IChartData::get_SecondaryCategories](./) renvoie null et les données dans [IChartData::get_Categories](../get_categories/) sont utilisées à la fois pour les séries primaires et secondaires. Si [IChartData::set_UseSecondaryCategories](../set_usesecondarycategories/) est défini sur true alors les données dans [IChartData::get_SecondaryCategories](./) sont utilisées pour les séries secondaires et les données dans [IChartData::get_Categories](../get_categories/) sont utilisées pour les séries primaires.

Exemple. Quelles catégories sont liées aux séries - ChartData.Categories ou ChartData.SecondaryCategories?

```cpp
if (series->get_PlotOnSecondAxis() && series->get_Chart()->get_ChartData()->get_UseSecondaryCategories())
{
    // les catégories associées sont series->get_Chart()->get_ChartData()->get_SecondaryCategories()
}
else
{
    // les catégories associées sont series->get_Chart()->get_ChartData()->get_Categories()
}
```

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IChartCategoryCollection](../../ichartcategorycollection/)
* Classe [IChartData](../)
* Espace de noms [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)