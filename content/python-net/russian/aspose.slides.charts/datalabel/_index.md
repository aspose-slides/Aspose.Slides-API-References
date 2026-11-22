---
title: DataLabel class
second_title: Aspose.Slides для Python через .NET справочник API
description: 
type: docs
url: /ru/aspose.slides.charts/datalabel/
---
## Класс DataLabel

Представляет метки серии.

Тип DataLabel раскрывает следующие члены:

## Конструкторы

| Конструктор | Описание |
| :- | :- |
| [`__init__(self, parent_immediate)`](/slides/python-net/ru/aspose.slides.charts/datalabel/__init__/#ichartdatapoint) | Создаёт новый экземпляр класса DataLabel. |

## Свойства

| Свойство | Описание |
| :- | :- |
| [`chart`](/slides/python-net/ru/aspose.slides.charts/datalabel/chart/) | Возвращает родительскую диаграмму.<br/>            Только для чтения [`IChart`](/slides/python-net/ru/aspose.slides.charts/ichart). |
| [`is_visible`](/slides/python-net/ru/aspose.slides.charts/datalabel/is_visible/) | Значение False означает, что метка данных не видна (и поэтому все флаги Show*- (ShowValue, ...) также False).<br/>            Только для чтения **bool**. |
| [`text_frame_for_overriding`](/slides/python-net/ru/aspose.slides.charts/datalabel/text_frame_for_overriding/) | Может содержать текст с богатым форматированием. Если это свойство не None, то это <br/>            значение отформатированного текста переопределяет автоматически сгенерированный текст метки данных.<br/>            Автосгенерированный текст метки данных — это текст, управляемый свойствами ShowSeriesName, <br/>            ShowValue, ... и форматируемый с помощью свойства TextFormatManager.TextFormat.<br/>            Только для чтения [`ITextFrame`](/slides/python-net/ru/aspose.slides/itextframe). |
| [`text_format`](/slides/python-net/ru/aspose.slides.charts/datalabel/text_format/) | Возвращает формат текста.<br/>            Только для чтения [`IChartTextFormat`](/slides/python-net/ru/aspose.slides.charts/icharttextformat). |
| [`x`](/slides/python-net/ru/aspose.slides.charts/datalabel/x/) | Возвращает или задаёт координату x заголовка как долю ширины диаграммы.<br/>            Чтение/запись **float**. |
| [`y`](/slides/python-net/ru/aspose.slides.charts/datalabel/y/) | Возвращает или задаёт координату y заголовка как долю высоты диаграммы.<br/>            Чтение/запись **float**. |
| [`width`](/slides/python-net/ru/aspose.slides.charts/datalabel/width/) | Возвращает или задаёт ширину заголовка как долю ширины диаграммы.<br/>            Чтение/запись **float**. |
| [`height`](/slides/python-net/ru/aspose.slides.charts/datalabel/height/) | Возвращает или задаёт высоту заголовка как долю высоты диаграммы.<br/>            Чтение/запись **float**. |
| [`right`](/slides/python-net/ru/aspose.slides.charts/datalabel/right/) | Справа.<br/>            Только для чтения **float**. |
| [`bottom`](/slides/python-net/ru/aspose.slides.charts/datalabel/bottom/) | Снизу.<br/>            Только для чтения **float**. |
| [`data_label_format`](/slides/python-net/ru/aspose.slides.charts/datalabel/data_label_format/) | Возвращает формат метки данных.<br/>            Только для чтения [`IDataLabelFormat`](/slides/python-net/ru/aspose.slides.charts/idatalabelformat). |
| [`value_from_cell`](/slides/python-net/ru/aspose.slides.charts/datalabel/value_from_cell/) | Получает или задаёт ячейку данных рабочей книги. Применяется, если свойство IDataLabelFormat.ShowLabelValueFromCell равно true. |
| [`label_shape_type`](/slides/python-net/ru/aspose.slides.charts/datalabel/label_shape_type/) | Получает или задаёт тип фигуры метки данных.<br/>             Возвращает [`ShapeType.NOT_DEFINED`](/slides/python-net/ru/aspose.slides/shapetype/NOT_DEFINED) если фигура не определена. |
| [`actual_x`](/slides/python-net/ru/aspose.slides.charts/datalabel/actual_x/) | Указывает фактическое расположение по оси x (слева) элемента диаграммы относительно левого верхнего угла диаграммы.<br/>            Вызовите метод IChart.ValidateChartLayout() перед получением фактических значений. <br/>            Чтение **float**. |
| [`actual_y`](/slides/python-net/ru/aspose.slides.charts/datalabel/actual_y/) | Указывает фактическую верхнюю позицию элемента диаграммы относительно левого верхнего угла диаграммы.<br/>            Вызовите метод IChart.ValidateChartLayout() перед получением фактических значений. <br/>            Чтение **float**. |
| [`actual_width`](/slides/python-net/ru/aspose.slides.charts/datalabel/actual_width/) | Указывает фактическую ширину элемента диаграммы. Вызовите метод IChart.ValidateChartLayout() перед получением фактических значений. <br/>            Чтение **float**. |
| [`actual_height`](/slides/python-net/ru/aspose.slides.charts/datalabel/actual_height/) | Указывает фактическую высоту элемента диаграммы. Вызовите метод IChart.ValidateChartLayout() перед получением фактических значений. <br/>            Чтение **float**. |
| [`slide`](/slides/python-net/ru/aspose.slides.charts/datalabel/slide/) |  |
| [`presentation`](/slides/python-net/ru/aspose.slides.charts/datalabel/presentation/) |  |

## Методы

| Метод | Описание |
| :- | :- |
| [`hide(self)`](/slides/python-net/ru/aspose.slides.charts/datalabel/hide/#) | Скрывает метку данных, устанавливая все флаги Show*- (ShowValue, ...) в состояние false.<br/>            После этого IsVisible будет false. |
| [`get_actual_label_text(self)`](/slides/python-net/ru/aspose.slides.charts/datalabel/get_actual_label_text/#) | Возвращает фактический текст метки на основе настроек DataLabelFormat или значения TextFrameForOverriding.Text. |
| [`add_text_frame_for_overriding(self, text)`](/slides/python-net/ru/aspose.slides.charts/datalabel/add_text_frame_for_overriding/#str) | Инициализирует TextFrameForOverriding текстом из параметра "text".<br/>            Если TextFrameForOverriding уже инициализирован, то просто меняет его текст. |

### См. также
* модуль [`aspose.slides.charts`](/slides/python-net/ru/aspose.slides.charts)
* библиотека [`Aspose.Slides`](/slides/python-net)