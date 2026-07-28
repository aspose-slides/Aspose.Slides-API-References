---
title: get_Categories()
second_title: Aspose.Slides dla C++ - Dokumentacja API
description: "Pobiera główne kategorie (lub zarówno główne, jak i podrzędne kategorie, jeśli IChartData::set_UseSecondaryCategories jest ustawione na false). Tylko do odczytu IChartCategoryCollection."
type: docs
weight: 40
url: /pl/aspose.slides.charts/ichartdata/get_categories/
---
## IChartData::get_Categories() metoda

Pobiera główne kategorie (lub zarówno główne, jak i podrzędne kategorie, jeśli [IChartData::set_UseSecondaryCategories](../set_usesecondarycategories/) jest ustawione na false). Tylko do odczytu [IChartCategoryCollection](../../ichartcategorycollection/).

```cpp
virtual System::SharedPtr<IChartCategoryCollection> Aspose::Slides::Charts::IChartData::get_Categories()=0
```

## Uwagi

Jeśli [IChartData::set_UseSecondaryCategories](../set_usesecondarycategories/) jest ustawione na false, wtedy [IChartData::get_SecondaryCategories](../get_secondarycategories/) zwraca null i dane w [IChartData::get_Categories](./) są używane zarówno dla serii głównych, jak i podrzędnych. Jeśli [IChartData::set_UseSecondaryCategories](../set_usesecondarycategories/) jest ustawione na true, wtedy dane w [IChartData::get_SecondaryCategories](../get_secondarycategories/) są używane dla serii podrzędnych, a dane w [IChartData::get_Categories](./) są używane dla serii głównych.

Przykład. Jakie kategorie są powiązane z serią — ChartData.Categories lub ChartData.SecondaryCategories?
```cpp
if (series->get_PlotOnSecondAxis() && series->get_Chart()->get_ChartData()->get_UseSecondaryCategories())
{
 // powiązane kategorie to series->get_Chart()->get_ChartData()->get_SecondaryCategories()
}
else
{
 // powiązane kategorie to series->get_Chart()->get_ChartData()->get_Categories()
}
```

## Zobacz także

* Definicja typu [SharedPtr](../../../system/sharedptr/)
* Klasa [IChartCategoryCollection](../../ichartcategorycollection/)
* Klasa [IChartData](../)
* Przestrzeń nazw [Aspose::Slides::Charts](../../)
* Biblioteka [Aspose.Slides](../../../)