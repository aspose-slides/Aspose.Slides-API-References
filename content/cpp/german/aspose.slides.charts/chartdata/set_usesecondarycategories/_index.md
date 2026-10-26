---
title: set_UseSecondaryCategories()
second_title: Aspose.Slides für C++ API-Referenz
description: "Wenn false gesetzt, gibt ChartData::get_SecondaryCategories null zurück und die Daten in ChartData::get_Categories werden sowohl für primäre als auch für sekundäre Serien verwendet. Wenn true gesetzt, werden die Daten in ChartData::get_SecondaryCategories für sekundäre Serien und die Daten in ChartData::get_Categories für primäre Serien verwendet. Schreiben Sie bool."
type: docs
weight: 66
url: /de/aspose.slides.charts/chartdata/set_usesecondarycategories/
---
## ChartData::set_UseSecondaryCategories(bool) Methode

If set to false then [ChartData::get_SecondaryCategories](../get_secondarycategories/) returns null and data in [ChartData::get_Categories](../get_categories/) is used both for primary and secondary series. If set to true then data in [ChartData::get_SecondaryCategories](../get_secondarycategories/) is used for secondary series and data in [ChartData::get_Categories](../get_categories/) is used for primary series. Write **bool**.

```cpp
void Aspose::Slides::Charts::ChartData::set_UseSecondaryCategories(bool value) override
```

## Bemerkungen

Example. What categories are related to series - [ChartData::get_Categories](../get_categories/) or [ChartData::get_SecondaryCategories](../get_secondarycategories/)? 
```cpp
if (series->get_PlotOnSecondAxis() && series->get_Chart()->get_ChartData()->get_UseSecondaryCategories())
{
    // Zugehörige Kategorien sind series->get_Chart()->get_ChartData()->get_SecondaryCategories()
}
else
{
    // Zugehörige Kategorien sind series->get_Chart()->get_ChartData()->get_Categories()
}
```

## Siehe auch

* Klasse [ChartData](../)
* Namensraum [Aspose::Slides::Charts](../../)
* Bibliothek [Aspose.Slides](../../../)