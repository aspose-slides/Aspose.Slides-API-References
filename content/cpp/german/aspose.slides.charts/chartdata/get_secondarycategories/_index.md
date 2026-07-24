---
title: get_SecondaryCategories()
second_title: Aspose.Slides für C++ API-Referenz
description: "Ermittelt die sekundären Kategorien, wenn ChartData::get_UseSecondaryCategories true ist. Schreibgeschützt IChartCategoryCollection."
type: docs
weight: 79
url: /de/aspose.slides.charts/chartdata/get_secondarycategories/
---
## ChartData::get_SecondaryCategories() Methode

Ermittelt die sekundären Kategorien, wenn [ChartData::get_UseSecondaryCategories](../get_usesecondarycategories/) true ist. Schreibgeschützt [IChartCategoryCollection](../../ichartcategorycollection/).

```cpp
System::SharedPtr<IChartCategoryCollection> Aspose::Slides::Charts::ChartData::get_SecondaryCategories() override
```

## Hinweise

Wenn [ChartData::set_UseSecondaryCategories](../set_usesecondarycategories/) auf false gesetzt ist, dann gibt [ChartData::get_SecondaryCategories](./) null zurück und Daten in [ChartData::get_Categories](../get_categories/) werden sowohl für primäre als auch für sekundäre Serien verwendet. Wenn [ChartData::set_UseSecondaryCategories](../set_usesecondarycategories/) auf true gesetzt ist, dann werden Daten in [ChartData::get_SecondaryCategories](./) für sekundäre Serien und Daten in [ChartData::get_Categories](../get_categories/) für primäre Serien verwendet.

Beispiel. Welche Kategorien stehen in Beziehung zu Serien - [ChartData::get_Categories](../get_categories/) oder [ChartData::get_SecondaryCategories](./)?
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

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IChartCategoryCollection](../../ichartcategorycollection/)
* Class [ChartData](../)
* Namespace [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)