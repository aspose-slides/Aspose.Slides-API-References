---
title: get_SeriesGroups()
second_title: Справочник API Aspose.Slides для C++
description: Получает группы серий. Только для чтения IChartSeriesGroupCollection.
type: docs
weight: 27
url: /ru/aspose.slides.charts/chartdata/get_seriesgroups/
---
## ChartData::get_SeriesGroups() метод

Получает группы серий. Только для чтения [IChartSeriesGroupCollection](../../ichartseriesgroupcollection/).

```cpp
System::SharedPtr<IChartSeriesGroupCollection> Aspose::Slides::Charts::ChartData::get_SeriesGroups() override
```

## Примечания

1) Каждая группа серий содержит серии с комбинируемыми типами. Группы комбинируемых типов серий определены и описаны с помощью перечисления CombinableSeriesTypesGroup. Кроме того, каждая группа серий содержит серии, которые отображаются либо на основной оси, либо на вторичной оси (не оба случая в одной группе). Таким образом, принцип группировки серий — это группировка по указанным выше типовым группам и по типу построения на основной/вторичной оси.

2) Группа серий содержит некоторые свойства серий, общие для каждой серии в группе ("series group properties"). "Series group properties" в классе [ChartSeriesGroup](../../chartseriesgroup/) доступны для чтения и записи. Каждое из "series group properties" может иметь только для чтения проекцию в классе [ChartSeries](../../chartseries/). 

## См. также

* Тип [SharedPtr](../../../system/sharedptr/)
* Класс [IChartSeriesGroupCollection](../../ichartseriesgroupcollection/)
* Класс [ChartData](../)
* Пространство имён [Aspose::Slides::Charts](../../)
* Библиотека [Aspose.Slides](../../../)