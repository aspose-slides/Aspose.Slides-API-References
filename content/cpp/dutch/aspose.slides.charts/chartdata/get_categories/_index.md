---
title: get_Categories()
second_title: Aspose.Slides voor C++ API-referentie
description: "Haalt de primaire categorieën op (of zowel primaire als secundaire categorieën als ChartData::set_UseSecondaryCategories is ingesteld op false). Alleen-lezen IChartCategoryCollection."
type: docs
weight: 40
url: /nl/aspose.slides.charts/chartdata/get_categories/
---
## ChartData::get_Categories() methode

Haalt de primaire categorieën op (of zowel primaire als secundaire categorieën als [ChartData::set_UseSecondaryCategories](../set_usesecondarycategories/) op false is ingesteld). Alleen-lezen [IChartCategoryCollection](../../ichartcategorycollection/).

```cpp
System::SharedPtr<IChartCategoryCollection> Aspose::Slides::Charts::ChartData::get_Categories() override
```

## Opmerkingen

Als [ChartData::set_UseSecondaryCategories](../set_usesecondarycategories/) op false is ingesteld dan retourneert [ChartData::get_SecondaryCategories](../get_secondarycategories/) null en worden gegevens in [ChartData::get_Categories](./) zowel voor primaire als secundaire series gebruikt. Als [ChartData::set_UseSecondaryCategories](../set_usesecondarycategories/) op true is ingesteld dan worden gegevens in [ChartData::get_SecondaryCategories](../get_secondarycategories/) gebruikt voor secundaire series en gegevens in [ChartData::get_Categories](./) voor primaire series. 

Voorbeeld. Welke categorieën zijn gerelateerd aan series - [ChartData::get_Categories](./) of [ChartData::get_SecondaryCategories](../get_secondarycategories/)? 
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

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IChartCategoryCollection](../../ichartcategorycollection/)
* Klasse [ChartData](../)
* Naamruimte [Aspose::Slides::Charts](../../)
* Bibliotheek [Aspose.Slides](../../../)