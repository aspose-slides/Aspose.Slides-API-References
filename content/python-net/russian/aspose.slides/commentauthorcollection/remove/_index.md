---
title: remove method
second_title: Aspose.Slides для Python через .NET справочник API
description: 
type: docs
url: /ru/aspose.slides/commentauthorcollection/remove/
weight: 50
---
## remove(self, author) {#icommentauthor}
Удаляет первое вхождение указанного автора из коллекции.

```python
def remove(self, author):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| author | [`ICommentAuthor`](/slides/python-net/ru/aspose.slides/icommentauthor) | Автор, которого нужно удалить из коллекции. |

### Исключения

| Исключение | Описание |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | Автор равен `None` |
| [`PptxEditException`](/slides/python-net/ru/aspose.slides/pptxeditexception) | Выбрасывается, если автор уже удалён. |

### См. также
* класс [`CommentAuthorCollection`](/slides/python-net/ru/aspose.slides/commentauthorcollection)
* класс [`ICommentAuthor`](/slides/python-net/ru/aspose.slides/icommentauthor)
* класс [`PptxEditException`](/slides/python-net/ru/aspose.slides/pptxeditexception)
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* библиотека [`Aspose.Slides`](/slides/python-net)