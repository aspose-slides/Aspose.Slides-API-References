---
title: insert_comment method
second_title: Aspose.Slides для Python через .NET API Reference
description: 
type: docs
url: /ru/aspose.slides/commentcollection/insert_comment/
weight: 50
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
| index | **int** | Индекс элемента в коллекции, в который следует вставить комментарий. |
| text | **str** | Обычный текст нового комментария. |
| slide | [`ISlide`](/slides/python-net/ru/aspose.slides/islide) | Слайд в презентации, в который добавляется новый комментарий. |
| position | **aspose.slides.PointF** | Позиция на слайде, где будет добавлен новый комментарий. |
| creation_time | **DateTime** | Время создания комментария. |



### См. также
* класс [`CommentCollection`](/slides/python-net/ru/aspose.slides/commentcollection)
* класс [`IComment`](/slides/python-net/ru/aspose.slides/icomment)
* класс [`ISlide`](/slides/python-net/ru/aspose.slides/islide)
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* библиотека [`Aspose.Slides`](/slides/python-net)