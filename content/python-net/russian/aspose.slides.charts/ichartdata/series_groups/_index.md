---
title: series_groups property
second_title: Aspose.Slides для Python через .NET справочник API
description: 
type: docs
url: /ru/aspose.slides.charts/ichartdata/series_groups/
weight: 150
---
## series_groups свойство
Получает группы рядов.
            Только для чтения [`IChartSeriesGroupCollection`](/slides/python-net/ru/aspose.slides.charts/ichartseriesgroupcollection).


### Примечания

1) Каждая группа рядов содержит ряды с комбинируемыми типами. Группы
            комбинируемых типов рядов определены и описаны перечислением CombinableSeriesTypesGroup
            enum.
            Также каждая группа рядов содержит ряды, которые отображаются либо
            на первичных осях, либо на вторичных осях (не обе случаи в одной группе).
            Таким образом, принцип группировки рядов — это группировка по типовым группам,
            упомянутым выше, и по типу построения на первичной/вторичной оси.

            2) Группа рядов содержит некоторые свойства рядов, которые общие для
            каждого ряда в группе ("свойства группы рядов").
            "Свойства группы рядов" в классе ChartSeriesGroup являются read/write.
            Каждое из "свойства группы рядов" может иметь только для чтения проекцию в классе ChartSeries.

### Определение:
```python
@property
def series_groups(self):
    ...
```


### См. также
* класс [`IChartData`](/slides/python-net/ru/aspose.slides.charts/ichartdata)
* класс [`IChartSeriesGroupCollection`](/slides/python-net/ru/aspose.slides.charts/ichartseriesgroupcollection)
* модуль [`aspose.slides.charts`](/slides/python-net/ru/aspose.slides.charts)
* библиотека [`Aspose.Slides`](/slides/python-net)