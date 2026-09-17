---
title: remove method
second_title: Aspose.Slides для Python через .NET API Reference
description: 
type: docs
url: /ru/aspose.slides/icommentcollection/remove/
weight: 60
---
## remove(self, comment) {#icomment}
Удаляет первое вхождение указанного комментария в коллекции.

```python
def remove(self, comment):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| comment | [`IComment`](/slides/python-net/ru/aspose.slides/icomment) | Комментарий, который нужно удалить из коллекции. |

### Исключения

| Исключение | Описание |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | Если comment равен `None` |
| [`PptxEditException`](/slides/python-net/ru/aspose.slides/pptxeditexception) | Выбрасывается, если comment уже удалён. |

### См. также
* класс [`IComment`](/slides/python-net/ru/aspose.slides/icomment)
* класс [`ICommentCollection`](/slides/python-net/ru/aspose.slides/icommentcollection)
* класс [`PptxEditException`](/slides/python-net/ru/aspose.slides/pptxeditexception)
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* библиотека [`Aspose.Slides`](/slides/python-net)