---
title: insert_comment method
second_title: Aspose.Slides для Python через .NET API
description: 
type: docs
url: /ru/aspose.slides/icommentcollection/insert_comment/
weight: 40
---
## insert_comment(self, index, text, slide, position, creation_time) {#int-str-islide-asposepydrawingpointf-datetime}
Вставить новый комментарий в коллекцию по указанному индексу.

### Возвращаемое значение

Вставленный комментарий.



```python
def insert_comment(self, index, text, slide, position, creation_time):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| index | **int** | Индекс элемента в коллекции, в который должен быть вставлен комментарий. |
| text | **str** | Обычный текст нового комментария. |
| slide | [`ISlide`](/slides/python-net/ru/aspose.slides/islide) | Слайд в презентации, где нужно добавить новый комментарий. |
| position | **aspose.slides.PointF** | Позиция на слайде, где нужно добавить новый комментарий. |
| creation_time | **DateTime** | Время создания комментария. |



### Смотрите также
* класс [`IComment`](/slides/python-net/ru/aspose.slides/icomment)
* класс [`ICommentCollection`](/slides/python-net/ru/aspose.slides/icommentcollection)
* класс [`ISlide`](/slides/python-net/ru/aspose.slides/islide)
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* библиотека [`Aspose.Slides`](/slides/python-net)