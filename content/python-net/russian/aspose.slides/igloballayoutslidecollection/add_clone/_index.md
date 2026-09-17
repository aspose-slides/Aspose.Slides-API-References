---
title: add_clone method
second_title: Aspose.Slides для Python через .NET справочник API
description: 
type: docs
url: /ru/aspose.slides/igloballayoutslidecollection/add_clone/
weight: 20
---
## add_clone(self, source_layout) {#ilayoutslide}
Добавляет копию указанного макета слайда в презентацию.

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
            При клонировании макета между разными презентациями мастер-макет также может быть склонирован, чтобы сохранить исходное форматирование.
            Internal registry is used to track automatically cloned masters to prevent creation of 
            Внутренний реестр используется для отслеживания автоматически склонированных мастеров, чтобы предотвратить создание 
            multiple clones of the same master slide.
            множественных копий одного и того же мастер-слайда.
            Manual cloning of master slides will be neither prevented nor registered.
            Ручное клонирование мастер-слайдов не будет ни предотвращено, ни зарегистрировано.


## add_clone(self, source_layout, dest_master) {#ilayoutslide-imasterslide}
Добавляет копию указанного макета слайда в презентацию.

### Возвращаемое значение

Добавленный слайд.



```python
def add_clone(self, source_layout, dest_master):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| source_layout | [`ILayoutSlide`](/slides/python-net/ru/aspose.slides/ilayoutslide) | Слайд для клонирования. |
| dest_master | [`IMasterSlide`](/slides/python-net/ru/aspose.slides/imasterslide) | Мастер-слайд для нового макета. |

### Примечания

New layout will be linked with defined master in destination presentation.
            Новый макет будет связан с определённым мастером в целевой презентации.
            So this is analogue of copy/paste with "Use Destination Theme" option in PowerPoint.
            Это аналог операции копировать/вставить с опцией «Использовать тему назначения» в PowerPoint.



### См. также
* класс [`IGlobalLayoutSlideCollection`](/slides/python-net/ru/aspose.slides/igloballayoutslidecollection)
* класс [`ILayoutSlide`](/slides/python-net/ru/aspose.slides/ilayoutslide)
* класс [`IMasterSlide`](/slides/python-net/ru/aspose.slides/imasterslide)
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* библиотека [`Aspose.Slides`](/slides/python-net)