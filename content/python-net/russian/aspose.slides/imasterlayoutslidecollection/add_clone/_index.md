---
title: add_clone method
second_title: Справочник API Aspose.Slides для Python через .NET
description: 
type: docs
url: /ru/aspose.slides/imasterlayoutslidecollection/add_clone/
weight: 20
---
## add_clone(self, source_layout) {#ilayoutslide}
Добавляет копию указанного макетного слайда в конец коллекции.

### Возвращаемое значение

Добавленный слайд.



```python
def add_clone(self, source_layout):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| source_layout | [`ILayoutSlide`](/slides/python-net/ru/aspose.slides/ilayoutslide) | Слайд для клонирования. |

### Примечания

1) Новый макет будет связан с родительским мастер-слайдом для этой коллекции макетных слайдов.  
   Таким образом, это аналог копирования/вставки с опцией «Использовать тему места назначения» в PowerPoint.  
2) Аналогом этого метода является метод **Aspose.Slides.IGlobalLayoutSlideCollection.AddClone(Aspose.Slides.ILayoutSlide,Aspose.Slide**,
   доступный через свойство [`IPresentation.layout_slides`](/slides/python-net/ru/aspose.slides/ipresentation/layout_slides).



### См. также
* класс [`ILayoutSlide`](/slides/python-net/ru/aspose.slides/ilayoutslide)
* класс [`IMasterLayoutSlideCollection`](/slides/python-net/ru/aspose.slides/imasterlayoutslidecollection)
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* библиотека [`Aspose.Slides`](/slides/python-net)