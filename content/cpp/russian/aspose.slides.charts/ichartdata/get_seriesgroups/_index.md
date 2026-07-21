---
title: get_SeriesGroups()
second_title: Aspose.Slides для C++ справочник API
description: Получает группы серий. Только для чтения IChartSeriesGroupCollection.
type: docs
weight: 27
url: /ru/aspose.slides.charts/ichartdata/get_seriesgroups/
---
## IChartData::get_SeriesGroups() метод

Получает группы серий. Только для чтения [IChartSeriesGroupCollection](../../ichartseriesgroupcollection/).

```cpp
virtual System::SharedPtr<IChartSeriesGroupCollection> Aspose::Slides::Charts::IChartData::get_SeriesGroups()=0
```

## Примечания

1) Каждая группа серий содержит серии с комбинируемыми типами. Группы комбинируемых типов серий определены и описаны с помощью перечисления CombinableSeriesTypesGroup. Также каждая группа серий содержит серии, которые отображаются либо на первичных осях, либо на вторичных осях (не одновременно в одной группе). Таким образом, принцип группировки серий — группировка по указанным выше типовым группам и по типу построения на первичной/вторичной оси.

2) Группа серий содержит некоторые свойства серий, общие для каждой серии в группе ("series group properties"). "Series group properties" в классе [ChartSeriesGroup](../../chartseriesgroup/) — чтение/запись. Каждое из "series group properties" может иметь проекцию только для чтения в классе [ChartSeries](../../chartseries/).

## См. также

* Тип [SharedPtr](../../../system/sharedptr/)
* Класс [IChartSeriesGroupCollection](../../ichartseriesgroupcollection/)
* Класс [IChartData](../)
* Пространство имён [Aspose::Slides::Charts](../../)
* Библиотека [Aspose.Slides](../../../)