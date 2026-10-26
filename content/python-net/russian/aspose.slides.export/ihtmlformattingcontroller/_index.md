---
title: IHtmlFormattingController class
second_title: Aspose.Slides для Python через .NET Справочник API
description: 
type: docs
url: /ru/aspose.slides.export/ihtmlformattingcontroller/
---
## IHtmlFormattingController класс

Контролирует генерацию html-файла.

Тип IHtmlFormattingController предоставляет следующие члены:

## Методы

| Метод | Описание |
| :- | :- |
| [`write_document_start(self, generator, presentation)`](/slides/python-net/ru/aspose.slides.export/ihtmlformattingcontroller/write_document_start/#ihtmlgenerator-ipresentation) | Вызывается для записи заголовка html-документа. Вызывается один раз за конвертацию презентации. |
| [`write_document_end(self, generator, presentation)`](/slides/python-net/ru/aspose.slides.export/ihtmlformattingcontroller/write_document_end/#ihtmlgenerator-ipresentation) | Вызывается для записи нижнего колонтитула html-документа. Вызывается один раз за конвертацию презентации. |
| [`write_slide_start(self, generator, slide)`](/slides/python-net/ru/aspose.slides.export/ihtmlformattingcontroller/write_slide_start/#ihtmlgenerator-islide) | Вызывается для записи заголовка html-слайда. Вызывается один раз для каждого слайда. |
| [`write_slide_end(self, generator, slide)`](/slides/python-net/ru/aspose.slides.export/ihtmlformattingcontroller/write_slide_end/#ihtmlgenerator-islide) | Вызывается для записи нижнего колонтитула html-слайда. Вызывается один раз для каждого слайда. |
| [`write_shape_start(self, generator, shape)`](/slides/python-net/ru/aspose.slides.export/ihtmlformattingcontroller/write_shape_start/#ihtmlgenerator-ishape) | Вызывается перед отрисовкой формы. Вызывается один раз для каждой формы. Если эта функция что-то записывает в генератор, текущая генерация изображения слайда будет завершена, добавленный html-фрагмент будет вставлен и новое изображение будет начато поверх предыдущего. |
| [`write_shape_end(self, generator, shape)`](/slides/python-net/ru/aspose.slides.export/ihtmlformattingcontroller/write_shape_end/#ihtmlgenerator-ishape) | Вызывается перед отрисовкой формы. Вызывается один раз для каждой формы. Если эта функция что-то записывает в генератор, текущая генерация изображения слайда будет завершена, добавленный html-фрагмент будет вставлен и новое изображение будет начато поверх предыдущего. |

### Смотрите также
* модуль [`aspose.slides.export`](/slides/python-net/ru/aspose.slides.export)
* библиотека [`Aspose.Slides`](/slides/python-net)