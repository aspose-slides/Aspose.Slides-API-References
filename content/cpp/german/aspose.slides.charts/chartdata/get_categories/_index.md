---
title: get_Categories()
second_title: Aspose.Slides für C++ API-Referenz
description: "Ruft die primären Kategorien ab (oder sowohl primäre als auch sekundäre Kategorien, wenn ChartData::set_UseSecondaryCategories auf false gesetzt ist). Schreibgeschützt IChartCategoryCollection."
type: docs
weight: 40
url: /de/aspose.slides.charts/chartdata/get_categories/
---
## ChartData::get_Categories() Methode

Ruft die primären Kategorien ab (oder sowohl primäre als auch sekundäre Kategorien, wenn [ChartData::set_UseSecondaryCategories](../set_usesecondarycategories/) auf false gesetzt ist). Schreibgeschützt [IChartCategoryCollection](../../ichartcategorycollection/).

```cpp
System::SharedPtr<IChartCategoryCollection> Aspose::Slides::Charts::ChartData::get_Categories() override
```

## Anmerkungen

Wenn [ChartData::set_UseSecondaryCategories](../set_usesecondarycategories/) auf false gesetzt ist, gibt [ChartData::get_SecondaryCategories](../get_secondarycategories/) null zurück und die Daten in [ChartData::get_Categories](./) werden sowohl für primäre als auch für sekundäre Serien verwendet. Wenn [ChartData::set_UseSecondaryCategories](../set_usesecondarycategories/) auf true gesetzt ist, werden die Daten in [ChartData::get_SecondaryCategories](../get_secondarycategories/) für sekundäre Serien und die Daten in [ChartData::get_Categories](./) für primäre Serien verwendet. 

Beispiel. Welche Kategorien stehen in Beziehung zu Serien - [ChartData::get_Categories](./) oder [ChartData::get_SecondaryCategories](../get_secondarycategories/)? 
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
* Klasse [ChartData](../)
* Namensraum [Aspose::Slides::Charts](../../)
* Bibliothek [Aspose.Slides](../../../)