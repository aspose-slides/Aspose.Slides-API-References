---
title: get_Categories()
second_title: Aspose.Slides voor C++ API-referentie
description: "Haalt de primaire categorieën op (of zowel primaire als secundaire categorieën als IChartData::set_UseSecondaryCategories is ingesteld op false). Alleen-lezen IChartCategoryCollection."
type: docs
weight: 40
url: /nl/aspose.slides.charts/ichartdata/get_categories/
---
## IChartData::get_Categories() methode


Haalt de primaire categorieën op (of zowel de primaire als secundaire categorieën als [IChartData::set_UseSecondaryCategories](../set_usesecondarycategories/) is ingesteld op false). Alleen-lezen [IChartCategoryCollection](../../ichartcategorycollection/).

```cpp
virtual System::SharedPtr<IChartCategoryCollection> Aspose::Slides::Charts::IChartData::get_Categories()=0
```

## Opmerkingen


Als [IChartData::set_UseSecondaryCategories](../set_usesecondarycategories/) is ingesteld op false, dan geeft [IChartData::get_SecondaryCategories](../get_secondarycategories/) null terug en worden de gegevens in [IChartData::get_Categories](./) zowel voor primaire als secundaire series gebruikt. Als [IChartData::set_UseSecondaryCategories](../set_usesecondarycategories/) is ingesteld op true, dan worden de gegevens in [IChartData::get_SecondaryCategories](../get_secondarycategories/) voor secundaire series gebruikt en de gegevens in [IChartData::get_Categories](./) voor primaire series. 

Voorbeeld. Welke categorieën zijn gerelateerd aan series - ChartData.Categories of ChartData.SecondaryCategories? 
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
* Klasse [IChartData](../)
* Naamruimte [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)