---
title: get_Categories()
second_title: Aspose.Slides for C++ – Dokumentacja API
description: "Pobiera podstawowe kategorie (lub zarówno podstawowe, jak i drugorzędne kategorie, jeśli ChartData::set_UseSecondaryCategories jest ustawione na false). Tylko do odczytu IChartCategoryCollection."
type: docs
weight: 40
url: /pl/aspose.slides.charts/chartdata/get_categories/
---
## ChartData::get_Categories() metoda

Pobiera podstawowe kategorie (lub zarówno podstawowe, jak i drugorzędne kategorie, jeśli [ChartData::set_UseSecondaryCategories](../set_usesecondarycategories/) jest ustawione na false). Tylko do odczytu [IChartCategoryCollection](../../ichartcategorycollection/).

```cpp
System::SharedPtr<IChartCategoryCollection> Aspose::Slides::Charts::ChartData::get_Categories() override
```

## Uwagi

Jeśli [ChartData::set_UseSecondaryCategories](../set_usesecondarycategories/) jest ustawione na false, to [ChartData::get_SecondaryCategories](../get_secondarycategories/) zwraca null i dane w [ChartData::get_Categories](./) są używane zarówno dla serii podstawowych, jak i drugorzędnych. Jeśli [ChartData::set_UseSecondaryCategories](../set_usesecondarycategories/) jest ustawione na true, to dane w [ChartData::get_SecondaryCategories](../get_secondarycategories/) są używane dla serii drugorzędnych, a dane w [ChartData::get_Categories](./) są używane dla serii podstawowych. 

Przykład. Jakie kategorie są powiązane z serią - [ChartData::get_Categories](./) lub [ChartData::get_SecondaryCategories](../get_secondarycategories/)? 
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

## Zobacz też

* Definicja typu [SharedPtr](../../../system/sharedptr/)
* Klasa [IChartCategoryCollection](../../ichartcategorycollection/)
* Klasa [ChartData](../)
* Przestrzeń nazw [Aspose::Slides::Charts](../../)
* Biblioteka [Aspose.Slides](../../../)