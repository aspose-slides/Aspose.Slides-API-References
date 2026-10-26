---
title: get_Categories()
second_title: Aspose.Slides для C++ справочник API
description: "Получает основные категории (или как основные, так и вторичные категории, если ChartData::set_UseSecondaryCategories установлен в false). Только для чтения IChartCategoryCollection."
type: docs
weight: 40
url: /ru/aspose.slides.charts/chartdata/get_categories/
---
## ChartData::get_Categories() метод

Получает основные категории (или как основные, так и вторичные категории, если [ChartData::set_UseSecondaryCategories](../set_usesecondarycategories/) установлен в false). Только для чтения [IChartCategoryCollection](../../ichartcategorycollection/).

```cpp
System::SharedPtr<IChartCategoryCollection> Aspose::Slides::Charts::ChartData::get_Categories() override
```

## Примечание

Если [ChartData::set_UseSecondaryCategories](../set_usesecondarycategories/) установлен в false, то [ChartData::get_SecondaryCategories](../get_secondarycategories/) возвращает null, а данные в [ChartData::get_Categories](./) используются как для основных, так и для вторичных рядов. Если [ChartData::set_UseSecondaryCategories](../set_usesecondarycategories/) установлен в true, то данные в [ChartData::get_SecondaryCategories](../get_secondarycategories/) используются для вторичных рядов, а данные в [ChartData::get_Categories](./) — для основных рядов. 

Пример. Какие категории связаны с рядом - [ChartData::get_Categories](./) или [ChartData::get_SecondaryCategories](../get_secondarycategories/)? 
```cpp
if (series->get_PlotOnSecondAxis() && series->get_Chart()->get_ChartData()->get_UseSecondaryCategories())
{
 // связанные категории находятся в series->get_Chart()->get_ChartData()->get_SecondaryCategories()
}
else
{
 // связанные категории находятся в series->get_Chart()->get_ChartData()->get_Categories()
}
```

## См. также

* typedef [SharedPtr](../../../system/sharedptr/)
* Класс [IChartCategoryCollection](../../ichartcategorycollection/)
* Класс [ChartData](../)
* Пространство имён [Aspose::Slides::Charts](../../)
* Библиотека [Aspose.Slides](../../../)