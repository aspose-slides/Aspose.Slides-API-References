---
title: ICommentCollection class
second_title: Aspose.Slides для Python через .NET API Reference
description: 
type: docs
url: /ru/aspose.slides/icommentcollection/
---
## ICommentCollection класс

Представляет коллекцию комментариев одного автора.

Тип ICommentCollection раскрывает следующие члены:

Получает элемент по заданному индексу.
            Только для чтения [`IComment`](/slides/python-net/ru/aspose.slides/icomment).

## Indexer

| Name | Description |
| :- | :- |
| [`[index]`](/slides/python-net/ru/aspose.slides/icommentcollection/__getitem__/) |  |

## Methods

| Method | Description |
| :- | :- |
| [`to_array(self)`](/slides/python-net/ru/aspose.slides/icommentcollection/to_array/#) | Создает и возвращает массив со всеми комментариями. |
| [`to_array(self, start_index, count)`](/slides/python-net/ru/aspose.slides/icommentcollection/to_array/#int-int) | Создает и возвращает массив со всеми комментариями из указанного диапазона. |
| [`add_comment(self, text, slide, position, creation_time)`](/slides/python-net/ru/aspose.slides/icommentcollection/add_comment/#str-islide-asposeslidespointf-datetime) | Добавляет новый комментарий в конец коллекции. |
| [`add_modern_comment(self, text, slide, shape, position, creation_time)`](/slides/python-net/ru/aspose.slides/icommentcollection/add_modern_comment/#str-islide-ishape-asposeslidespointf-datetime) | Добавляет новый современный комментарий в конец коллекции. |
| [`insert_comment(self, index, text, slide, position, creation_time)`](/slides/python-net/ru/aspose.slides/icommentcollection/insert_comment/#int-str-islide-asposeslidespointf-datetime) | Вставляет новый комментарий в коллекцию по заданному индексу. |
| [`insert_modern_comment(self, index, text, slide, shape, position, creation_time)`](/slides/python-net/ru/aspose.slides/icommentcollection/insert_modern_comment/#int-str-islide-ishape-asposeslidespointf-datetime) | Вставляет новый современный комментарий в коллекцию по заданному индексу. |
| [`remove_at(self, index)`](/slides/python-net/ru/aspose.slides/icommentcollection/remove_at/#int) | Удаляет элемент по заданному индексу в коллекции. |
| [`remove(self, comment)`](/slides/python-net/ru/aspose.slides/icommentcollection/remove/#icomment) | Удаляет первое вхождение указанного комментария в коллекции. |
| [`clear(self)`](/slides/python-net/ru/aspose.slides/icommentcollection/clear/#) | Удаляет все комментарии из коллекции. |

### См. также
* класс [`IComment`](/slides/python-net/ru/aspose.slides/icomment)
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* библиотека [`Aspose.Slides`](/slides/python-net)