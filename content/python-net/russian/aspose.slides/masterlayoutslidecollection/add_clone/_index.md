---
title: add_clone method
second_title: Aspose.Slides для Python через .NET API справка
description: 
type: docs
url: /ru/aspose.slides/masterlayoutslidecollection/add_clone/
weight: 20
---
## add_clone(self, source_layout) {#ilayoutslide}
Добавляет копию указанного слайда макета в конец коллекции.

### Возвращаемое значение

Added slide.

```python
def add_clone(self, source_layout):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| source_layout | [`ILayoutSlide`](/slides/python-net/ru/aspose.slides/ilayoutslide) | Слайд для клонирования. |

### Примечания

1) Новый макет будет связан с родительским мастером-слайдом для этой коллекции слайдов макета.  
   Таким образом, это аналог копирования/вставки с опцией "Use Destination Theme" в PowerPoint.  
2) Аналогом этого метода является метод **Aspose.Slides.IGlobalLayoutSlideCollection.AddClone(Aspose.Slides.ILayoutSlide,Aspose.Slide** , доступный через свойство [`IPresentation.layout_slides`](/slides/python-net/ru/aspose.slides/ipresentation/layout_slides).

### См. также
* класс [`ILayoutSlide`](/slides/python-net/ru/aspose.slides/ilayoutslide)
* класс [`MasterLayoutSlideCollection`](/slides/python-net/ru/aspose.slides/masterlayoutslidecollection)
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* библиотека [`Aspose.Slides`](/slides/python-net)