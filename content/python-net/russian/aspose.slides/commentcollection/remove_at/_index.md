---
title: remove_at method
second_title: Aspose.Slides для Python через .NET справочник API
description: 
type: docs
url: /ru/aspose.slides/commentcollection/remove_at/
weight: 80
---
## remove_at(self, index) {#int}
Удаляет элемент по указанному индексу в коллекции.

```python
def remove_at(self, index):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| index | **int** | Нулевой (нумерация с нуля) индекс элемента, который следует удалить. |

### Исключения

| Исключение | Описание |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | Индекс меньше 0 или индекс равен или превышает Count |
| [`PptxEditException`](/slides/python-net/ru/aspose.slides/pptxeditexception) | Выбрасывается, если комментарий уже удалён. |



### См. также
* класс [`CommentCollection`](/slides/python-net/ru/aspose.slides/commentcollection)
* класс [`PptxEditException`](/slides/python-net/ru/aspose.slides/pptxeditexception)
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* библиотека [`Aspose.Slides`](/slides/python-net)