---
title: insert_clone method
second_title: Aspose.Slides для Python через .NET API Reference
description: 
type: docs
url: /ru/aspose.slides/masterlayoutslidecollection/insert_clone/
weight: 50
---
## insert_clone(self, index, source_layout) {#int-ilayoutslide}
Вставляет копию указанного слайда макета в заданную позицию коллекции.

### Возвращаемое значение
Вставленный слайд.

```python
def insert_clone(self, index, source_layout):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| index | **int** | Индекс нового слайда. |
| source_layout | [`ILayoutSlide`](/slides/python-net/ru/aspose.slides/ilayoutslide) | Слайд для клонирования. |

### Примечания
Новый макет будет связан с родительским мастер-слайдом для этой коллекции слайдов макета.  
Таким образом, это аналог копирования/вставки с опцией «Use Destination Theme» в PowerPoint.

### См. также
* класс [`ILayoutSlide`](/slides/python-net/ru/aspose.slides/ilayoutslide)
* класс [`MasterLayoutSlideCollection`](/slides/python-net/ru/aspose.slides/masterlayoutslidecollection)
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* библиотека [`Aspose.Slides`](/slides/python-net)