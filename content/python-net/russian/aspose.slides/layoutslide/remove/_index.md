---
title: remove method
second_title: Aspose.Slides для Python через .NET – справочник API
description: 
type: docs
url: /ru/aspose.slides/layoutslide/remove/
weight: 60
---
## remove(self) {#}
Удаляет макет из презентации.


```python
def remove(self):
    ...
```


### Примечания

Чтобы избежать возбуждения PptxEditException, проверьте свойство HasDependingSlides макета заранее.

### Исключения

| Исключение | Описание |
| :- | :- |
| [`PptxEditException`](/slides/python-net/ru/aspose.slides/pptxeditexception) | Выбрасывается, если макет уже удалён из презентации или если макет используется в презентации (его <br/>            HasDependingSlides property is true). |



### См. также
* класс [`LayoutSlide`](/slides/python-net/ru/aspose.slides/layoutslide)
* класс [`PptxEditException`](/slides/python-net/ru/aspose.slides/pptxeditexception)
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* библиотека [`Aspose.Slides`](/slides/python-net)