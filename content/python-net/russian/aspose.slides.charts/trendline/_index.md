---
title: Trendline class
second_title: Aspose.Slides для Python через .NET справочник API
description: 
type: docs
url: /ru/aspose.slides.charts/trendline/
---
## Trendline класс

Класс представляет линию тренда серии диаграммы

Тип Trendline предоставляет следующие члены:

## Свойства

| Property | Description |
| :- | :- |
| [`trendline_name`](/slides/python-net/ru/aspose.slides.charts/trendline/trendline_name/) | Получает или задает имя линии тренда.<br/>            Чтение/запись **str**. |
| [`trendline_type`](/slides/python-net/ru/aspose.slides.charts/trendline/trendline_type/) | Получает или задает тип линии тренда.<br/>            Чтение/запись [`TrendlineType`](/slides/python-net/ru/aspose.slides.charts/trendlinetype). |
| [`format`](/slides/python-net/ru/aspose.slides.charts/trendline/format/) | Представляет формат линии тренда.<br/>            Чтение/запись [`IFormat`](/slides/python-net/ru/aspose.slides.charts/iformat). |
| [`backward`](/slides/python-net/ru/aspose.slides.charts/trendline/backward/) | Указывает количество категорий (или единиц на диаграмме рассеяния), на которое линия тренда продолжается до<br/>            данных для серии, по которой строится тренд. На диаграммах рассеяния и нерассеяния это значение должно быть любым неотрицательным<br/>            значением.<br/>            Чтение/запись **float**. |
| [`forward`](/slides/python-net/ru/aspose.slides.charts/trendline/forward/) | Указывает количество категорий (или единиц на диаграмме рассеяния), на которое линия тренда продолжается после<br/>            данных для серии, по которой строится тренд. На диаграммах рассеяния и нерассеяния это значение должно быть любым неотрицательным<br/>            значением.<br/>            Чтение/запись **float**. |
| [`intercept`](/slides/python-net/ru/aspose.slides.charts/trendline/intercept/) | Указывает значение, где линия тренда пересекает ось y. Это свойство поддерживается только<br/>            когда тип линии тренда — exp, linear или poly.<br/>            Чтение/запись **float**. |
| [`display_equation`](/slides/python-net/ru/aspose.slides.charts/trendline/display_equation/) | Указывает, что уравнение линии тренда отображается на диаграмме (в той же метке, что и значение Rsquaredvalue).<br/>            Чтение/запись **bool**. |
| [`order`](/slides/python-net/ru/aspose.slides.charts/trendline/order/) | Указывает порядок полиномиальной линии тренда. Для других типов линий тренда игнорируется. Значение должно быть от 2 до 6.<br/>            Чтение/запись **int**. |
| [`period`](/slides/python-net/ru/aspose.slides.charts/trendline/period/) | Указывает период линии тренда для скользящей средней. Он игнорируется для других<br/>            вариантов линии тренда. Значение должно быть от 2 до 255.<br/>            Чтение/запись **int**. |
| [`display_r_squared_value`](/slides/python-net/ru/aspose.slides.charts/trendline/display_r_squared_value/) | Указывает, что значение R-squared линии тренда отображается на диаграмме (в той же метке, что и уравнение).<br/>            Чтение/запись **bool**. |
| [`related_legend_entry`](/slides/python-net/ru/aspose.slides.charts/trendline/related_legend_entry/) | Представляет запись легенды, связанную с этой линией тренда<br/>            Только для чтения [`ILegendEntryProperties`](/slides/python-net/ru/aspose.slides.charts/ilegendentryproperties). |
| [`text_frame_for_overriding`](/slides/python-net/ru/aspose.slides.charts/trendline/text_frame_for_overriding/) | Может содержать текст с расширенным форматированием. Если это свойство не None, то это <br/>            отформатированное значение текста переопределяет автоматически сгенерированный текст подписи данных.<br/>            Автоматически сгенерированный текст подписи данных означает текст, управляемый свойствами ShowSeriesName, <br/>            ShowValue, ... и форматируемый с помощью свойства TextFormatManager.TextFormat.<br/>            Только для чтения [`ITextFrame`](/slides/python-net/ru/aspose.slides/itextframe). |
| [`text_format`](/slides/python-net/ru/aspose.slides.charts/trendline/text_format/) | Возвращает формат текста.<br/>            Только для чтения [`IChartTextFormat`](/slides/python-net/ru/aspose.slides.charts/icharttextformat). |
| [`chart`](/slides/python-net/ru/aspose.slides.charts/trendline/chart/) | Возвращает родительскую диаграмму.<br/>            Только для чтения [`IChart`](/slides/python-net/ru/aspose.slides.charts/ichart). |
| [`slide`](/slides/python-net/ru/aspose.slides.charts/trendline/slide/) |  |
| [`presentation`](/slides/python-net/ru/aspose.slides.charts/trendline/presentation/) |  |

## Методы

| Method | Description |
| :- | :- |
| [`add_text_frame_for_overriding(self, text)`](/slides/python-net/ru/aspose.slides.charts/trendline/add_text_frame_for_overriding/#str) | Инициализировать TextFrameForOverriding текстом из параметра "text".<br/>            Если TextFrameForOverriding уже инициализирован, то просто изменяет его текст. |

### См. также
* модуль [`aspose.slides.charts`](/slides/python-net/ru/aspose.slides.charts)
* библиотека [`Aspose.Slides`](/slides/python-net)