---
title: get_Categories()
second_title: Référence API Aspose.Slides pour C++
description: "Récupère les catégories principales (ou les catégories principales et secondaires si ChartData::set_UseSecondaryCategories est défini sur false). Lecture seule IChartCategoryCollection."
type: docs
weight: 40
url: /fr/aspose.slides.charts/chartdata/get_categories/
---
## ChartData::get_Categories() méthode

Récupère les catégories principales (ou les catégories principales et secondaires si [ChartData::set_UseSecondaryCategories](../set_usesecondarycategories/) est défini sur false). Lecture seule [IChartCategoryCollection](../../ichartcategorycollection/).

```cpp
System::SharedPtr<IChartCategoryCollection> Aspose::Slides::Charts::ChartData::get_Categories() override
```

## Remarques

Si [ChartData::set_UseSecondaryCategories](../set_usesecondarycategories/) est défini sur false alors [ChartData::get_SecondaryCategories](../get_secondarycategories/) renvoie null et les données dans [ChartData::get_Categories](./) sont utilisées à la fois pour les séries principales et secondaires. Si [ChartData::set_UseSecondaryCategories](../set_usesecondarycategories/) est défini sur true alors les données dans [ChartData::get_SecondaryCategories](../get_secondarycategories/) sont utilisées pour les séries secondaires et les données dans [ChartData::get_Categories](./) sont utilisées pour les séries principales. 

Exemple. Quelles catégories sont liées aux séries - [ChartData::get_Categories](./) ou [ChartData::get_SecondaryCategories](../get_secondarycategories/) ?
```cpp
if (series->get_PlotOnSecondAxis() && series->get_Chart()->get_ChartData()->get_UseSecondaryCategories())
{
    // related categories are series->get_Chart()->get_ChartData()->get_SecondaryCategories()
}
else
{
    // related categories are series->get_Chart()->get_ChartData()->get_Categories()
}
```

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IChartCategoryCollection](../../ichartcategorycollection/)
* Classe [ChartData](../)
* Espace de noms [Aspose::Slides::Charts](../../)
* Bibliothèque [Aspose.Slides](../../../)