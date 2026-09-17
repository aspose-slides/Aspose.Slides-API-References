---
title: remove method
second_title: Aspose.Slides для Python через .NET справочник API
description: 
type: docs
url: /ru/aspose.slides/globallayoutslidecollection/remove/
weight: 40
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

1) Чтобы избежать выброса исключения PptxEditException, проверьте свойство HasDependingSlides макета заранее.  
2) Вы также можете использовать метод [`ILayoutSlide.remove`](/slides/python-net/ru/aspose.slides/ilayoutslide/remove), чтобы упростить код.

### Исключения

| Исключение | Описание |
| :- | :- |
| [`PptxEditException`](/slides/python-net/ru/aspose.slides/pptxeditexception) | Выбрасывается, если макет используется в презентации (его свойство HasDependingSlides равно true). |



### См. также
* класс [`GlobalLayoutSlideCollection`](/slides/python-net/ru/aspose.slides/globallayoutslidecollection)
* класс [`ILayoutSlide`](/slides/python-net/ru/aspose.slides/ilayoutslide)
* класс [`PptxEditException`](/slides/python-net/ru/aspose.slides/pptxeditexception)
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* библиотека [`Aspose.Slides`](/slides/python-net)