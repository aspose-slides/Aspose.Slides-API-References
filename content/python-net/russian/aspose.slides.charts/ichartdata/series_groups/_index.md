---
title: series_groups property
second_title: Aspose.Slides для Python через .NET Справочник API
description: 
type: docs
url: /ru/aspose.slides.charts/ichartdata/series_groups/
weight: 140
---
## series_groups свойство
Получает группы рядов.
Только для чтения [`IChartSeriesGroupCollection`](/slides/python-net/ru/aspose.slides.charts/ichartseriesgroupcollection).

### Замечания

1) Каждая группа рядов содержит ряды с комбинируемыми типами. Группы комбинируемых типов рядов определяются и описываются перечислением CombinableSeriesTypesGroup. Также каждая группа рядов содержит ряды, которые отображаются либо на первичной оси, либо на вторичной оси (не обе версии в одной группе). Таким образом, принцип группировки рядов — это группировка по типовым группам, упомянутым выше, и по типу отображения primary/secondary.

2) Группа рядов содержит некоторые свойства рядов, общие для каждого ряда в группе "series group properties". "series group properties" в классе ChartSeriesGroup является чтение/запись. Каждое из "series group properties" может иметь только для чтения проекцию в классе ChartSeries.

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