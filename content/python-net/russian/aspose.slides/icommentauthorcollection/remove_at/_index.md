---
title: remove_at method
second_title: Aspose.Slides для Python через .NET справочник API
description: 
type: docs
url: /ru/aspose.slides/icommentauthorcollection/remove_at/
weight: 60
---
## remove_at(self, index) {#int}
Удаляет автора по указанному индексу в коллекции.

```python
def remove_at(self, index):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| index | **int** | Нулевой индекс элемента, который нужно удалить. |

### Исключения

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | Индекс меньше 0 или индекс равен или превышает Count |
| [`PptxEditException`](/slides/python-net/ru/aspose.slides/pptxeditexception) | Выбрасывается, если автор уже удалён. |

### См. также
* класс [`ICommentAuthorCollection`](/slides/python-net/ru/aspose.slides/icommentauthorcollection)
* класс [`PptxEditException`](/slides/python-net/ru/aspose.slides/pptxeditexception)
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* библиотека [`Aspose.Slides`](/slides/python-net)