---
title: set_UseSecondaryCategories()
second_title: Aspose.Slides for C++ API-referencia
description: "Ha false értékre van beállítva, akkor a ChartData::get_SecondaryCategories null értéket ad vissza, és a ChartData::get_Categories adata mind az elsődleges, mind a másodlagos sorozatokhoz használatos. Ha true értékre van beállítva, akkor a ChartData::get_SecondaryCategories adata a másodlagos sorozatokhoz, a ChartData::get_Categories adata pedig az elsődleges sorozatokhoz használatos. Írjon bool."
type: docs
weight: 66
url: /hu/aspose.slides.charts/chartdata/set_usesecondarycategories/
---

## ChartData::set_UseSecondaryCategories(bool) metódus

Ha false értékre van beállítva, akkor a [ChartData::get_SecondaryCategories](../get_secondarycategories/) null értéket ad vissza, és a [ChartData::get_Categories](../get_categories/) adata mind az elsődleges, mind a másodlagos sorozatokhoz használatos. Ha true értékre van beállítva, akkor a [ChartData::get_SecondaryCategories](../get_secondarycategories/) adata a másodlagos sorozatokhoz, a [ChartData::get_Categories](../get_categories/) adata pedig az elsődleges sorozatokhoz használatos. Írja **bool**.

```cpp
void Aspose::Slides::Charts::ChartData::set_UseSecondaryCategories(bool value) override
```

## Megjegyzések

Példa. Mely kategóriák kapcsolódnak a sorozatokhoz - [ChartData::get_Categories](../get_categories/) vagy [ChartData::get_SecondaryCategories](../get_secondarycategories/)? 
```cpp
if (series->get_PlotOnSecondAxis() && series->get_Chart()->get_ChartData()->get_UseSecondaryCategories())
{
    // kapcsolódó kategóriák a series->get_Chart()->get_ChartData()->get_SecondaryCategories()
}
else
{
    // kapcsolódó kategóriák a series->get_Chart()->get_ChartData()->get_Categories()
}
```

## Lásd még

* Osztály [ChartData](../)
* Névtér [Aspose::Slides::Charts](../../)
* Könyvtár [Aspose.Slides](../../../)