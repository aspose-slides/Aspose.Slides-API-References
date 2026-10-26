---
title: HtmlGenerator class
second_title: Aspose.Slides для Python через .NET API справочник
description: 
type: docs
url: /ru/aspose.slides.export/htmlgenerator/
---
## HtmlGenerator класс

Генератор HTML.

Тип HtmlGenerator раскрывает следующие члены:

## Свойства

| Свойство | Описание |
| :- | :- |
| [`slide_image_size`](/slides/python-net/ru/aspose.slides.export/htmlgenerator/slide_image_size/) | Returns slide image size.<br/>            Тoлько для чтения [`SizeF`](/slides/python-net/ru/aspose.slides/sizef). |
| [`slide_image_size_unit`](/slides/python-net/ru/aspose.slides.export/htmlgenerator/slide_image_size_unit/) | Returns a unit in which slide image size is specified.<br/>            Тoлько для чтения [`SvgCoordinateUnit`](/slides/python-net/ru/aspose.slides.export/svgcoordinateunit). |
| [`slide_image_size_unit_code`](/slides/python-net/ru/aspose.slides.export/htmlgenerator/slide_image_size_unit_code/) | Returns a css code of unit in which slide image size is specified.<br/>            Тoлько для чтения **str**. |
| [`previous_slide_index`](/slides/python-net/ru/aspose.slides.export/htmlgenerator/previous_slide_index/) | Returns index of previously rendered slide or -1 if first slide is rendering.<br/>            Тoлько для чтения **int**. |
| [`slide_index`](/slides/python-net/ru/aspose.slides.export/htmlgenerator/slide_index/) | Returns index of currently rendering slide.<br/>            Тoлько для чтения **int**. |
| [`next_slide_index`](/slides/python-net/ru/aspose.slides.export/htmlgenerator/next_slide_index/) | Returns index of a slide, which will be rendered after the current slide or -1 if currently rendering last slide.<br/>            Тoлько для чтения **int**. |

## Методы

| Метод | Описание |
| :- | :- |
| [`add_html(self, html)`](/slides/python-net/ru/aspose.slides.export/htmlgenerator/add_html/#str) | Добавляет отформатированный HTML-текст. |
| [`add_html(self, html)`](/slides/python-net/ru/aspose.slides.export/htmlgenerator/add_html/#listchar) | Добавляет отформатированный HTML-текст. |
| [`add_html(self, html, start_index, length)`](/slides/python-net/ru/aspose.slides.export/htmlgenerator/add_html/#listchar-int-int) | Добавляет отформатированный HTML-текст. |
| [`add_text(self, text)`](/slides/python-net/ru/aspose.slides.export/htmlgenerator/add_text/#str) | Добавляет обычный текст в файлы HTML, заменяя специальные символы на HTML-сущности.<br/>            Переводы строк и пробелы не заменяются. |
| [`add_text(self, text)`](/slides/python-net/ru/aspose.slides.export/htmlgenerator/add_text/#listchar) | Добавляет обычный текст в файлы HTML, заменяя специальные символы на HTML-сущности.<br/>            Переводы строк и пробелы не заменяются. |
| [`add_text(self, text, start_index, length)`](/slides/python-net/ru/aspose.slides.export/htmlgenerator/add_text/#listchar-int-int) | Добавляет обычный текст в файлы HTML, заменяя специальные символы на HTML-сущности.<br/>            Переводы строк и пробелы не заменяются. |
| [`add_attribute_value(self, value)`](/slides/python-net/ru/aspose.slides.export/htmlgenerator/add_attribute_value/#str) | Экранирует значение атрибута и добавляет его в файл HTML. |
| [`add_attribute_value(self, value)`](/slides/python-net/ru/aspose.slides.export/htmlgenerator/add_attribute_value/#listchar) | Экранирует значение атрибута и добавляет его в файл HTML. |
| [`add_attribute_value(self, value, start_index, length)`](/slides/python-net/ru/aspose.slides.export/htmlgenerator/add_attribute_value/#listchar-int-int) | Экранирует значение атрибута и добавляет его в файл HTML. |


### См. также
* модуль [`aspose.slides.export`](/slides/python-net/ru/aspose.slides.export)
* библиотека [`Aspose.Slides`](/slides/python-net)