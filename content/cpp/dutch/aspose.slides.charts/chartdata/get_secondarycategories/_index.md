---
title: get_SecondaryCategories()
second_title: Aspose.Slides voor C++ API-referentie
description: "Haalt de secundaire categorieën op als ChartData::get_UseSecondaryCategories waar is. Alleen-lezen IChartCategoryCollection."
type: docs
weight: 79
url: /nl/aspose.slides.charts/chartdata/get_secondarycategories/
---
## ChartData::get_SecondaryCategories() methode


Haalt de secundaire categorieën op als [ChartData::get_UseSecondaryCategories](../get_usesecondarycategories/) waar is. Alleen-lezen [IChartCategoryCollection](../../ichartcategorycollection/).

```cpp
System::SharedPtr<IChartCategoryCollection> Aspose::Slides::Charts::ChartData::get_SecondaryCategories() override
```

## Opmerkingen


Als [ChartData::set_UseSecondaryCategories](../set_usesecondarycategories/) is ingesteld op false, dan geeft [ChartData::get_SecondaryCategories](./) null terug en worden de gegevens in [ChartData::get_Categories](../get_categories/) zowel voor primaire als secundaire series gebruikt. Als [ChartData::set_UseSecondaryCategories](../set_usesecondarycategories/) is ingesteld op true, dan worden de gegevens in [ChartData::get_SecondaryCategories](./) gebruikt voor secundaire series en de gegevens in [ChartData::get_Categories](../get_categories/) gebruikt voor primaire series. 

Voorbeeld. Welke categorieën zijn gerelateerd aan series - [ChartData::get_Categories](../get_categories/) of [ChartData::get_SecondaryCategories](./)? 
```cpp
if (series->get_PlotOnSecondAxis() && series->get_Chart()->get_ChartData()->get_UseSecondaryCategories())
{
    // gerelateerde categorieën zijn series->get_Chart()->get_ChartData()->get_SecondaryCategories()
}
else
{
    // gerelateerde categorieën zijn series->get_Chart()->get_ChartData()->get_Categories()
}
```

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IChartCategoryCollection](../../ichartcategorycollection/)
* Klasse [ChartData](../)
* Naamruimte [Aspose::Slides::Charts](../../)
* Bibliotheek [Aspose.Slides](../../../)