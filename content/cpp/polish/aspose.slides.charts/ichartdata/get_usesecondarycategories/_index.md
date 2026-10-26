---
title: get_UseSecondaryCategories()
second_title: Aspose.Slides dla C++ – odniesienie API
description: "Jeśli ustawiono na false, wtedy IChartData::get_SecondaryCategories zwraca null i dane w IChartData::get_Categories są używane zarówno dla serii podstawowej, jak i wtórnej. Jeśli ustawiono na true, wtedy dane w IChartData::get_SecondaryCategories są używane dla serii wtórnej, a dane w IChartData::get_Categories są używane dla serii podstawowej. Odczytaj bool."
type: docs
weight: 53
url: /pl/aspose.slides.charts/ichartdata/get_usesecondarycategories/
---
## IChartData::get_UseSecondaryCategories() metoda


Jeśli ustawiono na false, to [IChartData::get_SecondaryCategories](../get_secondarycategories/) zwraca null i dane w [IChartData::get_Categories](../get_categories/) są używane zarówno dla serii podstawowej, jak i wtórnej. Jeśli ustawiono na true, to dane w [IChartData::get_SecondaryCategories](../get_secondarycategories/) są używane dla serii wtórnej, a dane w [IChartData::get_Categories](../get_categories/) są używane dla serii podstawowej. Odczytaj **bool**.

```cpp
virtual bool Aspose::Slides::Charts::IChartData::get_UseSecondaryCategories()=0
```

## Uwagi


Przykład. Które kategorie są powiązane z seriami - ChartData.Categories lub ChartData.SecondaryCategories? 
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