---
title: set_UseSecondaryCategories()
second_title: Aspose.Slides C++ API referencia
description: "Ha false-ra van állítva, akkor IChartData::get_SecondaryCategories null értéket ad vissza, és az IChartData::get_Categories adatok mind az elsődleges, mind a másodlagos sorozatokhoz használatosak. Ha true-ra van állítva, akkor az IChartData::get_SecondaryCategories adatok a másodlagos sorozatokhoz, az IChartData::get_Categories adatok pedig az elsődleges sorozatokhoz kerülnek felhasználásra. Írja bool."
type: docs
weight: 66
url: /hu/aspose.slides.charts/ichartdata/set_usesecondarycategories/
---
## IChartData::set_UseSecondaryCategories(bool) metódus


Ha false-ra van állítva, akkor [IChartData::get_SecondaryCategories](../get_secondarycategories/) null értéket ad vissza, és a [IChartData::get_Categories](../get_categories/) adatok mind az elsődleges, mind a másodlagos sorozatokhoz használatosak. Ha true-ra van állítva, akkor a [IChartData::get_SecondaryCategories](../get_secondarycategories/) adatok a másodlagos sorozatokhoz, a [IChartData::get_Categories](../get_categories/) adatok pedig az elsődleges sorozatokhoz kerülnek felhasználásra. Írja **bool**.

```cpp
virtual void Aspose::Slides::Charts::IChartData::set_UseSecondaryCategories(bool value)=0
```

## Megjegyzések


Példa. Mely kategóriák kapcsolódnak a sorozatokhoz - ChartData.Categories vagy ChartData.SecondaryCategories? 
```cpp
if (series->get_PlotOnSecondAxis() && series->get_Chart()->get_ChartData()->get_UseSecondaryCategories())
{
    // a kapcsolódó kategóriák a series->get_Chart()->get_ChartData()->get_SecondaryCategories()
}
else
{
    // a kapcsolódó kategóriák a series->get_Chart()->get_ChartData()->get_Categories()
}
```

## Lásd még

* Osztály [IChartData](../)
* Névterület [Aspose::Slides::Charts](../../)
* Könyvtár [Aspose.Slides](../../../)