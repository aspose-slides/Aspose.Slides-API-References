---
title: get_Categories()
second_title: Aspose.Slides pro C++ API Reference
description: "Získá primární kategorie (nebo jak primární, tak sekundární kategorie, pokud je ChartData::set_UseSecondaryCategories nastaveno na false). Pouze pro čtení IChartCategoryCollection."
type: docs
weight: 40
url: /cs/aspose.slides.charts/chartdata/get_categories/
---
## ChartData::get_Categories() metoda


Získá primární kategorie (nebo jak primární, tak sekundární kategorie, pokud je [ChartData::set_UseSecondaryCategories](../set_usesecondarycategories/) nastaveno na false). Pouze pro čtení [IChartCategoryCollection](../../ichartcategorycollection/).

```cpp
System::SharedPtr<IChartCategoryCollection> Aspose::Slides::Charts::ChartData::get_Categories() override
```

## Poznámky


Pokud je [ChartData::set_UseSecondaryCategories](../set_usesecondarycategories/) nastaveno na false, pak [ChartData::get_SecondaryCategories](../get_secondarycategories/) vrací null a data v [ChartData::get_Categories](./) jsou použita jak pro primární, tak pro sekundární řady. Pokud je [ChartData::set_UseSecondaryCategories](../set_usesecondarycategories/) nastaveno na true, pak data v [ChartData::get_SecondaryCategories](../get_secondarycategories/) jsou použita pro sekundární řady a data v [ChartData::get_Categories](./) jsou použita pro primární řady. 

Příklad. K jakým kategoriím patří řady - [ChartData::get_Categories](./) nebo [ChartData::get_SecondaryCategories](../get_secondarycategories/)? 
```cpp
if (series->get_PlotOnSecondAxis() && series->get_Chart()->get_ChartData()->get_UseSecondaryCategories())
{
    // příslušné kategorie jsou series->get_Chart()->get_ChartData()->get_SecondaryCategories()
}
else
{
    // příslušné kategorie jsou series->get_Chart()->get_ChartData()->get_Categories()
}
```

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [IChartCategoryCollection](../../ichartcategorycollection/)
* Třída [ChartData](../)
* Obor názvů [Aspose::Slides::Charts](../../)
* Knihovna [Aspose.Slides](../../../)