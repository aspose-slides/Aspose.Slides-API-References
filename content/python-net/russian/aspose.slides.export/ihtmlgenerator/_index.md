---
title: IHtmlGenerator class
second_title: Aspose.Slides для Python через .NET справочник API
description: 
type: docs
url: /ru/aspose.slides.export/ihtmlgenerator/
---
## IHtmlGenerator class

Генератор HTML.

Тип IHtmlGenerator раскрывает следующие члены:

## Свойства

| Свойство | Описание |
| :- | :- |
| [`slide_image_size`](/slides/python-net/ru/aspose.slides.export/ihtmlgenerator/slide_image_size/) | Возвращает размер изображения слайда.<br/>            Только для чтения [`SizeF`](/slides/python-net/ru/aspose.slides/sizef). |
| [`slide_image_size_unit`](/slides/python-net/ru/aspose.slides.export/ihtmlgenerator/slide_image_size_unit/) | Возвращает единицу измерения, в которой задается размер изображения слайда.<br/>            Только для чтения [`SvgCoordinateUnit`](/slides/python-net/ru/aspose.slides.export/svgcoordinateunit). |
| [`slide_image_size_unit_code`](/slides/python-net/ru/aspose.slides.export/ihtmlgenerator/slide_image_size_unit_code/) | Возвращает css-код единицы измерения, в которой задается размер изображения слайда.<br/>            Только для чтения **str**. |
| [`previous_slide_index`](/slides/python-net/ru/aspose.slides.export/ihtmlgenerator/previous_slide_index/) | Возвращает индекс ранее отрисованного слайда или -1, если отрисовывается первый слайд.<br/>            Только для чтения **int**. |
| [`slide_index`](/slides/python-net/ru/aspose.slides.export/ihtmlgenerator/slide_index/) | Возвращает индекс текущего отрисовываемого слайда.<br/>            Только для чтения **int**. |
| [`next_slide_index`](/slides/python-net/ru/aspose.slides.export/ihtmlgenerator/next_slide_index/) | Возвращает индекс слайда, который будет отрисован после текущего, или -1, если текущий слайд является последним.<br/>            Только для чтения **int**. |

## Методы

| Метод | Описание |
| :- | :- |
| [`add_html(self, html)`](/slides/python-net/ru/aspose.slides.export/ihtmlgenerator/add_html/#str) | Добавляет отформатированный HTML-текст. |
| [`add_html(self, html)`](/slides/python-net/ru/aspose.slides.export/ihtmlgenerator/add_html/#listchar) | Добавляет отформатированный HTML-текст. |
| [`add_html(self, html, start_index, length)`](/slides/python-net/ru/aspose.slides.export/ihtmlgenerator/add_html/#listchar-int-int) | Добавляет отформатированный HTML-текст. |
| [`add_text(self, text)`](/slides/python-net/ru/aspose.slides.export/ihtmlgenerator/add_text/#str) | Добавляет простой текст в HTML-файлы, заменяя специальные символы HTML-сущностями.<br/>            Разрывы строк и пробелы не заменяются. |
| [`add_text(self, text)`](/slides/python-net/ru/aspose.slides.export/ihtmlgenerator/add_text/#listchar) | Добавляет простой текст в HTML-файлы, заменяя специальные символы HTML-сущностями.<br/>            Разрывы строк и пробелы не заменяются. |
| [`add_text(self, text, start_index, length)`](/slides/python-net/ru/aspose.slides.export/ihtmlgenerator/add_text/#listchar-int-int) | Добавляет простой текст в HTML-файлы, заменяя специальные символы HTML-сущностями.<br/>            Разрывы строк и пробелы не заменяются. |
| [`add_attribute_value(self, value)`](/slides/python-net/ru/aspose.slides.export/ihtmlgenerator/add_attribute_value/#str) | Экранирует значение атрибута и добавляет его в HTML-файл. |
| [`add_attribute_value(self, value)`](/slides/python-net/ru/aspose.slides.export/ihtmlgenerator/add_attribute_value/#listchar) | Экранирует значение атрибута и добавляет его в HTML-файл. |
| [`add_attribute_value(self, value, start_index, length)`](/slides/python-net/ru/aspose.slides.export/ihtmlgenerator/add_attribute_value/#listchar-int-int) | Экранирует значение атрибута и добавляет его в HTML-файл. |

### См. также
* модуль [`aspose.slides.export`](/slides/python-net/ru/aspose.slides.export)
* библиотека [`Aspose.Slides`](/slides/python-net)