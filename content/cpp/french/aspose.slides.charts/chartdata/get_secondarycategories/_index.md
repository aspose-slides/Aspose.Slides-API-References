---
title: get_SecondaryCategories()
second_title: Référence de l'API Aspose.Slides pour C++
description: "Obtient les catégories secondaires si ChartData::get_UseSecondaryCategories est vrai. Lecture seule IChartCategoryCollection."
type: docs
weight: 79
url: /fr/aspose.slides.charts/chartdata/get_secondarycategories/
---
## ChartData::get_SecondaryCategories() méthode

Obtient les catégories secondaires si [ChartData::get_UseSecondaryCategories](../get_usesecondarycategories/) est vrai. Lecture seule [IChartCategoryCollection](../../ichartcategorycollection/).

```cpp
System::SharedPtr<IChartCategoryCollection> Aspose::Slides::Charts::ChartData::get_SecondaryCategories() override
```

## Remarques

Si [ChartData::set_UseSecondaryCategories](../set_usesecondarycategories/) est défini sur false alors [ChartData::get_SecondaryCategories](./) renvoie null et les données dans [ChartData::get_Categories](../get_categories/) sont utilisées à la fois pour les séries principales et secondaires. Si [ChartData::set_UseSecondaryCategories](../set_usesecondarycategories/) est défini sur true alors les données dans [ChartData::get_SecondaryCategories](./) sont utilisées pour les séries secondaires et les données dans [ChartData::get_Categories](../get_categories/) sont utilisées pour les séries principales. 

Exemple. Quelles catégories sont liées à la série - [ChartData::get_Categories](../get_categories/) ou [ChartData::get_SecondaryCategories](./)? 
```cpp
if (series->get_PlotOnSecondAxis() && series->get_Chart()->get_ChartData()->get_UseSecondaryCategories())
{
    // les catégories liées sont series->get_Chart()->get_ChartData()->get_SecondaryCategories()
}
else
{
    // les catégories liées sont series->get_Chart()->get_ChartData()->get_Categories()
}
```

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IChartCategoryCollection](../../ichartcategorycollection/)
* Classe [ChartData](../)
* Espace de noms [Aspose::Slides::Charts](../../)
* Bibliothèque [Aspose.Slides](../../../)