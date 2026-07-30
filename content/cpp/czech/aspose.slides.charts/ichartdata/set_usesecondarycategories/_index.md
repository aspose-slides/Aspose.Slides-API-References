---
title: set_UseSecondaryCategories()
second_title: Aspose.Slides pro C++ - referenční příručka API
description: "Pokud je nastaveno na false, pak IChartData::get_SecondaryCategories vrací null a data v IChartData::get_Categories jsou používána jak pro primární, tak pro sekundární řady. Pokud je nastaveno na true, pak data v IChartData::get_SecondaryCategories jsou používána pro sekundární řady a data v IChartData::get_Categories jsou používána pro primární řady. Zapište bool."
type: docs
weight: 66
url: /cs/aspose.slides.charts/ichartdata/set_usesecondarycategories/
---
## IChartData::set_UseSecondaryCategories(bool) metoda

Pokud je nastaveno na false, pak [IChartData::get_SecondaryCategories](../get_secondarycategories/) vrací null a data v [IChartData::get_Categories](../get_categories/) jsou používána jak pro primární, tak pro sekundární řady. Pokud je nastaveno na true, pak data v [IChartData::get_SecondaryCategories](../get_secondarycategories/) jsou používána pro sekundární řady a data v [IChartData::get_Categories](../get_categories/) jsou používána pro primární řady. Zapište **bool**.

```cpp
virtual void Aspose::Slides::Charts::IChartData::set_UseSecondaryCategories(bool value)=0
```

## Poznámky

Příklad. K jakým kategoriím jsou řady přiřazeny - ChartData.Categories nebo ChartData.SecondaryCategories?
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

* Třída [IChartData](../)
* Jmenný prostor [Aspose::Slides::Charts](../../)
* Knihovna [Aspose.Slides](../../../)