---
title: remove_at method
second_title: Aspose.Slides для Python через .NET API справочник
description: 
type: docs
url: /ru/aspose.slides/masterslidecollection/remove_at/
weight: 40
---
## remove_at(self, index) {#int}
Удаляет элемент с указанным индексом в коллекции.

```python
def remove_at(self, index):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| index | **int** | Нулевой индекс элемента, который нужно удалить. |

### Примечания

Чтобы избежать выброса PptxEditException, проверьте свойство HasDependingSlides мастера заранее.

### Исключения

| Исключение | Описание |
| :- | :- |
| [`PptxEditException`](/slides/python-net/ru/aspose.slides/pptxeditexception) | Выбрасывается, если мастер, который нужно удалить, используется в презентации (его свойство HasDependingSlides равно true). |

### См. также
* класс [`MasterSlideCollection`](/slides/python-net/ru/aspose.slides/masterslidecollection)
* класс [`PptxEditException`](/slides/python-net/ru/aspose.slides/pptxeditexception)
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* библиотека [`Aspose.Slides`](/slides/python-net)