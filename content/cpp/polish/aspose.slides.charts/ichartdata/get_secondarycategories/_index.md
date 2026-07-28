---
title: get_SecondaryCategories()
second_title: Odwołanie API Aspose.Slides dla C++
description: "Pobiera drugorzędne kategorie, jeśli IChartData::get_UseSecondaryCategories ma wartość true. Tylko do odczytu IChartCategoryCollection."
type: docs
weight: 79
url: /pl/aspose.slides.charts/ichartdata/get_secondarycategories/
---
## IChartData::get_SecondaryCategories() metoda


Pobiera drugorzędne kategorie, jeśli [IChartData::get_UseSecondaryCategories](../get_usesecondarycategories/) ma wartość true. Tylko do odczytu [IChartCategoryCollection](../../ichartcategorycollection/).

```cpp
virtual System::SharedPtr<IChartCategoryCollection> Aspose::Slides::Charts::IChartData::get_SecondaryCategories()=0
```

## Uwagi


Jeśli [IChartData::set_UseSecondaryCategories](../set_usesecondarycategories/) ma ustawioną wartość false, wtedy [IChartData::get_SecondaryCategories](./) zwraca null i dane w [IChartData::get_Categories](../get_categories/) są używane zarówno dla serii podstawowych, jak i drugorzędnych. Jeśli [IChartData::set_UseSecondaryCategories](../set_usesecondarycategories/) ma ustawioną wartość true, wtedy dane w [IChartData::get_SecondaryCategories](./) są używane dla serii drugorzędnych, a dane w [IChartData::get_Categories](../get_categories/) są używane dla serii podstawowych. 

Przykład. Które kategorie są powiązane z seriami - ChartData.Categories czy ChartData.SecondaryCategories? 
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
* Klasa [IChartData](../)
* Przestrzeń nazw [Aspose::Slides::Charts](../../)
* Biblioteka [Aspose.Slides](../../../)