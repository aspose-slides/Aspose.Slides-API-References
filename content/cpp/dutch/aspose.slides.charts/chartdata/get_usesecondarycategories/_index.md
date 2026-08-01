---
title: get_UseSecondaryCategories()
second_title: Aspose.Slides voor C++ API-referentie
description: "Als ingesteld op false dan ChartData::get_SecondaryCategories null retourneert en gegevens in ChartData::get_Categories zowel voor primaire als secundaire series gebruikt. Als ingesteld op true dan gegevens in ChartData::get_SecondaryCategories voor secundaire series gebruikt en gegevens in ChartData::get_Categories voor primaire series gebruikt. Lees bool."
type: docs
weight: 53
url: /nl/aspose.slides.charts/chartdata/get_usesecondarycategories/
---
## ChartData::get_UseSecondaryCategories() methode

Als ingesteld op false dan [ChartData::get_SecondaryCategories](../get_secondarycategories/) retourneert null en worden gegevens in [ChartData::get_Categories](../get_categories/) zowel voor primaire als secundaire series gebruikt. Als ingesteld op true dan worden gegevens in [ChartData::get_SecondaryCategories](../get_secondarycategories/) voor secundaire series gebruikt en worden gegevens in [ChartData::get_Categories](../get_categories/) voor primaire series gebruikt. Lees **bool**.

```cpp
bool Aspose::Slides::Charts::ChartData::get_UseSecondaryCategories() override
```

## Opmerkingen

Voorbeeld. Welke categorieën zijn gerelateerd aan series - [ChartData::get_Categories](../get_categories/) of [ChartData::get_SecondaryCategories](../get_secondarycategories/)?
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

* Klasse [ChartData](../)
* Naamruimte [Aspose::Slides::Charts](../../)
* Bibliotheek [Aspose.Slides](../../../)