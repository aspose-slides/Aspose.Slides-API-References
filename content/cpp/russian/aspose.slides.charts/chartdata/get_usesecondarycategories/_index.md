---
title: get_UseSecondaryCategories()
second_title: Aspose.Slides для C++ API Reference
description: "Если установлено в false, то ChartData::get_SecondaryCategories возвращает null и данные в ChartData::get_Categories используются как для основной, так и для вторичной серии. Если установлено в true, то данные в ChartData::get_SecondaryCategories используются для вторичной серии, а данные в ChartData::get_Categories — для основной серии. Чтение bool."
type: docs
weight: 53
url: /ru/aspose.slides.charts/chartdata/get_usesecondarycategories/
---
## ChartData::get_UseSecondaryCategories() метод

Если установлено в false, тогда [ChartData::get_SecondaryCategories](../get_secondarycategories/) возвращает null, и данные в [ChartData::get_Categories](../get_categories/) используются как для основной, так и для вторичной серии. Если установлено в true, тогда данные в [ChartData::get_SecondaryCategories](../get_secondarycategories/) используются для вторичной серии, а данные в [ChartData::get_Categories](../get_categories/) — для основной серии. Читать **bool**.

```cpp
bool Aspose::Slides::Charts::ChartData::get_UseSecondaryCategories() override
```

## Примечания

Пример. Какие категории связаны с сериями — [ChartData::get_Categories](../get_categories/) или [ChartData::get_SecondaryCategories](../get_secondarycategories/)?
```cpp
if (series->get_PlotOnSecondAxis() && series->get_Chart()->get_ChartData()->get_UseSecondaryCategories())
{
    // связанные категории - series->get_Chart()->get_ChartData()->get_SecondaryCategories()
}
else
{
    // связанные категории - series->get_Chart()->get_ChartData()->get_Categories()
}
```

## См. также

* Класс [ChartData](../)
* Пространство имён [Aspose::Slides::Charts](../../)
* Библиотека [Aspose.Slides](../../../)