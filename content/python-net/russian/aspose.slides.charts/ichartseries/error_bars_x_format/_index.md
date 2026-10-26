---
title: error_bars_x_format property
second_title: Aspose.Slides для Python через .NET справочник API
description: 
type: docs
url: /ru/aspose.slides.charts/ichartseries/error_bars_x_format/
weight: 110
---
## error_bars_x_format свойство
Представляет ErrorBars серии с направлением X.

            ErrorBars с направлением X доступны для серий типа area, bar, scatter и bubble.
            Для всех остальных типов диаграмм это свойство возвращает None (включая 3D-диаграммы).
            В случае пользовательских значений используйте коллекцию DataPoints для указания значения
            (with [`IChartDataPoint.error_bars_custom_values`](/slides/python-net/ru/aspose.slides.charts/ichartdatapoint/error_bars_custom_values) свойство).

            Только для чтения [`IErrorBarsFormat`](/slides/python-net/ru/aspose.slides.charts/ierrorbarsformat).

### Определение:
```python
@property
def error_bars_x_format(self):
    ...
```

### См. также
* класс [`IChartSeries`](/slides/python-net/ru/aspose.slides.charts/ichartseries)
* класс [`IErrorBarsFormat`](/slides/python-net/ru/aspose.slides.charts/ierrorbarsformat)
* модуль [`aspose.slides.charts`](/slides/python-net/ru/aspose.slides.charts)
* library [`Aspose.Slides`](/slides/python-net)