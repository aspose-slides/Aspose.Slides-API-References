---
title: get_PieSplitBy()
second_title: Aspose.Slides для C++ API Reference
description: Указывает, как определить, какие точки данных находятся во втором круге или полосе на диаграмме «круг-в-круге» или «полоса-в-круге». Это свойство относится не только к данной серии, но и ко всем сериям группы родительских серий — это проекция соответствующего группового свойства. Поэтому это свойство только для чтения. Используйте свойство ParentSeriesGroup для доступа к группе родительских серий. Используйте get_ParentSeriesGroup()->get(set)_PieSplitBy() свойство чтения/записи для изменения значения. Только для чтения PieSplitType.
type: docs
weight: 729
url: /ru/aspose.slides.charts/ichartseries/get_piesplitby/
---
## IChartSeries::get_PieSplitBy() метод

Указывает, как определить, какие точки данных находятся во втором круге или полосе на диаграмме «круг-в-круге» или «полоса-в-круге». Это свойство относится не только к данной серии, но и ко всем сериям группы родительских серий — это проекция соответствующего группового свойства. Поэтому это свойство только для чтения. Используйте свойство ParentSeriesGroup для доступа к группе родительских серий. Используйте [get_ParentSeriesGroup()](../get_parentseriesgroup/)->get(set)_PieSplitBy() свойство чтения/записи для изменения значения. Только для чтения [PieSplitType](../../piesplittype/).

```cpp
virtual PieSplitType Aspose::Slides::Charts::IChartSeries::get_PieSplitBy()=0
```

## Примечания

1) Это проекция свойства [get_ParentSeriesGroup()](../get_parentseriesgroup/)->get(set)_PieSplitBy(). 2) Если значение свойства [PieSplitType::Custom](../../piesplittype/), то вы можете определить пользовательскую информацию о разбиении с помощью свойства [get_ParentSeriesGroup()](../get_parentseriesgroup/)->[get_PieSplitCustomPoints()](../get_piesplitcustompoints/).

## См. также

* Перечисление [PieSplitType](../../piesplittype/)
* Класс [IChartSeries](../)
* Пространство имён [Aspose::Slides::Charts](../../)
* Библиотека [Aspose.Slides](../../../)