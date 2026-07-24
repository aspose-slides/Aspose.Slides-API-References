---
title: set_UseSecondaryCategories()
second_title: Aspose.Slides für C++ API-Referenz
description: "Wenn auf false gesetzt, gibt IChartData::get_SecondaryCategories null zurück und die Daten in IChartData::get_Categories werden sowohl für primäre als auch für sekundäre Serien verwendet. Wenn auf true gesetzt, werden die Daten in IChartData::get_SecondaryCategories für sekundäre Serien und die Daten in IChartData::get_Categories für primäre Serien verwendet. Schreiben Sie bool."
type: docs
weight: 66
url: /de/aspose.slides.charts/ichartdata/set_usesecondarycategories/
---
## IChartData::set_UseSecondaryCategories(bool) Methode

Wenn auf false gesetzt, dann gibt [IChartData::get_SecondaryCategories](../get_secondarycategories/) null zurück und die Daten in [IChartData::get_Categories](../get_categories/) werden sowohl für primäre als auch für sekundäre Serien verwendet. Wenn auf true gesetzt, werden die Daten in [IChartData::get_SecondaryCategories](../get_secondarycategories/) für sekundäre Serien und die Daten in [IChartData::get_Categories](../get_categories/) für primäre Serien verwendet. Schreiben Sie **bool**.

```cpp
virtual void Aspose::Slides::Charts::IChartData::set_UseSecondaryCategories(bool value)=0
```

## Anmerkungen

Beispiel. Welche Kategorien sind den Serien zugeordnet - ChartData.Categories oder ChartData.SecondaryCategories?

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

* Klasse [IChartData](../)
* Namensraum [Aspose::Slides::Charts](../../)
* Bibliothek [Aspose.Slides](../../../)