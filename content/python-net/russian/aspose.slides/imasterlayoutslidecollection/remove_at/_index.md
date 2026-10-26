---
title: remove_at method
second_title: Aspose.Slides для Python через .NET справочник API
description: 
type: docs
url: /ru/aspose.slides/imasterlayoutslidecollection/remove_at/
weight: 70
---
## remove_at(self, index) {#int}
Удаляет элемент в указанном индексе коллекции.

```python
def remove_at(self, index):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| index | **int** | Нулевой индекс элемента, который следует удалить. |

### Примечания

1) Чтобы избежать выброса PptxEditException, проверьте свойство HasDependingSlides макета заранее.
2) Вы также можете использовать метод [`ILayoutSlide.remove`](/slides/python-net/ru/aspose.slides/ilayoutslide/remove) для упрощения кода.

### Исключения

| Исключение | Описание |
| :- | :- |
| [`PptxEditException`](/slides/python-net/ru/aspose.slides/pptxeditexception) | Выбрасывается, если макет используется в презентации (его свойство HasDependingSlides равно true). |

### См. также
* класс [`IMasterLayoutSlideCollection`](/slides/python-net/ru/aspose.slides/imasterlayoutslidecollection)
* класс [`PptxEditException`](/slides/python-net/ru/aspose.slides/pptxeditexception)
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* библиотека [`Aspose.Slides`](/slides/python-net)