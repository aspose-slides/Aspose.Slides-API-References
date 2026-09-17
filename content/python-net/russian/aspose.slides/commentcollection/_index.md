---
title: CommentCollection class
second_title: Aspose.Slides для Python через .NET справочник API
description: 
type: docs
url: /ru/aspose.slides/commentcollection/
---
## CommentCollection класс

Представляет коллекцию комментариев одного автора.

Тип CommentCollection раскрывает следующие члены:

Получает элемент по указанному индексу.
            Read-only [`Comment`](/slides/python-net/ru/aspose.slides/comment).

## Индексатор

| Имя | Описание |
| :- | :- |
| [`[index]`](/slides/python-net/ru/aspose.slides/commentcollection/__getitem__/) |  |

## Методы

| Метод | Описание |
| :- | :- |
| [`to_array(self)`](/slides/python-net/ru/aspose.slides/commentcollection/to_array/#) | Создает и возвращает массив со всеми комментариями. |
| [`to_array(self, start_index, count)`](/slides/python-net/ru/aspose.slides/commentcollection/to_array/#int-int) | Создает и возвращает массив с комментариями из указанного диапазона. |
| [`add_comment(self, text, slide, position, creation_time)`](/slides/python-net/ru/aspose.slides/commentcollection/add_comment/#str-islide-asposepydrawingpointf-datetime) | Добавляет новый комментарий в конец коллекции. |
| [`add_modern_comment(self, text, slide, shape, position, creation_time)`](/slides/python-net/ru/aspose.slides/commentcollection/add_modern_comment/#str-islide-ishape-asposepydrawingpointf-datetime) | Добавляет новый современный комментарий в конец коллекции. |
| [`insert_comment(self, index, text, slide, position, creation_time)`](/slides/python-net/ru/aspose.slides/commentcollection/insert_comment/#int-str-islide-asposepydrawingpointf-datetime) | Вставляет новый комментарий в коллекцию по указанному индексу. |
| [`insert_modern_comment(self, index, text, slide, shape, position, creation_time)`](/slides/python-net/ru/aspose.slides/commentcollection/insert_modern_comment/#int-str-islide-ishape-asposepydrawingpointf-datetime) | Вставляет новый современный комментарий в коллекцию по указанному индексу. |
| [`remove_at(self, index)`](/slides/python-net/ru/aspose.slides/commentcollection/remove_at/#int) | Удаляет элемент по указанному индексу в коллекции. |
| [`remove(self, comment)`](/slides/python-net/ru/aspose.slides/commentcollection/remove/#icomment) | Удаляет первое вхождение указанного комментария в коллекции. |
| [`clear(self)`](/slides/python-net/ru/aspose.slides/commentcollection/clear/#) | Удаляет все комментарии из коллекции. |
| [`find_comment_by_idx(self, idx)`](/slides/python-net/ru/aspose.slides/commentcollection/find_comment_by_idx/#int) | Находит комментарий в коллекции по индексу. |


### См. также
* класс [`Comment`](/slides/python-net/ru/aspose.slides/comment)
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* библиотека [`Aspose.Slides`](/slides/python-net)