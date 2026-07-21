---
title: set_UseSecondaryCategories()
second_title: Aspose.Slides для C++ справка по API
description: "Если установить значение false, то ChartData::get_SecondaryCategories возвращает null, и данные в ChartData::get_Categories используются как для основной, так и для вторичной серии. Если установить значение true, то данные в ChartData::get_SecondaryCategories используются для вторичной серии, а данные в ChartData::get_Categories используются для основной серии. Запишите bool."
type: docs
weight: 66
url: /ru/aspose.slides.charts/chartdata/set_usesecondarycategories/
---
## ChartData::set_UseSecondaryCategories(bool) метод


Если установить значение false, тогда [ChartData::get_SecondaryCategories](../get_secondarycategories/) возвращает null, и данные в [ChartData::get_Categories](../get_categories/) используются как для основной, так и для вторичной серии. Если установить значение true, тогда данные в [ChartData::get_SecondaryCategories](../get_secondarycategories/) используются для вторичной серии, а данные в [ChartData::get_Categories](../get_categories/) — для основной серии. Запишите **bool**.

```cpp
void Aspose::Slides::Charts::ChartData::set_UseSecondaryCategories(bool value) override
```

## Примечания


Пример. Какие категории связаны с серией — [ChartData::get_Categories](../get_categories/) или [ChartData::get_SecondaryCategories](../get_secondarycategories/)? 
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

* Класс [ChartData](../)
* Пространство имён [Aspose::Slides::Charts](../../)
* Библиотека [Aspose.Slides](../../../)