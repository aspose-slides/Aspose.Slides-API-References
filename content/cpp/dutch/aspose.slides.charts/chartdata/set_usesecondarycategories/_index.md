---
title: set_UseSecondaryCategories()
second_title: Aspose.Slides voor C++ API-referentie
description: "Als ingesteld op false dan retourneert ChartData::get_SecondaryCategories null en gegevens in ChartData::get_Categories worden zowel voor primaire als secundaire reeksen gebruikt. Als ingesteld op true dan worden gegevens in ChartData::get_SecondaryCategories gebruikt voor secundaire reeksen en gegevens in ChartData::get_Categories gebruikt voor primaire reeksen. Schrijf bool."
type: docs
weight: 66
url: /nl/aspose.slides.charts/chartdata/set_usesecondarycategories/
---
## ChartData::set_UseSecondaryCategories(bool) methode

Als ingesteld op false dan retourneert [ChartData::get_SecondaryCategories](../get_secondarycategories/) null en worden gegevens in [ChartData::get_Categories](../get_categories/) gebruikt voor zowel primaire als secundaire reeksen. Als ingesteld op true dan worden gegevens in [ChartData::get_SecondaryCategories](../get_secondarycategories/) gebruikt voor secundaire reeksen en gegevens in [ChartData::get_Categories](../get_categories/) gebruikt voor primaire reeksen. Schrijf **bool**.

```cpp
void Aspose::Slides::Charts::ChartData::set_UseSecondaryCategories(bool value) override
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

## Zie Ook

* Klasse [ChartData](../)
* Naamruimte [Aspose::Slides::Charts](../../)
* Bibliotheek [Aspose.Slides](../../../)