---
title: get_Categories()
second_title: Aspose.Slides für C++ API Referenz
description: "Ruft die primären Kategorien ab (oder sowohl primäre als auch sekundäre Kategorien, wenn IChartData::set_UseSecondaryCategories auf false gesetzt ist). Nur lesbar IChartCategoryCollection."
type: docs
weight: 40
url: /de/aspose.slides.charts/ichartdata/get_categories/
---
## IChartData::get_Categories() Methode

Ruft die primären Kategorien ab (oder sowohl primäre als auch sekundäre Kategorien, wenn [IChartData::set_UseSecondaryCategories](../set_usesecondarycategories/) auf false gesetzt ist). Nur lesbar [IChartCategoryCollection](../../ichartcategorycollection/).

```cpp
virtual System::SharedPtr<IChartCategoryCollection> Aspose::Slides::Charts::IChartData::get_Categories()=0
```

## Hinweise

Wenn [IChartData::set_UseSecondaryCategories](../set_usesecondarycategories/) auf false gesetzt ist, gibt [IChartData::get_SecondaryCategories](../get_secondarycategories/) null zurück und die Daten in [IChartData::get_Categories](./) werden sowohl für primäre als auch für sekundäre Serien verwendet. Wenn [IChartData::set_UseSecondaryCategories](../set_usesecondarycategories/) auf true gesetzt ist, werden die Daten in [IChartData::get_SecondaryCategories](../get_secondarycategories/) für sekundäre Serien und die Daten in [IChartData::get_Categories](./) für primäre Serien verwendet.

Beispiel. Welche Kategorien sind mit Serien verknüpft – ChartData.Categories oder ChartData.SecondaryCategories?
```cpp
if (series->get_PlotOnSecondAxis() && series->get_Chart()->get_ChartData()->get_UseSecondaryCategories())
{
    // related categories are series->get_Chart()->get_ChartData()->get_SecondaryCategories()
}
else
{
    // related categories are series->get_Chart()->get_ChartData()->get_Categories()
}
```

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IChartCategoryCollection](../../ichartcategorycollection/)
* Klasse [IChartData](../)
* Namensraum [Aspose::Slides::Charts](../../)
* Bibliothek [Aspose.Slides](../../../)