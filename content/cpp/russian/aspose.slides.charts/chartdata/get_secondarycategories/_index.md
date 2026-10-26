---
title: get_SecondaryCategories()
second_title: Aspose.Slides для C++ справки API
description: "Получает вторичные категории, если ChartData::get_UseSecondaryCategories истинно. Только для чтения IChartCategoryCollection."
type: docs
weight: 79
url: /ru/aspose.slides.charts/chartdata/get_secondarycategories/
---
## ChartData::get_SecondaryCategories() метод

Получает вторичные категории, если [ChartData::get_UseSecondaryCategories](../get_usesecondarycategories/) истинно. Только для чтения [IChartCategoryCollection](../../ichartcategorycollection/).

```cpp
System::SharedPtr<IChartCategoryCollection> Aspose::Slides::Charts::ChartData::get_SecondaryCategories() override
```

## Примечания

Если [ChartData::set_UseSecondaryCategories](../set_usesecondarycategories/) установлен в false, то [ChartData::get_SecondaryCategories](./) возвращает null, и данные в [ChartData::get_Categories](../get_categories/) используются как для основной, так и для вторичной серии. Если [ChartData::set_UseSecondaryCategories](../set_usesecondarycategories/) установлен в true, то данные в [ChartData::get_SecondaryCategories](./) используются для вторичной серии, а данные в [ChartData::get_Categories](../get_categories/) — для основной серии. 

Пример. Какие категории связаны с серией - [ChartData::get_Categories](../get_categories/) или [ChartData::get_SecondaryCategories](./)? 
```cpp
if (series->get_PlotOnSecondAxis() && series->get_Chart()->get_ChartData()->get_UseSecondaryCategories())
{
    // связанные категории находятся series->get_Chart()->get_ChartData()->get_SecondaryCategories()
}
else
{
    // связанные категории находятся series->get_Chart()->get_ChartData()->get_Categories()
}
```

## Смотрите также

* typedef [SharedPtr](../../../system/sharedptr/)
* класс [IChartCategoryCollection](../../ichartcategorycollection/)
* класс [ChartData](../)
* пространство имён [Aspose::Slides::Charts](../../)
* библиотека [Aspose.Slides](../../../)