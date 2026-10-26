---
title: ErrorBarsFormat class
second_title: Aspose.Slides для Python через .NET API Справочник
description: 
type: docs
url: /ru/aspose.slides.charts/errorbarsformat/
---
## ErrorBarsFormat класс

Представляет линии ошибок серии диаграммы. ErrorBars пользовательские значения находятся в IChartDataPointCollection (в свойстве [`IChartDataPoint.error_bars_custom_values`](/slides/python-net/ru/aspose.slides.charts/ichartdatapoint/error_bars_custom_values)).

Тип ErrorBarsFormat раскрывает следующие члены:

## Свойства

| Property | Description |
| :- | :- |
| [`type`](/slides/python-net/ru/aspose.slides.charts/errorbarsformat/type/) | Получает или задает тип линий ошибок. <br/>            Чтение/запись [`ErrorBarType`](/slides/python-net/ru/aspose.slides.charts/errorbartype). |
| [`value_type`](/slides/python-net/ru/aspose.slides.charts/errorbarsformat/value_type/) | Представляет возможные способы определения длины линий ошибок. <br/>            В случае пользовательского типа значения для указания значения используйте свойство [`IChartDataPoint.error_bars_custom_values`](/slides/python-net/ru/aspose.slides.charts/ichartdatapoint/error_bars_custom_values) конкретной точки данных в коллекции DataPoints серии.<br/>            В случае типов значений Fixed, Percentage или StandardDeviation используйте свойство Value для указания значения.  <br/>            Чтение/запись [`ErrorBarValueType`](/slides/python-net/ru/aspose.slides.charts/errorbarvaluetype). |
| [`has_end_cap`](/slides/python-net/ru/aspose.slides.charts/errorbarsformat/has_end_cap/) | Указывает, что конечная крышка не рисуется на линиях ошибок.<br/>            Чтение/запись **bool**. |
| [`value`](/slides/python-net/ru/aspose.slides.charts/errorbarsformat/value/) | Получает или задает значение, которое используется с типами значений Fixed, Percentage и StandardDeviation для определения длины линий ошибок. <br/>            В любом другом случае будет возвращать NaN.<br/>            Чтение/запись **float**. |
| [`format`](/slides/python-net/ru/aspose.slides.charts/errorbarsformat/format/) | Представляет формат линий ошибок.<br/>            Чтение/запись [`IFormat`](/slides/python-net/ru/aspose.slides.charts/iformat). |
| [`chart`](/slides/python-net/ru/aspose.slides.charts/errorbarsformat/chart/) | Возвращает родительскую диаграмму.<br/>            Только чтение [`IChart`](/slides/python-net/ru/aspose.slides.charts/ichart). |
| [`is_visible`](/slides/python-net/ru/aspose.slides.charts/errorbarsformat/is_visible/) | Получает или задает видимость линий ошибок.<br/>            Чтение/запись **bool**. |
| [`slide`](/slides/python-net/ru/aspose.slides.charts/errorbarsformat/slide/) |  |
| [`presentation`](/slides/python-net/ru/aspose.slides.charts/errorbarsformat/presentation/) |  |

### См. также
* модуль [`aspose.slides.charts`](/slides/python-net/ru/aspose.slides.charts)
* библиотека [`Aspose.Slides`](/slides/python-net)