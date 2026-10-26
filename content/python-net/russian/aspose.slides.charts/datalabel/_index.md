---
title: DataLabel class
second_title: Aspose.Slides для Python через .NET Справочник API
description: 
type: docs
url: /ru/aspose.slides.charts/datalabel/
---
## DataLabel класс

Представляет подписи серии.

Тип DataLabel раскрывает следующие члены:

## Конструкторы

| Конструктор | Описание |
| :- | :- |
| [`__init__(self, parent_immediate)`](/slides/python-net/ru/aspose.slides.charts/datalabel/__init__/#ichartdatapoint) | Создает новый экземпляр класса DataLabel. |

## Свойства

| Свойство | Описание |
| :- | :- |
| [`chart`](/slides/python-net/ru/aspose.slides.charts/datalabel/chart/) | Возвращает родительскую диаграмму.<br/>            Только чтение [`IChart`](/slides/python-net/ru/aspose.slides.charts/ichart). |
| [`is_visible`](/slides/python-net/ru/aspose.slides.charts/datalabel/is_visible/) | False означает, что подпись данных не видна (и поэтому все флаги Show*-flags (ShowValue, ...) равны false).<br/>            Только чтение **bool**. |
| [`text_frame_for_overriding`](/slides/python-net/ru/aspose.slides.charts/datalabel/text_frame_for_overriding/) | Может содержать форматированный текст. Если это свойство не None, то этот <br/>            форматированный текст переопределяет автоматически сгенерированный текст подписи данных.<br/>            Автоматически сгенерированный текст подписи данных — это текст, управляемый свойствами ShowSeriesName, <br/>            ShowValue, ... и форматируемый с помощью свойства TextFormatManager.TextFormat.<br/>            Только чтение [`ITextFrame`](/slides/python-net/ru/aspose.slides/itextframe). |
| [`text_format`](/slides/python-net/ru/aspose.slides.charts/datalabel/text_format/) | Возвращает формат текста.<br/>            Только чтение [`IChartTextFormat`](/slides/python-net/ru/aspose.slides.charts/icharttextformat). |
| [`x`](/slides/python-net/ru/aspose.slides.charts/datalabel/x/) | Возвращает или задает координату x заголовка как долю от ширины диаграммы.<br/>            Чтение/запись **float**. |
| [`y`](/slides/python-net/ru/aspose.slides.charts/datalabel/y/) | Возвращает или задает координату y заголовка как долю от высоты диаграммы.<br/>            Чтение/запись **float**. |
| [`width`](/slides/python-net/ru/aspose.slides.charts/datalabel/width/) | Возвращает или задает ширину заголовка как долю от ширины диаграммы.<br/>            Чтение/запись **float**. |
| [`height`](/slides/python-net/ru/aspose.slides.charts/datalabel/height/) | Возвращает или задает высоту заголовка как долю от высоты диаграммы.<br/>            Чтение/запись **float**. |
| [`right`](/slides/python-net/ru/aspose.slides.charts/datalabel/right/) | Справа.<br/>            Только чтение **float**. |
| [`bottom`](/slides/python-net/ru/aspose.slides.charts/datalabel/bottom/) | Снизу.<br/>            Только чтение **float**. |
| [`data_label_format`](/slides/python-net/ru/aspose.slides.charts/datalabel/data_label_format/) | Возвращает формат подписи данных.<br/>            Только чтение [`IDataLabelFormat`](/slides/python-net/ru/aspose.slides.charts/idatalabelformat). |
| [`value_from_cell`](/slides/python-net/ru/aspose.slides.charts/datalabel/value_from_cell/) | Получает или задает ячейку данных рабочей книги. Применяется, если свойство IDataLabelFormat.ShowLabelValueFromCell равно true. |
| [`actual_x`](/slides/python-net/ru/aspose.slides.charts/datalabel/actual_x/) | Указывает фактическое положение по оси x (слева) элемента диаграммы относительно левого верхнего угла диаграммы.<br/>            Вызовите метод IChart.ValidateChartLayout() перед получением фактических значений.<br/>            Чтение **float**. |
| [`actual_y`](/slides/python-net/ru/aspose.slides.charts/datalabel/actual_y/) | Указывает фактическую верхнюю границу элемента диаграммы относительно левого верхнего угла диаграммы.<br/>            Вызовите метод IChart.ValidateChartLayout() перед получением фактических значений.<br/>            Чтение **float**. |
| [`actual_width`](/slides/python-net/ru/aspose.slides.charts/datalabel/actual_width/) | Указывает фактическую ширину элемента диаграммы. Вызовите метод IChart.ValidateChartLayout() перед получением фактических значений.<br/>            Чтение **float**. |
| [`actual_height`](/slides/python-net/ru/aspose.slides.charts/datalabel/actual_height/) | Указывает фактическую высоту элемента диаграммы. Вызовите метод IChart.ValidateChartLayout() перед получением фактических значений.<br/>            Чтение **float**. |
| [`slide`](/slides/python-net/ru/aspose.slides.charts/datalabel/slide/) |  |
| [`presentation`](/slides/python-net/ru/aspose.slides.charts/datalabel/presentation/) |  |

## Методы

| Метод | Описание |
| :- | :- |
| [`hide(self)`](/slides/python-net/ru/aspose.slides.charts/datalabel/hide/#) | Скрывает подпись данных, установив все флаги Show*-flags (ShowValue, ...) в состояние false.<br/>            После этого IsVisible будет false. |
| [`get_actual_label_text(self)`](/slides/python-net/ru/aspose.slides.charts/datalabel/get_actual_label_text/#) | Возвращает фактический текст подписи на основе настроек DataLabelFormat или значения TextFrameForOverriding.Text. |
| [`add_text_frame_for_overriding(self, text)`](/slides/python-net/ru/aspose.slides.charts/datalabel/add_text_frame_for_overriding/#str) | Инициализирует TextFrameForOverriding текстом в параметре "text".<br/>            Если TextFrameForOverriding уже инициализирован, то просто меняет его текст. |


### См. также
* модуль [`aspose.slides.charts`](/slides/python-net/ru/aspose.slides.charts)
* библиотека [`Aspose.Slides`](/slides/python-net)