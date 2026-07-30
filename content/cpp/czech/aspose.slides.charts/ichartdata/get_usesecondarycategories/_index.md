---
title: get_UseSecondaryCategories()
second_title: Aspose.Slides pro C++ – reference API
description: "Pokud je nastaveno na false, pak IChartData::get_SecondaryCategories vrací null a data v IChartData::get_Categories jsou použita jak pro primární, tak pro sekundární řady. Pokud je nastaveno na true, pak data v IChartData::get_SecondaryCategories jsou použita pro sekundární řady a data v IChartData::get_Categories jsou použita pro primární řady. Čte se **bool**."
type: docs
weight: 53
url: /cs/aspose.slides.charts/ichartdata/get_usesecondarycategories/
---
## IChartData::get_UseSecondaryCategories() metoda


Pokud je nastaveno na false, pak [IChartData::get_SecondaryCategories](../get_secondarycategories/) vrací null a data v [IChartData::get_Categories](../get_categories/) jsou použita jak pro primární, tak pro sekundární řady. Pokud je nastaveno na true, pak data v [IChartData::get_SecondaryCategories](../get_secondarycategories/) jsou použita pro sekundární řady a data v [IChartData::get_Categories](../get_categories/) jsou použita pro primární řady. Vrací **bool**.

```cpp
virtual bool Aspose::Slides::Charts::IChartData::get_UseSecondaryCategories()=0
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