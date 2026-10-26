---
title: remove_at method
second_title: Справочник API Aspose.Slides для Python через .NET
description: 
type: docs
url: /ru/aspose.slides/commentauthorcollection/remove_at/
weight: 60
---
## remove_at(self, index) {#int}
Удаляет автора по указанному индексу в коллекции.


```python
def remove_at(self, index):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| index | **int** | Нулевой индекс элемента, который нужно удалить. |

### Исключения

| Исключение | Описание |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | Индекс меньше 0 или индекс равен или больше Count |
| [`PptxEditException`](/slides/python-net/ru/aspose.slides/pptxeditexception) | Выбрасывается, если автор уже удалён. |



### См. также
* класс [`CommentAuthorCollection`](/slides/python-net/ru/aspose.slides/commentauthorcollection)
* класс [`PptxEditException`](/slides/python-net/ru/aspose.slides/pptxeditexception)
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* библиотека [`Aspose.Slides`](/slides/python-net)