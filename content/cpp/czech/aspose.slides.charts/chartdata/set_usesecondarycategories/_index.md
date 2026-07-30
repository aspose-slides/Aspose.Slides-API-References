---
title: set_UseSecondaryCategories()
second_title: Aspose.Slides pro C++ - referenční dokumentace API
description: "Pokud je nastaveno na false, pak ChartData::get_SecondaryCategories vrátí null a data v ChartData::get_Categories jsou použita jak pro primární, tak pro sekundární řady. Pokud je nastaveno na true, pak data v ChartData::get_SecondaryCategories jsou použita pro sekundární řady a data v ChartData::get_Categories jsou použita pro primární řady. Zapište bool."
type: docs
weight: 66
url: /cs/aspose.slides.charts/chartdata/set_usesecondarycategories/
---
## ChartData::set_UseSecondaryCategories(bool) metoda


Pokud je nastaveno na false, pak [ChartData::get_SecondaryCategories](../get_secondarycategories/) vrátí null a data v [ChartData::get_Categories](../get_categories/) jsou použita jak pro primární, tak pro sekundární řady. Pokud je nastaveno na true, pak data v [ChartData::get_SecondaryCategories](../get_secondarycategories/) jsou použita pro sekundární řady a data v [ChartData::get_Categories](../get_categories/) jsou použita pro primární řady. Zapište **bool**.

```cpp
void Aspose::Slides::Charts::ChartData::set_UseSecondaryCategories(bool value) override
```

## Poznámky


Příklad. K jakým kategoriím patří řady – [ChartData::get_Categories](../get_categories/) nebo [ChartData::get_SecondaryCategories](../get_secondarycategories/)?

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