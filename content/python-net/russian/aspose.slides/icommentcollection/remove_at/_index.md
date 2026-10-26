---
title: remove_at method
second_title: Aspose.Slides для Python через .NET API Reference
description: 
type: docs
url: /ru/aspose.slides/icommentcollection/remove_at/
weight: 70
---
## remove_at(self, index) {#int}
Удаляет элемент по указанному индексу в коллекции.

```python
def remove_at(self, index):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| index | **int** | Нулевой индекс элемента, который следует удалить. |

### Исключения

| Исключение | Описание |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | Индекс меньше 0 или индекс равен или превышает Count |
| [`PptxEditException`](/slides/python-net/ru/aspose.slides/pptxeditexception) | Выбрасывается, если комментарий уже удалён. |

### Смотрите также
* класс [`ICommentCollection`](/slides/python-net/ru/aspose.slides/icommentcollection)
* класс [`PptxEditException`](/slides/python-net/ru/aspose.slides/pptxeditexception)
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* библиотека [`Aspose.Slides`](/slides/python-net)