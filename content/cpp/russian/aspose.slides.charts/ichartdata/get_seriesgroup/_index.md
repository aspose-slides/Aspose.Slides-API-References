---
title: get_SeriesGroup()
second_title: Aspose.Slides для C++ справочник API
description: 
type: docs
weight: 222
url: /ru/aspose.slides.charts/ichartdata/get_seriesgroup/
---
## IChartData::get_SeriesGroup(System::SharedPtr\<IChartSeries\>) метод




```cpp
virtual System::SharedPtr<IChartSeriesGroup> Aspose::Slides::Charts::IChartData::get_SeriesGroup(System::SharedPtr<IChartSeries> ofSeries)=0
```

## IChartData::get_SeriesGroup(int32_t) метод


Возвращает группу серий по указанному индексу.

```cpp
virtual System::SharedPtr<IChartSeriesGroup> Aspose::Slides::Charts::IChartData::get_SeriesGroup(int32_t index)=0
```

## Remarks


1) Каждая группа серий содержит серии совместимых типов. Группы совместимых типов серий определены и описаны перечислением CombinableSeriesTypesGroup. Кроме того, каждая группа серий содержит серии, отображаемые либо на первичной оси, либо на вторичной оси (не оба случая в одной группе). Следовательно, принцип группировки серий — группировка по типам, упомянутым выше, и по типу построения — первичная/вторичная ось. 2) Группа серий содержит некоторые свойства серий, общие для каждой серии в группе («свойства группы серий»). «Свойства группы серий» в классе [ChartSeriesGroup](../../chartseriesgroup/) являются чтение/запись. Каждое из «свойств группы серий» может иметь только-для-чтения проекцию в классе [ChartSeries](../../chartseries/). 
## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [IChartSeriesGroup](../../ichartseriesgroup/)
* Класс [IChartSeries](../../ichartseries/)
* Класс [IChartData](../)
* Пространство имен [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)