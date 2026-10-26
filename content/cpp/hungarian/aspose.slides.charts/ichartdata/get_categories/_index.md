---
title: get_Categories()
second_title: Aspose.Slides C++ API referencia
description: "Lekéri az elsődleges kategóriákat (vagy az elsődleges és másodlagos kategóriákat is, ha az IChartData::set_UseSecondaryCategories hamisra van állítva). Csak olvasható IChartCategoryCollection."
type: docs
weight: 40
url: /hu/aspose.slides.charts/ichartdata/get_categories/
---
## IChartData::get_Categories() metódus


A lekéri az elsődleges kategóriákat (vagy az elsődleges és másodlagos kategóriákat is, ha [IChartData::set_UseSecondaryCategories](../set_usesecondarycategories/) hamisra van állítva). Csak olvasható [IChartCategoryCollection](../../ichartcategorycollection/).

```cpp
virtual System::SharedPtr<IChartCategoryCollection> Aspose::Slides::Charts::IChartData::get_Categories()=0
```

## Megjegyzések


Ha [IChartData::set_UseSecondaryCategories](../set_usesecondarycategories/) hamisra van állítva, akkor [IChartData::get_SecondaryCategories](../get_secondarycategories/) null értéket ad vissza, és a [IChartData::get_Categories](./)-ban lévő adat mind elsődleges, mind másodlagos sorozatokhoz használható. Ha [IChartData::set_UseSecondaryCategories](../set_usesecondarycategories/) igazra van állítva, akkor a [IChartData::get_SecondaryCategories](../get_secondarycategories/)-ban lévő adat a másodlagos sorozatokhoz, a [IChartData::get_Categories](./)-ban lévő adat pedig az elsődleges sorozatokhoz használható. 

Példa. Mely kategóriák kapcsolódnak a sorozatokhoz – ChartData.Categories vagy ChartData.SecondaryCategories? 
```cpp
if (series->get_PlotOnSecondAxis() && series->get_Chart()->get_ChartData()->get_UseSecondaryCategories())
{
    // related categories are series->get_Chart()->get_ChartData()->get_SecondaryCategories()
}
else
{
    // related categories are series->get_Chart()->get_ChartData()->get_Categories()
}
```

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [IChartCategoryCollection](../../ichartcategorycollection/)
* Osztály [IChartData](../)
* Névtér [Aspose::Slides::Charts](../../)
* Könyvtár [Aspose.Slides](../../../)