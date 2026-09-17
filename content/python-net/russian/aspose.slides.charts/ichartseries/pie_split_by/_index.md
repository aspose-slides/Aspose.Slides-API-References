---
title: pie_split_by property
second_title: Aspose.Slides для Python через .NET API Reference
description: 
type: docs
url: /ru/aspose.slides.charts/ichartseries/pie_split_by/
weight: 340
---
## pie_split_by свойство
Определяет, как определить, какие точки данных находятся во второй части пирога или столбце на диаграмме типа pie-of-pie или bar-of-pie. Это свойство относится не только к этой серии, но и ко всем сериям группы родительских серий — это проекция соответствующего свойства группы. И поэтому это свойство только для чтения. Используйте свойство ParentSeriesGroup для доступа к группе родительских серий. Используйте свойство ParentSeriesGroup.PieSplitBy чтение/запись для изменения значения. Только для чтения [`PieSplitType`](/slides/python-net/ru/aspose.slides.charts/piesplittype).

### Замечания

1) Это проекция свойства ParentSeriesGroup.PieSplitBy.  
2) Если значение свойства равно PieSplitType.Custom, то вы можете определить пользовательскую информацию о разбиении с помощью свойства ParentSeriesGroup.PieSplitCustomPoints.

### Определение:
```python
@property
def pie_split_by(self):
    ...
```

### См. также
* класс [`IChartSeries`](/slides/python-net/ru/aspose.slides.charts/ichartseries)
* перечисление [`PieSplitType`](/slides/python-net/ru/aspose.slides.charts/piesplittype)
* модуль [`aspose.slides.charts`](/slides/python-net/ru/aspose.slides.charts)
* библиотека [`Aspose.Slides`](/slides/python-net)