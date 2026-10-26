---
title: overlap property
second_title: Aspose.Slides для Python через .NET Справочник API
description: 
type: docs
url: /ru/aspose.slides.charts/ichartseries/overlap/
weight: 310
---
## Свойство overlap
Указывает, насколько полосы и столбцы перекрываются на 2-D диаграммах, в процентах (от -100% до 100%). 
            Это свойство относится не только к этой серии, но и ко всем сериям группы родительских серий. 
            Это проекция соответствующего свойства в группе родительских серий, поэтому это свойство только для чтения.
            Чтобы изменить значение, используйте свойство ParentSeriesGroup.Overlap, доступное для чтения/записи.
            Только для чтения **int**.


### Примечания

Overlap указывает степень перекрытия или промежутка между полосами и столбцами в процентах от их ширины:
            - -100%: Максимальный промежуток (полосы полностью разделены).
            - 0%: Полосы размещаются рядом без перекрытия и без промежутка.
            - 100%: Максимальное перекрытие (полосы полностью перекрывают друг друга).
            Это проекция свойства ParentSeriesGroup.Overlap.

### Определение:
```python
@property
def overlap(self):
    ...
```


### См. также
* класс [`IChartSeries`](/slides/python-net/ru/aspose.slides.charts/ichartseries)
* модуль [`aspose.slides.charts`](/slides/python-net/ru/aspose.slides.charts)
* библиотека [`Aspose.Slides`](/slides/python-net)