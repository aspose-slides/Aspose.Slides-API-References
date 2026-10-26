---
title: insert_clone method
second_title: Aspose.Slides для Python через .NET — справочник API
description: 
type: docs
url: /ru/aspose.slides/imasterlayoutslidecollection/insert_clone/
weight: 50
---
## insert_clone(self, index, source_layout) {#int-ilayoutslide}
Вставляет копию указанного шаблона слайда в указанную позицию коллекции.

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

### Примечание

Новый макет будет связан с родительским мастер-слайдом для этой коллекции слайдов-макетов.  
Это аналог операции копировать/вставить с параметром «Use Destination Theme» в PowerPoint.



### См. также
* класс [`ILayoutSlide`](/slides/python-net/ru/aspose.slides/ilayoutslide)
* класс [`IMasterLayoutSlideCollection`](/slides/python-net/ru/aspose.slides/imasterlayoutslidecollection)
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* библиотека [`Aspose.Slides`](/slides/python-net)