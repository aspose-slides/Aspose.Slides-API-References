---
title: get_UseSecondaryCategories()
second_title: Aspose.Slides pro C++ API Reference
description: "Pokud je nastaveno na false, pak ChartData::get_SecondaryCategories vrací null a data v ChartData::get_Categories jsou používána jak pro primární, tak pro sekundární řady. Pokud je nastaveno na true, pak data v ChartData::get_SecondaryCategories jsou používána pro sekundární řady a data v ChartData::get_Categories jsou používána pro primární řady. Vrací bool."
type: docs
weight: 53
url: /cs/aspose.slides.charts/chartdata/get_usesecondarycategories/
---
## ChartData::get_UseSecondaryCategories() metoda


Pokud je nastaveno na false, pak [ChartData::get_SecondaryCategories](../get_secondarycategories/) vrací null a data v [ChartData::get_Categories](../get_categories/) jsou používána jak pro primární, tak pro sekundární řady. Pokud je nastaveno na true, pak data v [ChartData::get_SecondaryCategories](../get_secondarycategories/) jsou používána pro sekundární řady a data v [ChartData::get_Categories](../get_categories/) jsou používána pro primární řady. Vrací **bool**.

```cpp
bool Aspose::Slides::Charts::ChartData::get_UseSecondaryCategories() override
```

## Poznámky


Příklad. Které kategorie jsou přiřazeny k řadě - [ChartData::get_Categories](../get_categories/) nebo [ChartData::get_SecondaryCategories](../get_secondarycategories/)? 
```cpp
if (series->get_PlotOnSecondAxis() && series->get_Chart()->get_ChartData()->get_UseSecondaryCategories())
{
    // související kategorie jsou series->get_Chart()->get_ChartData()->get_SecondaryCategories()
}
else
{
    // související kategorie jsou series->get_Chart()->get_ChartData()->get_Categories()
}
```

## Viz také

* Třída [ChartData](../)
* Jmenný prostor [Aspose::Slides::Charts](../../)
* Knihovna [Aspose.Slides](../../../)