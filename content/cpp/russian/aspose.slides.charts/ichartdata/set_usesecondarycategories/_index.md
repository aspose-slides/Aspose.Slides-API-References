---
title: set_UseSecondaryCategories()
second_title: Справочник API Aspose.Slides для C++
description: "Если установить значение false, то IChartData::get_SecondaryCategories возвращает null, и данные в IChartData::get_Categories используются как для основной, так и для вторичной серии. Если установить значение true, то данные в IChartData::get_SecondaryCategories используются для вторичной серии, а данные в IChartData::get_Categories — для основной серии. Записать bool."
type: docs
weight: 66
url: /ru/aspose.slides.charts/ichartdata/set_usesecondarycategories/
---
## IChartData::set_UseSecondaryCategories(bool) метод

Если установить значение false, то [IChartData::get_SecondaryCategories](../get_secondarycategories/) возвращает null, и данные в [IChartData::get_Categories](../get_categories/) используются как для основной, так и для вторичной серии. Если установить значение true, то данные в [IChartData::get_SecondaryCategories](../get_secondarycategories/) используются для вторичной серии, а данные в [IChartData::get_Categories](../get_categories/) — для основной серии. Записать **bool**.

```cpp
virtual void Aspose::Slides::Charts::IChartData::set_UseSecondaryCategories(bool value)=0
```

## Примечания

Пример. Какие категории относятся к сериям — ChartData.Categories или ChartData.SecondaryCategories?

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

* Класс [IChartData](../)
* Пространство имён [Aspose::Slides::Charts](../../)
* Библиотека [Aspose.Slides](../../../)