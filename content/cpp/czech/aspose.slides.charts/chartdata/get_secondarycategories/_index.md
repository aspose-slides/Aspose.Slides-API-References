---
title: get_SecondaryCategories()
second_title: Aspose.Slides pro C++ API Reference
description: "Získá sekundární kategorie, pokud je ChartData::get_UseSecondaryCategories true. Pouze ke čtení IChartCategoryCollection."
type: docs
weight: 79
url: /cs/aspose.slides.charts/chartdata/get_secondarycategories/
---
## ChartData::get_SecondaryCategories() metoda

Získá sekundární kategorie, pokud je [ChartData::get_UseSecondaryCategories](../get_usesecondarycategories/) true. Pouze ke čtení [IChartCategoryCollection](../../ichartcategorycollection/).

```cpp
System::SharedPtr<IChartCategoryCollection> Aspose::Slides::Charts::ChartData::get_SecondaryCategories() override
```

## Poznámky

Pokud je [ChartData::set_UseSecondaryCategories](../set_usesecondarycategories/) nastaveno na false, pak [ChartData::get_SecondaryCategories](./) vrátí null a data v [ChartData::get_Categories](../get_categories/) jsou použita jak pro primární, tak pro sekundární řady. Pokud je [ChartData::set_UseSecondaryCategories](../set_usesecondarycategories/) nastaveno na true, pak data v [ChartData::get_SecondaryCategories](./) jsou použita pro sekundární řady a data v [ChartData::get_Categories](../get_categories/) jsou použita pro primární řady. 

Příklad. Jaké kategorie jsou spojeny se sérií - [ChartData::get_Categories](../get_categories/) nebo [ChartData::get_SecondaryCategories](./)? 
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

* Typedef [SharedPtr](../../../system/sharedptr/)
* třída [IChartCategoryCollection](../../ichartcategorycollection/)
* třída [ChartData](../)
* jmenný prostor [Aspose::Slides::Charts](../../)
* knihovna [Aspose.Slides](../../../)