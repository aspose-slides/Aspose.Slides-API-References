---
title: get_SecondaryCategories()
second_title: Aspose.Slides voor C++ API-referentie
description: "Haalt de secundaire categorieën op als IChartData::get_UseSecondaryCategories waar is. Alleen-lezen IChartCategoryCollection."
type: docs
weight: 79
url: /nl/aspose.slides.charts/ichartdata/get_secondarycategories/
---
## IChartData::get_SecondaryCategories() methode

Haalt de secundaire categorieën op als [IChartData::get_UseSecondaryCategories](../get_usesecondarycategories/) waar is. Alleen-lezen [IChartCategoryCollection](../../ichartcategorycollection/).

```cpp
virtual System::SharedPtr<IChartCategoryCollection> Aspose::Slides::Charts::IChartData::get_SecondaryCategories()=0
```

## Opmerkingen

Als [IChartData::set_UseSecondaryCategories](../set_usesecondarycategories/) is ingesteld op onwaar dan geeft [IChartData::get_SecondaryCategories](./) null terug en worden gegevens in [IChartData::get_Categories](../get_categories/) zowel voor primaire als secundaire series gebruikt. Als [IChartData::set_UseSecondaryCategories](../set_usesecondarycategories/) is ingesteld op waar dan worden gegevens in [IChartData::get_SecondaryCategories](./) voor secundaire series gebruikt en gegevens in [IChartData::get_Categories](../get_categories/) voor primaire series. 

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
* Bibliotheek [Aspose.Slides](../../../)