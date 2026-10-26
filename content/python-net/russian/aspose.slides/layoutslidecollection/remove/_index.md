---
title: remove method
second_title: Aspose.Slides для Python через .NET API справочник
description: 
type: docs
url: /ru/aspose.slides/layoutslidecollection/remove/
weight: 20
---
## remove(self, value) {#ilayoutslide}
Удаляет макет из коллекции.

```python
def remove(self, value):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| value | [`ILayoutSlide`](/slides/python-net/ru/aspose.slides/ilayoutslide) | Слайд макета, который нужно удалить из коллекции. |

### Примечания

1) Чтобы избежать выброса PptxEditException, проверьте свойство HasDependingSlides макета заранее.
2) Вы также можете использовать метод [`ILayoutSlide.remove`](/slides/python-net/ru/aspose.slides/ilayoutslide/remove) для упрощения кода.

### Исключения

| Исключение | Описание |
| :- | :- |
| [`PptxEditException`](/slides/python-net/ru/aspose.slides/pptxeditexception) | Выбрасывается, если макет используется в презентации (его свойство HasDependingSlides равно true). |

### См. также
* класс [`ILayoutSlide`](/slides/python-net/ru/aspose.slides/ilayoutslide)
* класс [`LayoutSlideCollection`](/slides/python-net/ru/aspose.slides/layoutslidecollection)
* класс [`PptxEditException`](/slides/python-net/ru/aspose.slides/pptxeditexception)
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* библиотека [`Aspose.Slides`](/slides/python-net)