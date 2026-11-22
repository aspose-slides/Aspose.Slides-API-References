---
title: IDataLabel class
second_title: Aspose.Slides для Python через .NET API Reference
description: 
type: docs
url: /ru/aspose.slides.charts/idatalabel/
---
## IDataLabel класс

Представляет метки серии.

Тип IDataLabel раскрывает следующие члены:

## Свойства

| Свойство | Описание |
| :- | :- |
| [`is_visible`](/slides/python-net/ru/aspose.slides.charts/idatalabel/is_visible/) | False означает, что метка данных не видна (и поэтому все флаги Show*-flags (ShowValue, ...) тоже false).<br/>            Только для чтения **bool**. |
| [`data_label_format`](/slides/python-net/ru/aspose.slides.charts/idatalabel/data_label_format/) | Возвращает формат метки данных.<br/>            Только для чтения [`IDataLabelFormat`](/slides/python-net/ru/aspose.slides.charts/idatalabelformat). |
| [`value_from_cell`](/slides/python-net/ru/aspose.slides.charts/idatalabel/value_from_cell/) | Получает или задает ячейку данных книги. Применяется, если свойство IDataLabelFormat.ShowLabelValueFromCell равно true. |
| [`label_shape_type`](/slides/python-net/ru/aspose.slides.charts/idatalabel/label_shape_type/) | Получает или задает тип фигуры метки данных.<br/>            Возвращает [`ShapeType.NOT_DEFINED`](/slides/python-net/ru/aspose.slides/shapetype/NOT_DEFINED), если фигура не определена. |
| [`x`](/slides/python-net/ru/aspose.slides.charts/idatalabel/x/) |  |
| [`y`](/slides/python-net/ru/aspose.slides.charts/idatalabel/y/) |  |
| [`width`](/slides/python-net/ru/aspose.slides.charts/idatalabel/width/) |  |
| [`height`](/slides/python-net/ru/aspose.slides.charts/idatalabel/height/) |  |
| [`right`](/slides/python-net/ru/aspose.slides.charts/idatalabel/right/) |  |
| [`bottom`](/slides/python-net/ru/aspose.slides.charts/idatalabel/bottom/) |  |
| [`chart`](/slides/python-net/ru/aspose.slides.charts/idatalabel/chart/) |  |
| [`slide`](/slides/python-net/ru/aspose.slides.charts/idatalabel/slide/) |  |
| [`presentation`](/slides/python-net/ru/aspose.slides.charts/idatalabel/presentation/) |  |
| [`text_frame_for_overriding`](/slides/python-net/ru/aspose.slides.charts/idatalabel/text_frame_for_overriding/) |  |
| [`text_format`](/slides/python-net/ru/aspose.slides.charts/idatalabel/text_format/) |  |
| [`actual_x`](/slides/python-net/ru/aspose.slides.charts/idatalabel/actual_x/) |  |
| [`actual_y`](/slides/python-net/ru/aspose.slides.charts/idatalabel/actual_y/) |  |
| [`actual_width`](/slides/python-net/ru/aspose.slides.charts/idatalabel/actual_width/) |  |
| [`actual_height`](/slides/python-net/ru/aspose.slides.charts/idatalabel/actual_height/) |  |

## Методы

| Метод | Описание |
| :- | :- |
| [`hide(self)`](/slides/python-net/ru/aspose.slides.charts/idatalabel/hide/#) | Скрывает метку данных, устанавливая все флаги Show*-flags (ShowValue, ...) в состояние false.<br/>            После этого IsVisible будет false. |
| [`get_actual_label_text(self)`](/slides/python-net/ru/aspose.slides.charts/idatalabel/get_actual_label_text/#) | Возвращает фактический текст метки на основе настроек DataLabelFormat или значения TextFrameForOverriding.Text. |
| [`add_text_frame_for_overriding(self, text)`](/slides/python-net/ru/aspose.slides.charts/idatalabel/add_text_frame_for_overriding/#str) |  |

### См. также
* модуль [`aspose.slides.charts`](/slides/python-net/ru/aspose.slides.charts)
* библиотека [`Aspose.Slides`](/slides/python-net)