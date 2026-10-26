---
title: get_PieSplitBy()
second_title: Aspose.Slides для C++ справочник API
description: Определяет, как определить, какие точки данных находятся во втором круге или столбце на диаграмме pie-of-pie или bar-of-pie. Это свойство относится не только к этой серии, но и ко всем сериям группы родительской серии — это проекция соответствующего свойства группы. Поэтому это свойство только для чтения. Используйте свойство ParentSeriesGroup для доступа к группе родительской серии. Используйте get_ParentSeriesGroup()->get(set)_PieSplitBy() свойство чтения/записи для изменения значения. Только для чтения PieSplitType.
type: docs
weight: 755
url: /ru/aspose.slides.charts/chartseries/get_piesplitby/
---
## ChartSeries::get_PieSplitBy() метод

Указывает, как определить, какие точки данных находятся во втором круге или колонке на диаграмме «pie-of-pie» или «bar-of-pie». Это свойство относится не только к этой серии, но и ко всем сериям группы родительской серии — это проекция соответствующего свойства группы. Поэтому это свойство только для чтения. Используйте свойство ParentSeriesGroup для доступа к группе родительской серии. Используйте [get_ParentSeriesGroup()](../get_parentseriesgroup/)->get(set)_PieSplitBy() для чтения/записи, чтобы изменить значение. Только для чтения [PieSplitType](../../piesplittype/).

```cpp
PieSplitType Aspose::Slides::Charts::ChartSeries::get_PieSplitBy() override
```

## Примечания

1) Это проекция свойства [get_ParentSeriesGroup()](../get_parentseriesgroup/)->get(set)_PieSplitBy(). 2) Если значение свойства [PieSplitType::Custom](../../piesplittype/), то вы можете задать пользовательскую информацию о разбиении с помощью свойства [get_ParentSeriesGroup()](../get_parentseriesgroup/)->[get_PieSplitCustomPoints()](../get_piesplitcustompoints/).

## Смотрите также

* Перечисление [PieSplitType](../../piesplittype/)
* Класс [ChartSeries](../)
* Пространство имён [Aspose::Slides::Charts](../../)
* Библиотека [Aspose.Slides](../../../)