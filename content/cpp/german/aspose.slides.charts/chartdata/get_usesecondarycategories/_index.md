---
title: get_UseSecondaryCategories()
second_title: Aspose.Slides für C++ API-Referenz
description: "Wenn auf false gesetzt, gibt ChartData::get_SecondaryCategories null zurück und die Daten in ChartData::get_Categories werden sowohl für primäre als auch für sekundäre Serien verwendet. Wenn auf true gesetzt, werden die Daten in ChartData::get_SecondaryCategories für sekundäre Serien und die Daten in ChartData::get_Categories für primäre Serien verwendet. Lesen bool."
type: docs
weight: 53
url: /de/aspose.slides.charts/chartdata/get_usesecondarycategories/
---
## ChartData::get_UseSecondaryCategories() Methode


Wenn auf false gesetzt, dann gibt [ChartData::get_SecondaryCategories](../get_secondarycategories/) null zurück und die Daten in [ChartData::get_Categories](../get_categories/) werden sowohl für primäre als auch für sekundäre Serien verwendet. Wenn auf true gesetzt, dann werden die Daten in [ChartData::get_SecondaryCategories](../get_secondarycategories/) für sekundäre Serien und die Daten in [ChartData::get_Categories](../get_categories/) für primäre Serien verwendet. Lesen **bool**.

```cpp
bool Aspose::Slides::Charts::ChartData::get_UseSecondaryCategories() override
```

## Hinweise


Beispiel. Welche Kategorien sind mit Serien verbunden - [ChartData::get_Categories](../get_categories/) oder [ChartData::get_SecondaryCategories](../get_secondarycategories/)? 
```cpp
if (series->get_PlotOnSecondAxis() && series->get_Chart()->get_ChartData()->get_UseSecondaryCategories())
{
    // verwandte Kategorien sind series->get_Chart()->get_ChartData()->get_SecondaryCategories()
}
else
{
    // verwandte Kategorien sind series->get_Chart()->get_ChartData()->get_Categories()
}
```

## Siehe auch

* Klasse [ChartData](../)
* Namensraum [Aspose::Slides::Charts](../../)
* Bibliothek [Aspose.Slides](../../../)