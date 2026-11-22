---
title: series_groups property
second_title: Справочник API Aspose.Slides для Python через .NET
description: 
type: docs
url: /ru/aspose.slides.charts/chartdata/series_groups/
weight: 150
---
## series_groups свойство
Получает группы серий.
Только для чтения [`IChartSeriesGroupCollection`](/slides/python-net/ru/aspose.slides.charts/ichartseriesgroupcollection).

### Примечания

1) Каждая группа рядов содержит ряды с комбинируемыми типами. Группы комбинируемых типов рядов определены и описаны перечислением CombinableSeriesTypesGroup enum. Также каждая группа рядов содержит ряды, которые отображаются либо на первичной оси, либо на вторичной оси (не оба случая в одной группе). Таким образом, принцип группировки рядов — это группировка по типовым группам, упомянутым выше, и по типу построения на первичной/вторичной оси.

2) Группа рядов содержит некоторые свойства рядов, общие для каждого ряда в группе ("series group properties").
"Series group properties" в классе ChartSeriesGroup — чтение/запись.
Каждое из "series group properties" может иметь только для чтения проекцию в классе ChartSeries.

### Определение:
```python
@property
def series_groups(self):
    ...
```

### Смотрите также
* класс [`ChartData`](/slides/python-net/ru/aspose.slides.charts/chartdata)
* класс [`IChartSeriesGroupCollection`](/slides/python-net/ru/aspose.slides.charts/ichartseriesgroupcollection)
* модуль [`aspose.slides.charts`](/slides/python-net/ru/aspose.slides.charts)
* библиотека [`Aspose.Slides`](/slides/python-net)