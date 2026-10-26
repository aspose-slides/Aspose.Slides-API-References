---
title: get_SecondaryCategories()
second_title: Aspose.Slides für C++ API-Referenz
description: "Liest die sekundären Kategorien, wenn IChartData::get_UseSecondaryCategories true ist. Schreibgeschützt IChartCategoryCollection."
type: docs
weight: 79
url: /de/aspose.slides.charts/ichartdata/get_secondarycategories/
---
## IChartData::get_SecondaryCategories() Methode

Liest die sekundären Kategorien, wenn [IChartData::get_UseSecondaryCategories](../get_usesecondarycategories/) true ist. Schreibgeschützt [IChartCategoryCollection](../../ichartcategorycollection/).

```cpp
virtual System::SharedPtr<IChartCategoryCollection> Aspose::Slides::Charts::IChartData::get_SecondaryCategories()=0
```

## Hinweise

Wenn [IChartData::set_UseSecondaryCategories](../set_usesecondarycategories/) auf false gesetzt ist, gibt [IChartData::get_SecondaryCategories](./) null zurück und die Daten in [IChartData::get_Categories](../get_categories/) werden sowohl für primäre als auch für sekundäre Serien verwendet. Wenn [IChartData::set_UseSecondaryCategories](../set_usesecondarycategories/) auf true gesetzt ist, werden die Daten in [IChartData::get_SecondaryCategories](./) für sekundäre Serien und die Daten in [IChartData::get_Categories](../get_categories/) für primäre Serien verwendet. 

Beispiel. Welche Kategorien sind mit Serien verknüpft – ChartData.Categories oder ChartData.SecondaryCategories? 
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

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IChartCategoryCollection](../../ichartcategorycollection/)
* Klasse [IChartData](../)
* Namensraum [Aspose::Slides::Charts](../../)
* Bibliothek [Aspose.Slides](../../../)