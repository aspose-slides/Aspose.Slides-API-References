---
title: get_UseSecondaryCategories()
second_title: Aspose.Slides C++ API hivatkozás
description: "Ha false-ra van állítva, akkor IChartData::get_SecondaryCategories null értéket ad vissza, és az IChartData::get_Categories adat mind elsődleges, mind másodlagos sorozathoz használható. Ha true-ra van állítva, akkor az IChartData::get_SecondaryCategories adat a másodlagos sorozathoz, az IChartData::get_Categories adat pedig az elsődleges sorozathoz használható. Olvasható bool."
type: docs
weight: 53
url: /hu/aspose.slides.charts/ichartdata/get_usesecondarycategories/
---
## IChartData::get_UseSecondaryCategories() metódus


Ha false-ra van állítva, akkor [IChartData::get_SecondaryCategories](../get_secondarycategories/) null értéket ad vissza, és a [IChartData::get_Categories](../get_categories/) adat mind az elsődleges, mind a másodlagos sorozathoz használható. Ha true-ra van állítva, akkor a [IChartData::get_SecondaryCategories](../get_secondarycategories/) adat a másodlagos sorozathoz, a [IChartData::get_Categories](../get_categories/) adat pedig az elsődleges sorozathoz használható. Olvasható **bool**.

```cpp
virtual bool Aspose::Slides::Charts::IChartData::get_UseSecondaryCategories()=0
```

## Megjegyzések


Példa. Mely kategóriák kapcsolódnak a sorozathoz – ChartData.Categories vagy ChartData.SecondaryCategories? 
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
* Névtér [Aspose::Slides::Charts](../../)
* Könyvtár [Aspose.Slides](../../../)