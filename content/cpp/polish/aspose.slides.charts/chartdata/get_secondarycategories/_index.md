---
title: get_SecondaryCategories()
second_title: Aspose.Slides dla C++ – odniesienie API
description: "Pobiera drugorzędne kategorie, jeśli ChartData::get_UseSecondaryCategories jest prawdziwe. Tylko do odczytu IChartCategoryCollection."
type: docs
weight: 79
url: /pl/aspose.slides.charts/chartdata/get_secondarycategories/
---
## ChartData::get_SecondaryCategories() metoda

Pobiera drugorzędne kategorie, jeśli [ChartData::get_UseSecondaryCategories](../get_usesecondarycategories/) jest prawdziwe. Tylko do odczytu [IChartCategoryCollection](../../ichartcategorycollection/).

```cpp
System::SharedPtr<IChartCategoryCollection> Aspose::Slides::Charts::ChartData::get_SecondaryCategories() override
```

## Uwagi

Jeśli [ChartData::set_UseSecondaryCategories](../set_usesecondarycategories/) jest ustawione na false, wtedy [ChartData::get_SecondaryCategories](./) zwraca null i dane w [ChartData::get_Categories](../get_categories/) są używane zarówno dla serii podstawowych, jak i drugorzędnych. Jeśli [ChartData::set_UseSecondaryCategories](../set_usesecondarycategories/) jest ustawione na true, wtedy dane w [ChartData::get_SecondaryCategories](./) są używane dla serii drugorzędnych, a dane w [ChartData::get_Categories](../get_categories/) są używane dla serii podstawowych.

Przykład. Jakie kategorie są powiązane z serią - [ChartData::get_Categories](../get_categories/) lub [ChartData::get_SecondaryCategories](./)?
```cpp
if (series->get_PlotOnSecondAxis() && series->get_Chart()->get_ChartData()->get_UseSecondaryCategories())
{
    // powiązane kategorie są series->get_Chart()->get_ChartData()->get_SecondaryCategories()
}
else
{
    // powiązane kategorie są series->get_Chart()->get_ChartData()->get_Categories()
}
```

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [IChartCategoryCollection](../../ichartcategorycollection/)
* Klasa [ChartData](../)
* Przestrzeń nazw [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)