---
title: get_SecondaryCategories()
second_title: Aspose.Slides for C++ API-referencia
description: "Lekéri a másodlagos kategóriákat, ha a ChartData::get_UseSecondaryCategories igaz. Csak olvasható IChartCategoryCollection."
type: docs
weight: 79
url: /hu/aspose.slides.charts/chartdata/get_secondarycategories/
---
## ChartData::get_SecondaryCategories() metódus

Lekéri a másodlagos kategóriákat, ha [ChartData::get_UseSecondaryCategories](../get_usesecondarycategories/) igaz. Csak olvasható [IChartCategoryCollection](../../ichartcategorycollection/).

```cpp
System::SharedPtr<IChartCategoryCollection> Aspose::Slides::Charts::ChartData::get_SecondaryCategories() override
```

## Megjegyzések

Ha [ChartData::set_UseSecondaryCategories](../set_usesecondarycategories/) hamisra van állítva, akkor [ChartData::get_SecondaryCategories](./) null értéket ad vissza, és a [ChartData::get_Categories](../get_categories/) adata mind az elsődleges, mind a másodlagos sorozathoz használatos. Ha [ChartData::set_UseSecondaryCategories](../set_usesecondarycategories/) igazra van állítva, akkor a [ChartData::get_SecondaryCategories](./) adata a másodlagos sorozathoz, a [ChartData::get_Categories](../get_categories/) adata pedig az elsődleges sorozathoz kerül felhasználásra.

Példa. Mely kategóriák kapcsolódnak a sorozathoz - [ChartData::get_Categories](../get_categories/) vagy [ChartData::get_SecondaryCategories](./)?

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