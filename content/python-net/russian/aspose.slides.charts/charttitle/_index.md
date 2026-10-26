---
title: ChartTitle class
second_title: Aspose.Slides для Python через .NET API Reference
description: 
type: docs
url: /ru/aspose.slides.charts/charttitle/
---
## ChartTitle класс

Представляет свойства заголовка диаграммы.

Тип ChartTitle раскрывает следующие члены:

## Свойства

| Property | Description |
| :- | :- |
| [`x`](/slides/python-net/ru/aspose.slides.charts/charttitle/x/) | Возвращает или задает координату x заголовка как долю от ширины диаграммы.<br/>            Чтение/запись **float**. |
| [`y`](/slides/python-net/ru/aspose.slides.charts/charttitle/y/) | Возвращает или задает координату y заголовка как долю от высоты диаграммы.<br/>            Чтение/запись **float**. |
| [`width`](/slides/python-net/ru/aspose.slides.charts/charttitle/width/) | Возвращает или задает ширину заголовка как долю от ширины диаграммы.<br/>            Чтение/запись **float**. |
| [`height`](/slides/python-net/ru/aspose.slides.charts/charttitle/height/) | Возвращает или задает высоту заголовка как долю от высоты диаграммы.<br/>            Чтение/запись **float**. |
| [`right`](/slides/python-net/ru/aspose.slides.charts/charttitle/right/) | Right.<br/>            Только для чтения **float**. |
| [`bottom`](/slides/python-net/ru/aspose.slides.charts/charttitle/bottom/) | Bottom.<br/>            Только для чтения **float**. |
| [`overlay`](/slides/python-net/ru/aspose.slides.charts/charttitle/overlay/) | Определяет, разрешено ли другим элементам диаграммы перекрывать заголовок.<br/>            Чтение/запись **bool**. |
| [`format`](/slides/python-net/ru/aspose.slides.charts/charttitle/format/) | Возвращает стили заполнения, линии и эффектов заголовка.<br/>            Только для чтения [`IFormat`](/slides/python-net/ru/aspose.slides.charts/iformat). |
| [`text_frame_for_overriding`](/slides/python-net/ru/aspose.slides.charts/charttitle/text_frame_for_overriding/) | Может содержать богато отформатированный текст. Если это свойство не None, то это <br/>            отформатированное текстовое значение переопределяет автоматически сгенерированный текст.<br/>            Автогенерированный текст — неявное свойство подписи данных, подписи единицы измерения оси значений, заголовка оси, заголовка диаграммы, подписи тренд-линии.<br/>            Автогенерированный текст форматируется свойством IFormattedTextContainer.TextFormat.<br/>            Только для чтения [`ITextFrame`](/slides/python-net/ru/aspose.slides/itextframe). |
| [`text_format`](/slides/python-net/ru/aspose.slides.charts/charttitle/text_format/) | Возвращает формат текста.<br/>            Только для чтения [`IChartTextFormat`](/slides/python-net/ru/aspose.slides.charts/icharttextformat). |
| [`actual_x`](/slides/python-net/ru/aspose.slides.charts/charttitle/actual_x/) | Указывает фактическое положение x (слева) элемента диаграммы относительно левого верхнего угла диаграммы.<br/>            Вызовите метод IChart.ValidateChartLayout() перед этим, чтобы получить фактические значения.<br/>            Чтение **float**. |
| [`actual_y`](/slides/python-net/ru/aspose.slides.charts/charttitle/actual_y/) | Указывает фактическую верхнюю позицию элемента диаграммы относительно левого верхнего угла диаграммы.<br/>            Вызовите метод IChart.ValidateChartLayout() перед этим, чтобы получить фактические значения.<br/>            Чтение **float**. |
| [`actual_width`](/slides/python-net/ru/aspose.slides.charts/charttitle/actual_width/) | Указывает фактическую ширину элемента диаграммы. Вызовите метод IChart.ValidateChartLayout() перед этим, чтобы получить фактические значения.<br/>            Чтение **float**. |
| [`actual_height`](/slides/python-net/ru/aspose.slides.charts/charttitle/actual_height/) | Указывает фактическую высоту элемента диаграммы. Вызовите метод IChart.ValidateChartLayout() перед этим, чтобы получить фактические значения.<br/>            Чтение **float**. |
| [`chart`](/slides/python-net/ru/aspose.slides.charts/charttitle/chart/) | Возвращает родительскую диаграмму.<br/>            Только для чтения [`IChart`](/slides/python-net/ru/aspose.slides.charts/ichart). |
| [`slide`](/slides/python-net/ru/aspose.slides.charts/charttitle/slide/) |  |
| [`presentation`](/slides/python-net/ru/aspose.slides.charts/charttitle/presentation/) |  |

## Методы

| Method | Description |
| :- | :- |
| [`add_text_frame_for_overriding(self, text)`](/slides/python-net/ru/aspose.slides.charts/charttitle/add_text_frame_for_overriding/#str) | Инициализирует TextFrameForOverriding текстом из параметра "text".<br/>            Если TextFrameForOverriding уже инициализирован, просто изменяет его текст. |

### Смотрите также
* модуль [`aspose.slides.charts`](/slides/python-net/ru/aspose.slides.charts)
* библиотека [`Aspose.Slides`](/slides/python-net)