---
title: pie_split_by property
second_title: Aspose.Slides для Python через .NET API
description: 
type: docs
url: /ru/aspose.slides.charts/chartseries/pie_split_by/
weight: 340
---
## pie_split_by свойство
Указывает, как определить, какие точки данных находятся во втором секторе или столбце на диаграмме типо-сектор-в-секторе или типо-столбец-в-секторе. Это свойство относится не только к этой серии, но и ко всем сериям группы родительских серий — это проекция соответствующего свойства группы. Таким образом, это свойство только для чтения. Используйте свойство ParentSeriesGroup для доступа к группе родительских серий. Используйте свойство ParentSeriesGroup.PieSplitBy с чтением/записью для изменения значения. Только для чтения [`PieSplitType`](/slides/python-net/ru/aspose.slides.charts/piesplittype).

### Примечания

1) Это проекция свойства ParentSeriesGroup.PieSplitBy.
2) Если значение свойства равно PieSplitType.Custom, то вы можете задать пользовательскую информацию о разбивке с помощью свойства ParentSeriesGroup.PieSplitCustomPoints.

### Определение:
```python
@property
def pie_split_by(self):
    ...
```

### См. также
* класс [`ChartSeries`](/slides/python-net/ru/aspose.slides.charts/chartseries)
* перечисление [`PieSplitType`](/slides/python-net/ru/aspose.slides.charts/piesplittype)
* модуль [`aspose.slides.charts`](/slides/python-net/ru/aspose.slides.charts)
* библиотека [`Aspose.Slides`](/slides/python-net)