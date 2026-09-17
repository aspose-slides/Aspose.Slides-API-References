---
title: ISlideCollection class
second_title: Aspose.Slides для Python через .NET справочник API
description: 
type: docs
url: /ru/aspose.slides/islidecollection/
---
## ISlideCollection класс

Представляет коллекцию слайдов.

Тип ISlideCollection раскрывает следующие члены:

Получает элемент по указанному индексу.
Только для чтения [`ISlide`](/slides/python-net/ru/aspose.slides/islide).

## Индексатор

| Имя | Описание |
| :- | :- |
| [`[index]`](/slides/python-net/ru/aspose.slides/islidecollection/__getitem__/) |  |

## Методы

| Метод | Описание |
| :- | :- |
| [`add_clone(self, source_slide)`](/slides/python-net/ru/aspose.slides/islidecollection/add_clone/#islide) | Добавляет копию указанного слайда в конец коллекции. |
| [`add_clone(self, source_slide, section)`](/slides/python-net/ru/aspose.slides/islidecollection/add_clone/#islide-isection) | Добавляет копию указанного слайда в конец указанного раздела. |
| [`add_clone(self, source_slide, dest_layout)`](/slides/python-net/ru/aspose.slides/islidecollection/add_clone/#islide-ilayoutslide) | Добавляет копию указанного слайда в конец коллекции. |
| [`add_clone(self, source_slide, dest_master, allow_clone_missing_layout)`](/slides/python-net/ru/aspose.slides/islidecollection/add_clone/#islide-imasterslide-bool) | Добавляет копию указанного исходного слайда в конец коллекции.<br/>Подходящий макет будет выбран автоматически из указанного мастера (подходящий макет — это макет с тем же типом или именем, что и макет исходного слайда). Если подходящий макет отсутствует, то макет исходного слайда будет клонирован (если allowCloneMissingLayout истинно) или будет выброшено PptxEditException (если allowCloneMissingLayout ложно). |
| [`insert_clone(self, index, source_slide)`](/slides/python-net/ru/aspose.slides/islidecollection/insert_clone/#int-islide) | Вставляет копию указанного слайда в указанную позицию коллекции. |
| [`insert_clone(self, index, source_slide, dest_layout)`](/slides/python-net/ru/aspose.slides/islidecollection/insert_clone/#int-islide-ilayoutslide) | Вставляет копию указанного слайда в указанную позицию коллекции. |
| [`insert_clone(self, index, source_slide, dest_master, allow_clone_missing_layout)`](/slides/python-net/ru/aspose.slides/islidecollection/insert_clone/#int-islide-imasterslide-bool) | Вставляет копию указанного исходного слайда в указанную позицию коллекции.<br/>Подходящий макет будет выбран автоматически из указанного мастера (подходящий макет — это макет с тем же типом или именем, что и макет исходного слайда). Если подходящий макет отсутствует, то макет исходного слайда будет клонирован (если allowCloneMissingLayout истинно) или будет выброшено PptxEditException (если allowCloneMissingLayout ложно). |
| [`to_array(self)`](/slides/python-net/ru/aspose.slides/islidecollection/to_array/#) | Создаёт и возвращает массив со всеми слайдами. |
| [`to_array(self, start_index, count)`](/slides/python-net/ru/aspose.slides/islidecollection/to_array/#int-int) | Создаёт и возвращает массив со всеми слайдами из указанного диапазона. |
| [`reorder(self, index, slide)`](/slides/python-net/ru/aspose.slides/islidecollection/reorder/#int-islide) | Перемещает слайд из коллекции в указанную позицию. |
| [`reorder(self, index, slides)`](/slides/python-net/ru/aspose.slides/islidecollection/reorder/#int-listislide) | Перемещает слайды из коллекции в указанную позицию.<br/>Слайды будут размещены, начиная с индекса, в том порядке, в котором они находятся в списке. |
| [`add_from_pdf(self, path)`](/slides/python-net/ru/aspose.slides/islidecollection/add_from_pdf/#str) | Создаёт слайды из PDF-документа и добавляет их в конец коллекции. |
| [`add_from_pdf(self, path, pdf_import_options)`](/slides/python-net/ru/aspose.slides/islidecollection/add_from_pdf/#str-asposeslidesimportingpdfimportoptions) | Создаёт слайды из PDF-документа и добавляет их в конец коллекции с учётом параметров импорта PDF. |
| [`add_from_pdf(self, pdf_stream, pdf_import_options)`](/slides/python-net/ru/aspose.slides/islidecollection/add_from_pdf/#iorawiobase-asposeslidesimportingpdfimportoptions) | Создаёт слайды из PDF-документа и добавляет их в конец коллекции. |
| [`add_from_pdf(self, pdf_stream)`](/slides/python-net/ru/aspose.slides/islidecollection/add_from_pdf/#iorawiobase) | Создаёт слайды из PDF-документа и добавляет их в конец коллекции. |
| [`add_from_html(self, html_text, resolver, uri)`](/slides/python-net/ru/aspose.slides/islidecollection/add_from_html/#str-asposeslidesimportingiexternalresourceresolver-str) | Создаёт слайды из HTML-текста и добавляет их в конец коллекции. |
| [`add_from_html(self, html_text)`](/slides/python-net/ru/aspose.slides/islidecollection/add_from_html/#str) | Создаёт слайды из HTML-текста и добавляет их в конец коллекции. |
| [`add_from_html(self, html_stream, resolver, uri)`](/slides/python-net/ru/aspose.slides/islidecollection/add_from_html/#iorawiobase-asposeslidesimportingiexternalresourceresolver-str) | Создаёт слайды из HTML-текста и добавляет их в конец коллекции. |
| [`add_from_html(self, html_stream)`](/slides/python-net/ru/aspose.slides/islidecollection/add_from_html/#iorawiobase) | Создаёт слайды из HTML-текста и добавляет их в конец коллекции. |
| [`insert_from_html(self, index, html_text, resolver, uri)`](/slides/python-net/ru/aspose.slides/islidecollection/insert_from_html/#int-str-asposeslidesimportingiexternalresourceresolver-str) | Создаёт слайды из HTML-текста и вставляет их в коллекцию в указанную позицию. |
| [`insert_from_html(self, index, html_text)`](/slides/python-net/ru/aspose.slides/islidecollection/insert_from_html/#int-str) | Создаёт слайды из HTML-текста и вставляет их в коллекцию в указанную позицию. |
| [`insert_from_html(self, index, html_stream, resolver, uri)`](/slides/python-net/ru/aspose.slides/islidecollection/insert_from_html/#int-iorawiobase-asposeslidesimportingiexternalresourceresolver-str) | Создаёт слайды из HTML-текста и вставляет их в коллекцию в указанную позицию. |
| [`insert_from_html(self, index, html_stream)`](/slides/python-net/ru/aspose.slides/islidecollection/insert_from_html/#int-iorawiobase) | Создаёт слайды из HTML-текста и вставляет их в коллекцию в указанную позицию. |
| [`insert_from_html(self, index, html_text, use_slide_with_index_as_start)`](/slides/python-net/ru/aspose.slides/islidecollection/insert_from_html/#int-str-bool) | Создаёт слайды из HTML-текста и вставляет их в коллекцию в указанную позицию. |
| [`insert_from_html(self, index, html_text, resolver, uri, use_slide_with_index_as_start)`](/slides/python-net/ru/aspose.slides/islidecollection/insert_from_html/#int-str-asposeslidesimportingiexternalresourceresolver-str-bool) | Создаёт слайды из HTML-текста и вставляет их в коллекцию в указанную позицию. |
| [`insert_from_html(self, index, html_stream, use_slide_with_index_as_start)`](/slides/python-net/ru/aspose.slides/islidecollection/insert_from_html/#int-iorawiobase-bool) | Создаёт слайды из HTML-текста и вставляет их в коллекцию в указанную позицию. |
| [`insert_from_html(self, index, html_stream, resolver, uri, use_slide_with_index_as_start)`](/slides/python-net/ru/aspose.slides/islidecollection/insert_from_html/#int-iorawiobase-asposeslidesimportingiexternalresourceresolver-str-bool) | Создаёт слайды из HTML-текста и вставляет их в коллекцию в указанную позицию. |
| [`add_empty_slide(self, layout)`](/slides/python-net/ru/aspose.slides/islidecollection/add_empty_slide/#ilayoutslide) | Добавляет новый пустой слайд в конец коллекции. |
| [`insert_empty_slide(self, index, layout)`](/slides/python-net/ru/aspose.slides/islidecollection/insert_empty_slide/#int-ilayoutslide) | Вставляет копию указанного слайда в указанную позицию коллекции. |
| [`remove(self, value)`](/slides/python-net/ru/aspose.slides/islidecollection/remove/#islide) | Удаляет первое вхождение конкретного объекта из коллекции. |
| [`remove_at(self, index)`](/slides/python-net/ru/aspose.slides/islidecollection/remove_at/#int) | Удаляет элемент по указанному индексу в коллекции. |
| [`index_of(self, slide)`](/slides/python-net/ru/aspose.slides/islidecollection/index_of/#islide) | Возвращает индекс указанного слайда в коллекции. |

### См. также
* класс [`ISlide`](/slides/python-net/ru/aspose.slides/islide)
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* библиотека [`Aspose.Slides`](/slides/python-net)