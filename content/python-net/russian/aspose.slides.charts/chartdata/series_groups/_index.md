---
title: series_groups property
second_title: Aspose.Slides для Python через .NET — справочник API
description: 
type: docs
url: /ru/aspose.slides.charts/chartdata/series_groups/
weight: 140
---
## series_groups свойство
Получает группы серий.
Только для чтения [`IChartSeriesGroupCollection`](/slides/python-net/ru/aspose.slides.charts/ichartseriesgroupcollection).

### Примечания

1) Каждая группа серий содержит серии с комбинируемыми типами. Группы комбинируемых типов серий определены и описаны перечислением CombinableSeriesTypesGroup enum. Также каждая группа серий содержит серии, которые отображаются либо на главных осях, либо на вторичных осях (не оба случая в одной группе). Таким образом, принцип группировки серий — это группировка по типовым группам, упомянутым выше, и по типу построения на главных/вторичных осях.

2) Группа серий содержит некоторые свойства серий, общие для каждой серии в группе ("Series group properties"). "Series group properties" в классе ChartSeriesGroup имеют режим read/write. Каждое из "Series group properties" может иметь только для чтения проекцию в классе ChartSeries.

### Определение:
```python
@property
def series_groups(self):
    ...
```

### См. также
* класс [`ChartData`](/slides/python-net/ru/aspose.slides.charts/chartdata)
* класс [`IChartSeriesGroupCollection`](/slides/python-net/ru/aspose.slides.charts/ichartseriesgroupcollection)
* модуль [`aspose.slides.charts`](/slides/python-net/ru/aspose.slides.charts)
* библиотека [`Aspose.Slides`](/slides/python-net)