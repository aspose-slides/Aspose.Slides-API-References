---
title: get_UseSecondaryCategories()
second_title: Aspose.Slides для C++ справочник API
description: "Если установлено в false, то IChartData::get_SecondaryCategories возвращает null, а данные в IChartData::get_Categories используются как для основной, так и для вторичной серии. Если установлено в true, то данные в IChartData::get_SecondaryCategories используются для вторичной серии, а данные в IChartData::get_Categories — для основной серии. Читать bool."
type: docs
weight: 53
url: /ru/aspose.slides.charts/ichartdata/get_usesecondarycategories/
---
## IChartData::get_UseSecondaryCategories() метод

Если установлено в false, то [IChartData::get_SecondaryCategories](../get_secondarycategories/) возвращает null, а данные в [IChartData::get_Categories](../get_categories/) используются как для основной, так и для вторичной серии. Если установлено в true, то данные в [IChartData::get_SecondaryCategories](../get_secondarycategories/) используются для вторичной серии, а данные в [IChartData::get_Categories](../get_categories/) — для основной серии. Читать **bool**.

```cpp
virtual bool Aspose::Slides::Charts::IChartData::get_UseSecondaryCategories()=0
```

## Примечания

Пример. Какие категории связаны с серией — ChartData.Categories или ChartData.SecondaryCategories?
```cpp
if (series->get_PlotOnSecondAxis() && series->get_Chart()->get_ChartData()->get_UseSecondaryCategories())
{
    // связанные категории: series->get_Chart()->get_ChartData()->get_SecondaryCategories()
}
else
{
    // связанные категории: series->get_Chart()->get_ChartData()->get_Categories()
}
```

## Смотрите также

* Класс [IChartData](../)
* Пространство имён [Aspose::Slides::Charts](../../)
* Библиотека [Aspose.Slides](../../../)