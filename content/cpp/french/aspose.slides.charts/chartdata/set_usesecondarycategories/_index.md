---
title: set_UseSecondaryCategories()
second_title: Référence API Aspose.Slides pour C++
description: "Si la valeur est false alors ChartData::get_SecondaryCategories renvoie null et les données dans ChartData::get_Categories sont utilisées à la fois pour les séries primaires et secondaires. Si la valeur est true alors les données dans ChartData::get_SecondaryCategories sont utilisées pour les séries secondaires et les données dans ChartData::get_Categories sont utilisées pour les séries primaires. Écrire bool."
type: docs
weight: 66
url: /fr/aspose.slides.charts/chartdata/set_usesecondarycategories/
---
## ChartData::set_UseSecondaryCategories(bool) méthode

Si la valeur est false alors [ChartData::get_SecondaryCategories](../get_secondarycategories/) renvoie null et les données dans [ChartData::get_Categories](../get_categories/) sont utilisées à la fois pour les séries primaires et secondaires. Si la valeur est true alors les données dans [ChartData::get_SecondaryCategories](../get_secondarycategories/) sont utilisées pour les séries secondaires et les données dans [ChartData::get_Categories](../get_categories/) sont utilisées pour les séries primaires. Écrire **bool**.

```cpp
void Aspose::Slides::Charts::ChartData::set_UseSecondaryCategories(bool value) override
```

## Remarques

Exemple. Quelles catégories sont associées aux séries - [ChartData::get_Categories](../get_categories/) ou [ChartData::get_SecondaryCategories](../get_secondarycategories/) ? 
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