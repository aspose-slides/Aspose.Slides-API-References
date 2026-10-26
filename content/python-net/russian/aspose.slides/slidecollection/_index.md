---
title: SlideCollection class
second_title: Aspose.Slides для Python через .NET - справочник API
description: 
type: docs
url: /ru/aspose.slides/slidecollection/
---
## SlideCollection класс

Представляет коллекцию слайдов.

Тип SlideCollection предоставляет следующие члены:

Получает элемент по указанному индексу.
            Только для чтения [`Slide`](/slides/python-net/ru/aspose.slides/slide).

## Индексатор

| Имя | Описание |
| :- | :- |
| [`[index]`](/slides/python-net/ru/aspose.slides/slidecollection/__getitem__/) |  |

## Методы

| Метод | Описание |
| :- | :- |
| [`add_clone(self, source_slide)`](/slides/python-net/ru/aspose.slides/slidecollection/add_clone/#islide) | Добавляет копию указанного слайда в конец коллекции. |
| [`add_clone(self, source_slide, section)`](/slides/python-net/ru/aspose.slides/slidecollection/add_clone/#islide-isection) | Добавляет копию указанного слайда в конец указанного раздела. |
| [`add_clone(self, source_slide, dest_layout)`](/slides/python-net/ru/aspose.slides/slidecollection/add_clone/#islide-ilayoutslide) | Добавляет копию указанного слайда в конец коллекции. |
| [`add_clone(self, source_slide, dest_master, allow_clone_missing_layout)`](/slides/python-net/ru/aspose.slides/slidecollection/add_clone/#islide-imasterslide-bool) | Добавляет копию указанного исходного слайда в конец коллекции.<br/>            Подходящий макет будет выбран автоматически из указанного <br/>            мастер-шаблона (подходящий макет — это макет с тем же Type или Name, что <br/>            у макета исходного слайда). Если подходящий макет отсутствует, <br/>            макет исходного слайда будет клонирован (если allowCloneMissingLayout <br/>            равно true) или будет выброшено исключение PptxEditException (если allowCloneMissingLayout<br/>            равно false). |
| [`insert_clone(self, index, source_slide)`](/slides/python-net/ru/aspose.slides/slidecollection/insert_clone/#int-islide) | Вставляет копию указанного слайда в указанную позицию коллекции. |
| [`insert_clone(self, index, source_slide, dest_layout)`](/slides/python-net/ru/aspose.slides/slidecollection/insert_clone/#int-islide-ilayoutslide) | Вставляет копию указанного слайда в указанную позицию коллекции. |
| [`insert_clone(self, index, source_slide, dest_master, allow_clone_missing_layout)`](/slides/python-net/ru/aspose.slides/slidecollection/insert_clone/#int-islide-imasterslide-bool) | Вставляет копию указанного исходного слайда в указанную позицию коллекции.<br/>            Подходящий макет будет выбран автоматически из указанного <br/>            мастер-шаблона (подходящий макет — это макет с тем же Type или Name, что <br/>            у макета исходного слайда). Если подходящий макет отсутствует, <br/>            макет исходного слайда будет клонирован (если allowCloneMissingLayout <br/>            равно true) или будет выброшено исключение PptxEditException (если allowCloneMissingLayout<br/>            равно false). |
| [`to_array(self)`](/slides/python-net/ru/aspose.slides/slidecollection/to_array/#) | Создаёт и возвращает массив, содержащий все слайды. |
| [`to_array(self, start_index, count)`](/slides/python-net/ru/aspose.slides/slidecollection/to_array/#int-int) | Создаёт и возвращает массив со всеми слайдами из указанного диапазона.<br/>            Индекс первого слайда для добавления. Количество слайдов для добавления. |
| [`reorder(self, index, slide)`](/slides/python-net/ru/aspose.slides/slidecollection/reorder/#int-islide) | Перемещает слайд в коллекции в указанную позицию. |
| [`reorder(self, index, slides)`](/slides/python-net/ru/aspose.slides/slidecollection/reorder/#int-listislide) | Перемещает слайды в коллекции в указанную позицию.<br/>            Слайды будут размещены, начиная с индекса, в порядке их появления в списке. |
| [`add_from_pdf(self, path)`](/slides/python-net/ru/aspose.slides/slidecollection/add_from_pdf/#str) | Создаёт слайды из PDF-документа и добавляет их в конец коллекции. |
| [`add_from_pdf(self, path, pdf_import_options)`](/slides/python-net/ru/aspose.slides/slidecollection/add_from_pdf/#str-asposeslidesimportingpdfimportoptions) | Создаёт слайды из PDF-документа и добавляет их в конец коллекции с учётом параметров импорта PDF. |
| [`add_from_pdf(self, pdf_stream)`](/slides/python-net/ru/aspose.slides/slidecollection/add_from_pdf/#iorawiobase) | Создаёт слайды из PDF-документа и добавляет их в конец коллекции. |
| [`add_from_pdf(self, pdf_stream, pdf_import_options)`](/slides/python-net/ru/aspose.slides/slidecollection/add_from_pdf/#iorawiobase-asposeslidesimportingpdfimportoptions) | Создаёт слайды из PDF-документа и добавляет их в конец коллекции. |
| [`add_from_html(self, html_text, resolver, uri)`](/slides/python-net/ru/aspose.slides/slidecollection/add_from_html/#str-asposeslidesimportingiexternalresourceresolver-str) | Создаёт слайды из HTML-текста и добавляет их в конец коллекции. |
| [`add_from_html(self, html_text)`](/slides/python-net/ru/aspose.slides/slidecollection/add_from_html/#str) | Создаёт слайды из HTML-текста и добавляет их в конец коллекции. |
| [`add_from_html(self, html_stream, resolver, uri)`](/slides/python-net/ru/aspose.slides/slidecollection/add_from_html/#iorawiobase-asposeslidesimportingiexternalresourceresolver-str) | Создаёт слайды из HTML-текста и добавляет их в конец коллекции. |
| [`add_from_html(self, html_stream)`](/slides/python-net/ru/aspose.slides/slidecollection/add_from_html/#iorawiobase) | Создаёт слайды из HTML-текста и добавляет их в конец коллекции. |
| [`insert_from_html(self, index, html_text, resolver, uri)`](/slides/python-net/ru/aspose.slides/slidecollection/insert_from_html/#int-str-asposeslidesimportingiexternalresourceresolver-str) | Создаёт слайды из HTML-текста и вставляет их в коллекцию в указанную позицию. |
| [`insert_from_html(self, index, html_text, resolver, uri, use_slide_with_index_as_start)`](/slides/python-net/ru/aspose.slides/slidecollection/insert_from_html/#int-str-asposeslidesimportingiexternalresourceresolver-str-bool) | Создаёт слайды из HTML-текста и вставляет их в коллекцию в указанную позицию. |
| [`insert_from_html(self, index, html_text)`](/slides/python-net/ru/aspose.slides/slidecollection/insert_from_html/#int-str) | Создаёт слайды из HTML-текста и вставляет их в коллекцию в указанную позицию. |
| [`insert_from_html(self, index, html_text, use_slide_with_index_as_start)`](/slides/python-net/ru/aspose.slides/slidecollection/insert_from_html/#int-str-bool) | Создаёт слайды из HTML-текста и вставляет их в коллекцию в указанную позицию. |
| [`insert_from_html(self, index, html_stream, resolver, uri)`](/slides/python-net/ru/aspose.slides/slidecollection/insert_from_html/#int-iorawiobase-asposeslidesimportingiexternalresourceresolver-str) | Создаёт слайды из HTML-текста и вставляет их в коллекцию в указанную позицию. |
| [`insert_from_html(self, index, html_stream, resolver, uri, use_slide_with_index_as_start)`](/slides/python-net/ru/aspose.slides/slidecollection/insert_from_html/#int-iorawiobase-asposeslidesimportingiexternalresourceresolver-str-bool) | Создаёт слайды из HTML-текста и вставляет их в коллекцию в указанную позицию. |
| [`insert_from_html(self, index, html_stream)`](/slides/python-net/ru/aspose.slides/slidecollection/insert_from_html/#int-iorawiobase) | Создаёт слайды из HTML-текста и вставляет их в коллекцию в указанную позицию. |
| [`insert_from_html(self, index, html_stream, use_slide_with_index_as_start)`](/slides/python-net/ru/aspose.slides/slidecollection/insert_from_html/#int-iorawiobase-bool) | Создаёт слайды из HTML-текста и вставляет их в коллекцию в указанную позицию. |
| [`add_empty_slide(self, layout)`](/slides/python-net/ru/aspose.slides/slidecollection/add_empty_slide/#ilayoutslide) | Добавляет новый пустой слайд в конец коллекции. |
| [`insert_empty_slide(self, index, layout)`](/slides/python-net/ru/aspose.slides/slidecollection/insert_empty_slide/#int-ilayoutslide) | Вставляет копию указанного слайда в указанную позицию коллекции. |
| [`remove(self, value)`](/slides/python-net/ru/aspose.slides/slidecollection/remove/#islide) | Удаляет первое вхождение указанного объекта из коллекции. |
| [`remove_at(self, index)`](/slides/python-net/ru/aspose.slides/slidecollection/remove_at/#int) | Удаляет элемент по указанному индексу из коллекции. |
| [`index_of(self, slide)`](/slides/python-net/ru/aspose.slides/slidecollection/index_of/#islide) | Возвращает индекс указанного слайда в коллекции. |


### См. также
* класс [`Slide`](/slides/python-net/ru/aspose.slides/slide)
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* библиотека [`Aspose.Slides`](/slides/python-net)