---
title: get_UseSecondaryCategories()
second_title: Aspose.Slides for C++ API Referenciája
description: "Ha false-ra van állítva, akkor a ChartData::get_SecondaryCategories null értéket ad vissza, és a ChartData::get_Categories adata mind az elsődleges, mind a másodlagos sorozathoz használatos. Ha true-ra van állítva, akkor a ChartData::get_SecondaryCategories adata a másodlagos sorozathoz, a ChartData::get_Categories adata pedig az elsődleges sorozathoz használatos. Visszatérési érték bool."
type: docs
weight: 53
url: /hu/aspose.slides.charts/chartdata/get_usesecondarycategories/
---
## ChartData::get_UseSecondaryCategories() metódus


Ha false-ra van állítva, akkor [ChartData::get_SecondaryCategories](../get_secondarycategories/) null értéket ad vissza, és a [ChartData::get_Categories](../get_categories/) adatot használja mind az elsődleges, mind a másodlagos sorozathoz. Ha true-ra van állítva, akkor a [ChartData::get_SecondaryCategories](../get_secondarycategories/) adatot használja a másodlagos sorozathoz, és a [ChartData::get_Categories](../get_categories/) adatot az elsődleges sorozathoz. Visszatérési érték **bool**.

```cpp
bool Aspose::Slides::Charts::ChartData::get_UseSecondaryCategories() override
```

## Megjegyzések


Példa. Mely kategóriák kapcsolódnak a sorozathoz – [ChartData::get_Categories](../get_categories/) vagy [ChartData::get_SecondaryCategories](../get_secondarycategories/)? 
```cpp
if (series->get_PlotOnSecondAxis() && series->get_Chart()->get_ChartData()->get_UseSecondaryCategories())
{
    // a kapcsolódó kategóriák series->get_Chart()->get_ChartData()->get_SecondaryCategories()
}
else
{
    // a kapcsolódó kategóriák series->get_Chart()->get_ChartData()->get_Categories()
}
```

## Lásd még

* Osztály [ChartData](../)
* Névterület [Aspose::Slides::Charts](../../)
* Könyvtár [Aspose.Slides](../../../)