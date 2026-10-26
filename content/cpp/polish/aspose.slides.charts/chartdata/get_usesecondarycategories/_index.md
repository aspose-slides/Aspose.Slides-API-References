---
title: get_UseSecondaryCategories()
second_title: Aspose.Slides dla C++ – referencja API
description: "Jeśli ustawiono na false, wtedy ChartData::get_SecondaryCategories zwraca null i dane w ChartData::get_Categories są używane zarówno dla serii głównej, jak i dodatkowej. Jeśli ustawiono na true, wtedy dane w ChartData::get_SecondaryCategories są używane dla serii dodatkowej, a dane w ChartData::get_Categories są używane dla serii głównej. Odczytaj bool."
type: docs
weight: 53
url: /pl/aspose.slides.charts/chartdata/get_usesecondarycategories/
---
## ChartData::get_UseSecondaryCategories() metoda


Jeśli ustawiono na false, wtedy [ChartData::get_SecondaryCategories](../get_secondarycategories/) zwraca null i dane w [ChartData::get_Categories](../get_categories/) są używane zarówno dla serii głównej, jak i dodatkowej. Jeśli ustawiono na true, wtedy dane w [ChartData::get_SecondaryCategories](../get_secondarycategories/) są używane dla serii dodatkowej, a dane w [ChartData::get_Categories](../get_categories/) są używane dla serii głównej. Odczytaj **bool**.

```cpp
bool Aspose::Slides::Charts::ChartData::get_UseSecondaryCategories() override
```

## Uwagi


Przykład. Które kategorie są powiązane z seriami - [ChartData::get_Categories](../get_categories/) lub [ChartData::get_SecondaryCategories](../get_secondarycategories/)? 
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