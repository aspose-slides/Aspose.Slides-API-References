---
title: get_UseSecondaryCategories()
second_title: Référence API Aspose.Slides pour C++
description: "Si la valeur est false alors ChartData::get_SecondaryCategories renvoie null et les données dans ChartData::get_Categories sont utilisées à la fois pour les séries principales et secondaires. Si la valeur est true alors les données dans ChartData::get_SecondaryCategories sont utilisées pour les séries secondaires et les données dans ChartData::get_Categories sont utilisées pour les séries principales. Lire bool."
type: docs
weight: 53
url: /fr/aspose.slides.charts/chartdata/get_usesecondarycategories/
---
## ChartData::get_UseSecondaryCategories() méthode

Si la valeur est false, alors [ChartData::get_SecondaryCategories](../get_secondarycategories/) renvoie null et les données dans [ChartData::get_Categories](../get_categories/) sont utilisées à la fois pour les séries principales et secondaires. Si la valeur est true, alors les données dans [ChartData::get_SecondaryCategories](../get_secondarycategories/) sont utilisées pour les séries secondaires et les données dans [ChartData::get_Categories](../get_categories/) sont utilisées pour les séries principales. Lire **bool**.

```cpp
bool Aspose::Slides::Charts::ChartData::get_UseSecondaryCategories() override
```

## Remarques

Exemple. Quelles catégories sont liées aux séries - [ChartData::get_Categories](../get_categories/) ou [ChartData::get_SecondaryCategories](../get_secondarycategories/)? 
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

* Classe [ChartData](../)
* Espace de noms [Aspose::Slides::Charts](../../)
* Bibliothèque [Aspose.Slides](../../../)