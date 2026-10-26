---
title: get_SecondaryCategories()
second_title: Справка API Aspose.Slides для C++
description: "Получает вторичные категории, если IChartData::get_UseSecondaryCategories равно true. Только для чтения IChartCategoryCollection."
type: docs
weight: 79
url: /ru/aspose.slides.charts/ichartdata/get_secondarycategories/
---
## IChartData::get_SecondaryCategories() метод

Получает вторичные категории, если [IChartData::get_UseSecondaryCategories](../get_usesecondarycategories/) равно true. Только для чтения [IChartCategoryCollection](../../ichartcategorycollection/).

```cpp
virtual System::SharedPtr<IChartCategoryCollection> Aspose::Slides::Charts::IChartData::get_SecondaryCategories()=0
```

## Примечания

Если [IChartData::set_UseSecondaryCategories](../set_usesecondarycategories/) установлен в false, то [IChartData::get_SecondaryCategories](./) возвращает null, а данные в [IChartData::get_Categories](../get_categories/) используются как для первичной, так и для вторичной серии. Если [IChartData::set_UseSecondaryCategories](../set_usesecondarycategories/) установлен в true, то данные в [IChartData::get_SecondaryCategories](./) используются для вторичной серии, а данные в [IChartData::get_Categories](../get_categories/) — для первичной серии.

Пример. Какие категории относятся к сериям — ChartData.Categories или ChartData.SecondaryCategories?
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

* Тип [SharedPtr](../../../system/sharedptr/)
* Класс [IChartCategoryCollection](../../ichartcategorycollection/)
* Класс [IChartData](../)
* Пространство имён [Aspose::Slides::Charts](../../)
* Библиотека [Aspose.Slides](../../../)