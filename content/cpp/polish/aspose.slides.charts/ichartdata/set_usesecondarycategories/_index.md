---
title: set_UseSecondaryCategories()
second_title: Aspose.Slides for C++ - odniesienie do API
description: "Jeśli ustawiono na false, wtedy IChartData::get_SecondaryCategories zwraca null i dane w IChartData::get_Categories są używane zarówno dla serii pierwszorzędnych, jak i drugorzędnych. Jeśli ustawiono na true, wtedy dane w IChartData::get_SecondaryCategories są używane dla serii drugorzędnych, a dane w IChartData::get_Categories są używane dla serii pierwszorzędnych. Zapisz bool."
type: docs
weight: 66
url: /pl/aspose.slides.charts/ichartdata/set_usesecondarycategories/
---
## IChartData::set_UseSecondaryCategories(bool) metoda

Jeśli ustawiono na false, to [IChartData::get_SecondaryCategories](../get_secondarycategories/) zwraca null i dane w [IChartData::get_Categories](../get_categories/) są używane zarówno dla serii pierwszorzędnych, jak i drugorzędnych. Jeśli ustawiono na true, to dane w [IChartData::get_SecondaryCategories](../get_secondarycategories/) są używane dla serii drugorzędnych, a dane w [IChartData::get_Categories](../get_categories/) są używane dla serii pierwszorzędnych. Zapisz **bool**.

```cpp
virtual void Aspose::Slides::Charts::IChartData::set_UseSecondaryCategories(bool value)=0
```

## Uwagi

Przykład. Jakie kategorie są powiązane z seriami - ChartData.Categories lub ChartData.SecondaryCategories?
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

* Klasa [IChartData](../)
* Przestrzeń nazw [Aspose::Slides::Charts](../../)
* Biblioteka [Aspose.Slides](../../../)