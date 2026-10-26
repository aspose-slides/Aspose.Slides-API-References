---
title: error_bars_y_format property
second_title: Aspose.Slides для Python через .NET API Справочник
description: 
type: docs
url: /ru/aspose.slides.charts/ichartseries/error_bars_y_format/
weight: 120
---
## error_bars_y_format свойство
Represents ErrorBars of series with derection Y.
            
            ErrorBars с направлением Y доступны для серий типов area, bar, line, scatter и bubble. 
            Для любых других типов диаграмм это свойство возвращает None (включая 3D диаграммы). 
            В случае пользовательских значений используйте коллекцию DataPoints для указания значения
            (с свойством [`IChartDataPoint.error_bars_custom_values`](/slides/python-net/ru/aspose.slides.charts/ichartdatapoint/error_bars_custom_values)).
            
            Только для чтения [`IErrorBarsFormat`](/slides/python-net/ru/aspose.slides.charts/ierrorbarsformat).

### Определение:
```python
@property
def error_bars_y_format(self):
    ...
```


### См. также
* класс [`IChartSeries`](/slides/python-net/ru/aspose.slides.charts/ichartseries)
* класс [`IErrorBarsFormat`](/slides/python-net/ru/aspose.slides.charts/ierrorbarsformat)
* модуль [`aspose.slides.charts`](/slides/python-net/ru/aspose.slides.charts)
* библиотека [`Aspose.Slides`](/slides/python-net)