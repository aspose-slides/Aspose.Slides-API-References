---
title: get_SeriesGroup()
second_title: Справочник API Aspose.Slides для C++
description: 
type: docs
weight: 222
url: /ru/aspose.slides.charts/chartdata/get_seriesgroup/
---
## ChartData::get_SeriesGroup(System::SharedPtr\<IChartSeries\>) метод




```cpp
System::SharedPtr<IChartSeriesGroup> Aspose::Slides::Charts::ChartData::get_SeriesGroup(System::SharedPtr<IChartSeries> ofSeries) override
```

## ChartData::get_SeriesGroup(int32_t) метод


Возвращает группу рядов по указанному индексу.

```cpp
System::SharedPtr<IChartSeriesGroup> Aspose::Slides::Charts::ChartData::get_SeriesGroup(int32_t index) override
```

## Примечания


1) Каждая группа рядов содержит ряды с комбинируемыми типами. Группы комбинируемых типов рядов определены и описаны перечислением CombinableSeriesTypesGroup. Также каждая группа рядов содержит ряды, которые отображаются либо на основных осях, либо на вторичных осях (не в обоих случаях в одной группе). Таким образом, принцип группировки рядов — группировка по вышеупомянутым типовым группам и по типу построения на основной/вторичной оси. 2) Группа рядов содержит некоторые свойства рядов, общие для каждого ряда в группе («свойства группы рядов»). «Свойства группы рядов» в классе [ChartSeriesGroup](../../chartseriesgroup/) являются чтение/запись. Каждое из «свойств группы рядов» может иметь только для чтения проекцию в классе [ChartSeries](../../chartseries/). 
## См. также

* Тип [SharedPtr](../../../system/sharedptr/)
* Класс [IChartSeriesGroup](../../ichartseriesgroup/)
* Класс [IChartSeries](../../ichartseries/)
* Класс [ChartData](../)
* Пространство имён [Aspose::Slides::Charts](../../)
* Библиотека [Aspose.Slides](../../../)