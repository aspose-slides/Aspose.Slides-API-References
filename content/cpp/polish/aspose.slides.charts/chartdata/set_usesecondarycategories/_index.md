---
title: set_UseSecondaryCategories()
second_title: Aspose.Slides dla C++ - Dokumentacja API
description: "Jeśli ustawiono na false, ChartData::get_SecondaryCategories zwraca null i dane w ChartData::get_Categories są używane zarówno dla serii głównej, jak i drugorzędnej. Jeśli ustawiono na true, dane w ChartData::get_SecondaryCategories są używane dla serii drugorzędnej, a dane w ChartData::get_Categories są używane dla serii głównej. Zapisz bool."
type: docs
weight: 66
url: /pl/aspose.slides.charts/chartdata/set_usesecondarycategories/
---
## ChartData::set_UseSecondaryCategories(bool) method


Jeśli ustawiono na false, [ChartData::get_SecondaryCategories](../get_secondarycategories/) zwraca null i dane w [ChartData::get_Categories](../get_categories/) są używane zarówno dla serii głównej, jak i drugorzędnej. Jeśli ustawiono na true, dane w [ChartData::get_SecondaryCategories](../get_secondarycategories/) są używane dla serii drugorzędnej, a dane w [ChartData::get_Categories](../get_categories/) są używane dla serii głównej. Zapisz **bool**.

```cpp
void Aspose::Slides::Charts::ChartData::set_UseSecondaryCategories(bool value) override
```

## Uwagi


Przykład. Które kategorie są powiązane z serią - [ChartData::get_Categories](../get_categories/) lub [ChartData::get_SecondaryCategories](../get_secondarycategories/)? 
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

* Klasa [ChartData](../)
* Przestrzeń nazw [Aspose::Slides::Charts](../../)
* Biblioteka [Aspose.Slides](../../../)