---
title: ICommentCollection class
second_title: Aspose.Slides для Python через .NET: справка API
description: 
type: docs
url: /ru/aspose.slides/icommentcollection/
---
## ICommentCollection класс

Представляет коллекцию комментариев одного автора.

Тип ICommentCollection раскрывает следующие члены:

Получает элемент по указанному индексу.
            Только для чтения [`IComment`](/slides/python-net/ru/aspose.slides/icomment).

## Индексатор

| Имя | Описание |
| :- | :- |
| [`[index]`](/slides/python-net/ru/aspose.slides/icommentcollection/__getitem__/) |  |

## Методы

| Метод | Описание |
| :- | :- |
| [`to_array(self)`](/slides/python-net/ru/aspose.slides/icommentcollection/to_array/#) | Создаёт и возвращает массив со всеми комментариями. |
| [`to_array(self, start_index, count)`](/slides/python-net/ru/aspose.slides/icommentcollection/to_array/#int-int) | Создаёт и возвращает массив со всеми комментариями из указанного диапазона. |
| [`add_comment(self, text, slide, position, creation_time)`](/slides/python-net/ru/aspose.slides/icommentcollection/add_comment/#str-islide-asposepydrawingpointf-datetime) | Добавить новый комментарий в конец коллекции. |
| [`add_modern_comment(self, text, slide, shape, position, creation_time)`](/slides/python-net/ru/aspose.slides/icommentcollection/add_modern_comment/#str-islide-ishape-asposepydrawingpointf-datetime) | Добавить новый современный комментарий в конец коллекции. |
| [`insert_comment(self, index, text, slide, position, creation_time)`](/slides/python-net/ru/aspose.slides/icommentcollection/insert_comment/#int-str-islide-asposepydrawingpointf-datetime) | Вставить новый комментарий в коллекцию по указанному индексу. |
| [`insert_modern_comment(self, index, text, slide, shape, position, creation_time)`](/slides/python-net/ru/aspose.slides/icommentcollection/insert_modern_comment/#int-str-islide-ishape-asposepydrawingpointf-datetime) | Вставить новый современный комментарий в коллекцию по указанному индексу. |
| [`remove_at(self, index)`](/slides/python-net/ru/aspose.slides/icommentcollection/remove_at/#int) | Удалить элемент по указанному индексу в коллекции. |
| [`remove(self, comment)`](/slides/python-net/ru/aspose.slides/icommentcollection/remove/#icomment) | Удалить первое вхождение указанного комментария в коллекции. |
| [`clear(self)`](/slides/python-net/ru/aspose.slides/icommentcollection/clear/#) | Удалить все комментарии из коллекции. |


### См. также
* класс [`IComment`](/slides/python-net/ru/aspose.slides/icomment)
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* библиотека [`Aspose.Slides`](/slides/python-net)