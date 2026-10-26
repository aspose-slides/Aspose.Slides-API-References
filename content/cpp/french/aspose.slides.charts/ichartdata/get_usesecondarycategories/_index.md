---
title: get_UseSecondaryCategories()
second_title: Référence de l'API Aspose.Slides for C++
description: "Si la valeur est false alors IChartData::get_SecondaryCategories renvoie null et les données dans IChartData::get_Categories sont utilisées à la fois pour les séries principales et secondaires. Si la valeur est true alors les données dans IChartData::get_SecondaryCategories sont utilisées pour les séries secondaires et les données dans IChartData::get_Categories sont utilisées pour les séries principales. Lire bool."
type: docs
weight: 53
url: /fr/aspose.slides.charts/ichartdata/get_usesecondarycategories/
---
## IChartData::get_UseSecondaryCategories() méthode


Si la valeur est false alors [IChartData::get_SecondaryCategories](../get_secondarycategories/) renvoie null et les données dans [IChartData::get_Categories](../get_categories/) sont utilisées à la fois pour les séries principales et secondaires. Si la valeur est true alors les données dans [IChartData::get_SecondaryCategories](../get_secondarycategories/) sont utilisées pour les séries secondaires et les données dans [IChartData::get_Categories](../get_categories/) sont utilisées pour les séries principales. Lecture **bool**.

```cpp
virtual bool Aspose::Slides::Charts::IChartData::get_UseSecondaryCategories()=0
```

## Remarques


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

* Classe [IChartData](../)
* Espace de noms [Aspose::Slides::Charts](../../)
* Bibliothèque [Aspose.Slides](../../../)