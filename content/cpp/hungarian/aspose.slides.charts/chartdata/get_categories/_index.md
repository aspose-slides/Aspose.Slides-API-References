---
title: get_Categories()
second_title: Aspose.Slides C++ API referencia
description: "Lekéri az elsődleges kategóriákat (vagy az elsődleges és a másodlagos kategóriákat is, ha a ChartData::set_UseSecondaryCategories false értékre van állítva). Csak olvasható IChartCategoryCollection."
type: docs
weight: 40
url: /hu/aspose.slides.charts/chartdata/get_categories/
---
## ChartData::get_Categories() metódus


Lekéri az elsődleges kategóriákat (vagy az elsődleges és a másodlagos kategóriákat is, ha a [ChartData::set_UseSecondaryCategories](../set_usesecondarycategories/) false-ra van állítva). Csak olvasható [IChartCategoryCollection](../../ichartcategorycollection/).

```cpp
System::SharedPtr<IChartCategoryCollection> Aspose::Slides::Charts::ChartData::get_Categories() override
```

## Megjegyzések


Ha a [ChartData::set_UseSecondaryCategories](../set_usesecondarycategories/) false értékre van állítva, akkor a [ChartData::get_SecondaryCategories](../get_secondarycategories/) null értéket ad vissza, és a [ChartData::get_Categories](./) adatot használja mind az elsődleges, mind a másodlagos sorozatokhoz. Ha a [ChartData::set_UseSecondaryCategories](../set_usesecondarycategories/) true értékre van állítva, akkor a [ChartData::get_SecondaryCategories](../get_secondarycategories/) adatot a másodlagos sorozatokhoz, a [ChartData::get_Categories](./) adatot pedig az elsődleges sorozatokhoz használja.

Példa. Mely kategóriák kapcsolódnak a sorozatokhoz - [ChartData::get_Categories](./) vagy [ChartData::get_SecondaryCategories](../get_secondarycategories/)?
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

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [IChartCategoryCollection](../../ichartcategorycollection/)
* Osztály [ChartData](../)
* Névtér [Aspose::Slides::Charts](../../)
* Könyvtár [Aspose.Slides](../../../)