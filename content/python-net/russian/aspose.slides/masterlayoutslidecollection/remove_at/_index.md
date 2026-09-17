---
title: remove_at method
second_title: Aspose.Slides для Python через .NET Справочник API
description: 
type: docs
url: /ru/aspose.slides/masterlayoutslidecollection/remove_at/
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
| index | **int** | Нулевой индекс удаляемого элемента. |

### Примечания

1) Чтобы избежать выбрасывания PptxEditException, проверьте свойство HasDependingSlides макета заранее.  
2) Вы также можете использовать метод [`ILayoutSlide.remove`](/slides/python-net/ru/aspose.slides/ilayoutslide/remove) для упрощения кода.

### Исключения

| Исключение | Описание |
| :- | :- |
| [`PptxEditException`](/slides/python-net/ru/aspose.slides/pptxeditexception) | Выбрасывается, если макет используется в презентации (его свойство HasDependingSlides равно true). |

### См. также
* класс [`MasterLayoutSlideCollection`](/slides/python-net/ru/aspose.slides/masterlayoutslidecollection)
* класс [`PptxEditException`](/slides/python-net/ru/aspose.slides/pptxeditexception)
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* библиотека [`Aspose.Slides`](/slides/python-net)