---
title: get_SecondaryCategories()
second_title: Aspose.Slides pro C++ API referenci
description: "Získá sekundární kategorie, pokud je IChartData::get_UseSecondaryCategories pravda. Pouze pro čtení IChartCategoryCollection."
type: docs
weight: 79
url: /cs/aspose.slides.charts/ichartdata/get_secondarycategories/
---
## IChartData::get_SecondaryCategories() metoda


Získá sekundární kategorie, pokud je [IChartData::get_UseSecondaryCategories](../get_usesecondarycategories/) pravda. Pouze pro čtení [IChartCategoryCollection](../../ichartcategorycollection/).

```cpp
virtual System::SharedPtr<IChartCategoryCollection> Aspose::Slides::Charts::IChartData::get_SecondaryCategories()=0
```

## Poznámky


Pokud je [IChartData::set_UseSecondaryCategories](../set_usesecondarycategories/) nastaveno na false, pak [IChartData::get_SecondaryCategories](./) vrací null a data v [IChartData::get_Categories](../get_categories/) jsou použita jak pro primární, tak pro sekundární řady. Pokud je [IChartData::set_UseSecondaryCategories](../set_usesecondarycategories/) nastaveno na true, pak data v [IChartData::get_SecondaryCategories](./) jsou použita pro sekundární řady a data v [IChartData::get_Categories](../get_categories/) jsou použita pro primární řady. 

Příklad. K jakým kategoriím patří řady - ChartData.Categories nebo ChartData.SecondaryCategories? 
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
* Třída [IChartCategoryCollection](../../ichartcategorycollection/)
* Třída [IChartData](../)
* Obor názvů [Aspose::Slides::Charts](../../)
* Knihovna [Aspose.Slides](../../../)