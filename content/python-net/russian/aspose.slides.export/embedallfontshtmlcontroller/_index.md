---
title: EmbedAllFontsHtmlController class
second_title: Справочник API Aspose.Slides для Python через .NET
description: 
type: docs
url: /ru/aspose.slides.export/embedallfontshtmlcontroller/
---
## EmbedAllFontsHtmlController класс

Класс контроллера форматирования, используемый для встраивания всех шрифтов презентации в формате WOFF.

Тип EmbedAllFontsHtmlController содержит следующие члены:

## Конструкторы

| Конструктор | Описание |
| :- | :- |
| [`__init__(self)`](/slides/python-net/ru/aspose.slides.export/embedallfontshtmlcontroller/__init__/#) | Создает новый экземпляр |
| [`__init__(self, font_name_exclude_list)`](/slides/python-net/ru/aspose.slides.export/embedallfontshtmlcontroller/__init__/#liststr) | Создает новый экземпляр |

## Методы

| Метод | Описание |
| :- | :- |
| [`write_document_start(self, generator, presentation)`](/slides/python-net/ru/aspose.slides.export/embedallfontshtmlcontroller/write_document_start/#ihtmlgenerator-ipresentation) | Вызывается для записи заголовка HTML-документа. Вызывается один раз для каждой конвертации презентации. |
| [`write_document_end(self, generator, presentation)`](/slides/python-net/ru/aspose.slides.export/embedallfontshtmlcontroller/write_document_end/#ihtmlgenerator-ipresentation) | Вызывается для записи нижнего колонтитула HTML-документа. Вызывается один раз для каждой конвертации презентации. |
| [`write_slide_start(self, generator, slide)`](/slides/python-net/ru/aspose.slides.export/embedallfontshtmlcontroller/write_slide_start/#ihtmlgenerator-islide) | Вызывается для записи заголовка HTML-слайда. Вызывается один раз для каждого слайда. |
| [`write_slide_end(self, generator, slide)`](/slides/python-net/ru/aspose.slides.export/embedallfontshtmlcontroller/write_slide_end/#ihtmlgenerator-islide) | Вызывается для записи нижнего колонтитула HTML-слайда. Вызывается один раз для каждого слайда. |
| [`write_shape_start(self, generator, shape)`](/slides/python-net/ru/aspose.slides.export/embedallfontshtmlcontroller/write_shape_start/#ihtmlgenerator-ishape) | Вызывается перед отрисовкой shape. Вызывается один раз для каждой shape. Если эта функция записывает что-либо в генератор, текущая генерация изображения слайда будет завершена, добавленный HTML-фрагмент будет вставлен, и новое изображение начнётся поверх предыдущего. |
| [`write_shape_end(self, generator, shape)`](/slides/python-net/ru/aspose.slides.export/embedallfontshtmlcontroller/write_shape_end/#ihtmlgenerator-ishape) | Вызывается перед отрисовкой shape. Вызывается один раз для каждой shape. Если эта функция записывает что-либо в генератор, текущая генерация изображения слайда будет завершена, добавленный HTML-фрагмент будет вставлен, и новое изображение начнётся поверх предыдущего. |
| [`write_all_fonts(self, generator, presentation)`](/slides/python-net/ru/aspose.slides.export/embedallfontshtmlcontroller/write_all_fonts/#ihtmlgenerator-ipresentation) | Записать все шрифты, содержащиеся в [`Presentation`](/slides/python-net/ru/aspose.slides/presentation). |
| [`write_font(self, generator, original_font, substituted_font, font_style, font_weight, font_data)`](/slides/python-net/ru/aspose.slides.export/embedallfontshtmlcontroller/write_font/#ihtmlgenerator-ifontdata-ifontdata-str-str-bytes) | Записывает данные в формате base64 непосредственно в HTML-документ. |

### Смотрите также
* модуль [`aspose.slides.export`](/slides/python-net/ru/aspose.slides.export)
* библиотека [`Aspose.Slides`](/slides/python-net)