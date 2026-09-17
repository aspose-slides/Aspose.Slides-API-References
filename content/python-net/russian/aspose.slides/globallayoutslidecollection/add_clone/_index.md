---
title: add_clone method
second_title: Aspose.Slides для Python через .NET API справочник
description: 
type: docs
url: /ru/aspose.slides/globallayoutslidecollection/add_clone/
weight: 20
---
## add_clone(self, source_layout) {#ilayoutslide}
Добавляет копию указанного макетного слайда в презентацию.

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

When cloning a layout between different presentations layout's master can be cloned too
            to keep source formatting.
            Internal registry is used to track automatically cloned masters to prevent creation of 
            multiple clones of the same master slide.
            Manual cloning of master slides will be neither prevented nor registered.


## add_clone(self, source_layout, dest_master) {#ilayoutslide-imasterslide}
Добавляет копию указанного макетного слайда в презентацию.

### Возвращаемое значение

Added slide.



```python
def add_clone(self, source_layout, dest_master):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| source_layout | [`ILayoutSlide`](/slides/python-net/ru/aspose.slides/ilayoutslide) | Слайд для клонирования. |
| dest_master | [`IMasterSlide`](/slides/python-net/ru/aspose.slides/imasterslide) | Мастер-слайд для нового макета. |

### Примечания

1) New layout will be linked with defined master in destination presentation.
            So this is analogue of copy/paste with "Use Destination Theme" option in PowerPoint.
            2) Analogue of this method is method **Aspose.Slides.IMasterLayoutSlideCollection.AddClone(Aspose.Slide**
            accessed with [`IMasterSlide.layout_slides`](/slides/python-net/ru/aspose.slides/imasterslide/layout_slides) property.



### См. также
* класс [`GlobalLayoutSlideCollection`](/slides/python-net/ru/aspose.slides/globallayoutslidecollection)
* класс [`ILayoutSlide`](/slides/python-net/ru/aspose.slides/ilayoutslide)
* класс [`IMasterSlide`](/slides/python-net/ru/aspose.slides/imasterslide)
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* библиотека [`Aspose.Slides`](/slides/python-net)