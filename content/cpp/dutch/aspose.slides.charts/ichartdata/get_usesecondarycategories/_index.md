---
title: get_UseSecondaryCategories()
second_title: Aspose.Slides voor C++ API-referentie
description: "Indien ingesteld op false dan retourneert IChartData::get_SecondaryCategories null en worden gegevens in IChartData::get_Categories zowel voor primaire als secundaire reeksen gebruikt. Indien ingesteld op true dan worden gegevens in IChartData::get_SecondaryCategories gebruikt voor secundaire reeksen en gegevens in IChartData::get_Categories gebruikt voor primaire reeksen. Lees bool."
type: docs
weight: 53
url: /nl/aspose.slides.charts/ichartdata/get_usesecondarycategories/
---
## IChartData::get_UseSecondaryCategories() methode

Als ingesteld op false dan [IChartData::get_SecondaryCategories](../get_secondarycategories/) null retourneert en data in [IChartData::get_Categories](../get_categories/) zowel voor primaire als secundaire reeksen wordt gebruikt. Als ingesteld op true dan worden data in [IChartData::get_SecondaryCategories](../get_secondarycategories/) gebruikt voor secundaire reeksen en data in [IChartData::get_Categories](../get_categories/) voor primaire reeksen. Lees **bool**.

```cpp
virtual bool Aspose::Slides::Charts::IChartData::get_UseSecondaryCategories()=0
```

## Opmerkingen

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

* Klasse [IChartData](../)
* Naamruimte [Aspose::Slides::Charts](../../)
* Bibliotheek [Aspose.Slides](../../../)