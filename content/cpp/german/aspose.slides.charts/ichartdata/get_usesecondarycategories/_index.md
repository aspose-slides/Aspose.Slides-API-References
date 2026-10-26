---
title: get_UseSecondaryCategories()
second_title: Aspose.Slides für C++ API-Referenz
description: "Wenn auf false gesetzt, gibt IChartData::get_SecondaryCategories null zurück und Daten in IChartData::get_Categories werden sowohl für primäre als auch für sekundäre Serien verwendet. Wenn auf true gesetzt, werden Daten in IChartData::get_SecondaryCategories für sekundäre Serien und Daten in IChartData::get_Categories für primäre Serien verwendet. Lese bool."
type: docs
weight: 53
url: /de/aspose.slides.charts/ichartdata/get_usesecondarycategories/
---
## IChartData::get_UseSecondaryCategories() Methode


Wenn auf false gesetzt, gibt [IChartData::get_SecondaryCategories](../get_secondarycategories/) null zurück und Daten in [IChartData::get_Categories](../get_categories/) werden sowohl für primäre als auch für sekundäre Serien verwendet. Wenn auf true gesetzt, werden Daten in [IChartData::get_SecondaryCategories](../get_secondarycategories/) für sekundäre Serien und Daten in [IChartData::get_Categories](../get_categories/) für primäre Serien verwendet. Lese **bool**.

```cpp
virtual bool Aspose::Slides::Charts::IChartData::get_UseSecondaryCategories()=0
```

## Anmerkungen


Beispiel. Welche Kategorien sind mit Serien verbunden – ChartData.Categories oder ChartData.SecondaryCategories? 
```cpp
if (series->get_PlotOnSecondAxis() && series->get_Chart()->get_ChartData()->get_UseSecondaryCategories())
{
    // zugehörige Kategorien sind series->get_Chart()->get_ChartData()->get_SecondaryCategories()
}
else
{
    // zugehörige Kategorien sind series->get_Chart()->get_ChartData()->get_Categories()
}
```

## Siehe auch

* Klasse [IChartData](../)
* Namensraum [Aspose::Slides::Charts](../../)
* Bibliothek [Aspose.Slides](../../../)