---
title: get_Categories()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: "Získá primární kategorie (nebo jak primární, tak sekundární kategorie, pokud je IChartData::set_UseSecondaryCategories nastaven na false). Pouze pro čtení IChartCategoryCollection."
type: docs
weight: 40
url: /cs/aspose.slides.charts/ichartdata/get_categories/
---
## IChartData::get_Categories() metoda


Získá primární kategorie (nebo jak primární, tak sekundární kategorie, pokud je [IChartData::set_UseSecondaryCategories](../set_usesecondarycategories/) nastaven na false). Pouze pro čtení [IChartCategoryCollection](../../ichartcategorycollection/).

```cpp
virtual System::SharedPtr<IChartCategoryCollection> Aspose::Slides::Charts::IChartData::get_Categories()=0
```

## Poznámky


Pokud je [IChartData::set_UseSecondaryCategories](../set_usesecondarycategories/) nastaven na false, pak [IChartData::get_SecondaryCategories](../get_secondarycategories/) vrací null a data v [IChartData::get_Categories](./) jsou použita jak pro primární, tak pro sekundární řady. Pokud je [IChartData::set_UseSecondaryCategories](../set_usesecondarycategories/) nastaven na true, pak data v [IChartData::get_SecondaryCategories](../get_secondarycategories/) jsou použita pro sekundární řady a data v [IChartData::get_Categories](./) jsou použita pro primární řady. 

Příklad. Které kategorie jsou spojeny s řadami – ChartData.Categories nebo ChartData.SecondaryCategories? 
```cpp
if (series->get_PlotOnSecondAxis() && series->get_Chart()->get_ChartData()->get_UseSecondaryCategories())
{
    // related categories are series->get_Chart()->get_ChartData()->get_SecondaryCategories()
}
else
{
    // related categories are series->get_Chart()->get_ChartData()->get_Categories()
}
```

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [IChartCategoryCollection](../../ichartcategorycollection/)
* Třída [IChartData](../)
* Jmenný prostor [Aspose::Slides::Charts](../../)
* Knihovna [Aspose.Slides](../../../)