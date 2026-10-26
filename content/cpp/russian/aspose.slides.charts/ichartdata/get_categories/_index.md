---
title: get_Categories()
second_title: Справочник API Aspose.Slides для C++
description: "Получает основные категории (или как основные, так и вторичные категории, если IChartData::set_UseSecondaryCategories установлен в false). Только для чтения IChartCategoryCollection."
type: docs
weight: 40
url: /ru/aspose.slides.charts/ichartdata/get_categories/
---
## IChartData::get_Categories() метод

Gets the primary categories (or both primary and secondary categories if [IChartData::set_UseSecondaryCategories](../set_usesecondarycategories/) is set to false). Read-only [IChartCategoryCollection](../../ichartcategorycollection/).

```cpp
virtual System::SharedPtr<IChartCategoryCollection> Aspose::Slides::Charts::IChartData::get_Categories()=0
```

## Remarks

If [IChartData::set_UseSecondaryCategories](../set_usesecondarycategories/) is set to false then [IChartData::get_SecondaryCategories](../get_secondarycategories/) returns null and data in [IChartData::get_Categories](./) is used both for primary and secondary series. If [IChartData::set_UseSecondaryCategories](../set_usesecondarycategories/) is set to true then data in [IChartData::get_SecondaryCategories](../get_secondarycategories/) is used for secondary series and data in [IChartData::get_Categories](./) is used for primary series. 

Example. What categories are related to series - ChartData.Categories or ChartData.SecondaryCategories? 
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

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [IChartCategoryCollection](../../ichartcategorycollection/)
* Класс [IChartData](../)
* Пространство имён [Aspose::Slides::Charts](../../)
* Библиотека [Aspose.Slides](../../../)