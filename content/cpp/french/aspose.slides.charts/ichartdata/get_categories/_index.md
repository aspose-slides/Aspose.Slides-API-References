---
title: get_Categories()
second_title: Référence API Aspose.Slides pour C++
description: "Récupère les catégories principales (ou les catégories principales et secondaires si IChartData::set_UseSecondaryCategories est réglé sur false). Lecture seule IChartCategoryCollection."
type: docs
weight: 40
url: /fr/aspose.slides.charts/ichartdata/get_categories/
---
## IChartData::get_Categories() méthode

Récupère les catégories principales (ou les catégories principales et secondaires si [IChartData::set_UseSecondaryCategories](../set_usesecondarycategories/) est réglé sur false). Lecture seule [IChartCategoryCollection](../../ichartcategorycollection/).

```cpp
virtual System::SharedPtr<IChartCategoryCollection> Aspose::Slides::Charts::IChartData::get_Categories()=0
```

## Remarques

Si [IChartData::set_UseSecondaryCategories](../set_usesecondarycategories/) est réglé sur false alors [IChartData::get_SecondaryCategories](../get_secondarycategories/) renvoie null et les données dans [IChartData::get_Categories](./) sont utilisées à la fois pour les séries principales et secondaires. Si [IChartData::set_UseSecondaryCategories](../set_usesecondarycategories/) est réglé sur true alors les données dans [IChartData::get_SecondaryCategories](../get_secondarycategories/) sont utilisées pour les séries secondaires et les données dans [IChartData::get_Categories](./) sont utilisées pour les séries principales. 

Exemple. Quelles catégories sont liées aux séries - ChartData.Categories ou ChartData.SecondaryCategories ? 
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
* Bibliothèque [Aspose.Slides](../../../)