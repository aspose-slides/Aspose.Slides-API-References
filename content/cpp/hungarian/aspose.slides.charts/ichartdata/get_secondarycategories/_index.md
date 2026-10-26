---
title: get_SecondaryCategories()
second_title: Aspose.Slides for C++ API-referencia
description: "A másodlagos kategóriákat adja vissza, ha az IChartData::get_UseSecondaryCategories igaz. Csak olvasható IChartCategoryCollection."
type: docs
weight: 79
url: /hu/aspose.slides.charts/ichartdata/get_secondarycategories/
---
## IChartData::get_SecondaryCategories() metódus


A másodlagos kategóriákat adja vissza, ha [IChartData::get_UseSecondaryCategories](../get_usesecondarycategories/) igaz. Csak olvasható [IChartCategoryCollection](../../ichartcategorycollection/).

```cpp
virtual System::SharedPtr<IChartCategoryCollection> Aspose::Slides::Charts::IChartData::get_SecondaryCategories()=0
```

## Megjegyzések


Ha [IChartData::set_UseSecondaryCategories](../set_usesecondarycategories/) hamisra van állítva, akkor [IChartData::get_SecondaryCategories](./) null értéket ad vissza, és a [IChartData::get_Categories](../get_categories/) adatok mind az elsődleges, mind a másodlagos sorozatokhoz használatosak. Ha [IChartData::set_UseSecondaryCategories](../set_usesecondarycategories/) igazra van állítva, akkor a [IChartData::get_SecondaryCategories](./) adatok a másodlagos sorozatokhoz, a [IChartData::get_Categories](../get_categories/) adatok pedig az elsődleges sorozatokhoz használatosak.

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

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [IChartCategoryCollection](../../ichartcategorycollection/)
* Osztály [IChartData](../)
* Névtér [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)