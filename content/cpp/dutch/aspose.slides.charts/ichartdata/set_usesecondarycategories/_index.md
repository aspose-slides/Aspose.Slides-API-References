---
title: set_UseSecondaryCategories()
second_title: Aspose.Slides voor C++ API-referentie
description: "Als ingesteld op false, dan retourneert IChartData::get_SecondaryCategories null en worden gegevens in IChartData::get_Categories zowel voor primaire als secundaire series gebruikt. Als ingesteld op true, dan worden gegevens in IChartData::get_SecondaryCategories gebruikt voor secundaire series en gegevens in IChartData::get_Categories gebruikt voor primaire series. Schrijf bool."
type: docs
weight: 66
url: /nl/aspose.slides.charts/ichartdata/set_usesecondarycategories/
---
## IChartData::set_UseSecondaryCategories(bool) methode

Als ingesteld op false, dan retourneert [IChartData::get_SecondaryCategories](../get_secondarycategories/) null en worden gegevens in [IChartData::get_Categories](../get_categories/) zowel voor primaire als secundaire series gebruikt. Als ingesteld op true, dan worden gegevens in [IChartData::get_SecondaryCategories](../get_secondarycategories/) gebruikt voor secundaire series en gegevens in [IChartData::get_Categories](../get_categories/) gebruikt voor primaire series. Schrijf **bool**.

```cpp
virtual void Aspose::Slides::Charts::IChartData::set_UseSecondaryCategories(bool value)=0
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