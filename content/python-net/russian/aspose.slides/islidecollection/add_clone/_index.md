---
title: add_clone method
second_title: Aspose.Slides для Python через .NET: справочник API
description: 
type: docs
url: /ru/aspose.slides/islidecollection/add_clone/
weight: 10
---
## add_clone(self, source_slide) {#islide}
Добавляет копию указанного слайда в конец коллекции.

### Возвращаемое значение

Новый слайд.



```python
def add_clone(self, source_slide):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| source_slide | [`ISlide`](/slides/python-net/ru/aspose.slides/islide) | Слайд для клонирования. |

### Примечания

При клонировании слайда между разными презентациями мастер-слайда также может быть клонирован.  
Внутренний реестр используется для отслеживания автоматически клонированных мастеров, чтобы предотвратить создание нескольких копий одного и того же мастер-слайда.  
Ручное клонирование мастер-слайдов не будет ни предотвращено, ни зарегистрировано.  
Если вам требуется больший контроль над процессом клонирования, используйте  
**Aspose.Slides.ISlideCollection.AddClone(Aspose.Slides.ISlide,Aspose.Slide** или  
**Aspose.Slides.ISlideCollection.AddClone(Aspose.Slides.ISlide,Aspose.Slides.IMasterSlide,Syste** для клонирования слайдов,  
**Aspose.Slides.IGlobalLayoutSlideCollection.AddClone(Aspose.Slide** или  
**Aspose.Slides.IGlobalLayoutSlideCollection.AddClone(Aspose.Slides.ILayoutSlide,Aspose.Slide** для клонирования компоновок и  
**Aspose.Slides.IMasterSlideCollection.AddClone(Aspose.Slide** для клонирования мастеров.


## add_clone(self, source_slide, section) {#islide-isection}
Добавляет копию указанного слайда в конец указанного раздела.

### Возвращаемое значение

Новый слайд.



```python
def add_clone(self, source_slide, section):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| source_slide | [`ISlide`](/slides/python-net/ru/aspose.slides/islide) | Слайд для клонирования. |
| section | [`ISection`](/slides/python-net/ru/aspose.slides/isection) | Раздел для нового слайда. |

### Исключения

| Исключение | Описание |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** |  |
| [`PptxEditException`](/slides/python-net/ru/aspose.slides/pptxeditexception) |  |


## add_clone(self, source_slide, dest_layout) {#islide-ilayoutslide}
Добавляет копию указанного слайда в конец коллекции.

### Возвращаемое значение

Новый слайд.



```python
def add_clone(self, source_slide, dest_layout):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| source_slide | [`ISlide`](/slides/python-net/ru/aspose.slides/islide) | Слайд для клонирования. |
| dest_layout | [`ILayoutSlide`](/slides/python-net/ru/aspose.slides/ilayoutslide) | Слайд-компоновка для нового слайда. |


## add_clone(self, source_slide, dest_master, allow_clone_missing_layout) {#islide-imasterslide-bool}
Добавляет копию указанного исходного слайда в конец коллекции.  
Подходящая компоновка будет выбрана автоматически из указанного мастера (подходящая компоновка — это компоновка с тем же типом или именем, что и у компоновки исходного слайда). Если подходящей компоновки нет, компоновка исходного слайда будет клонирована (если allowCloneMissingLayout равно true) или будет выброшено PptxEditException (если allowCloneMissingLayout равно false).

### Возвращаемое значение

Новый слайд.



```python
def add_clone(self, source_slide, dest_master, allow_clone_missing_layout):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| source_slide | [`ISlide`](/slides/python-net/ru/aspose.slides/islide) | Слайд для клонирования. |
| dest_master | [`IMasterSlide`](/slides/python-net/ru/aspose.slides/imasterslide) | Мастер-слайд для нового слайда. |
| allow_clone_missing_layout | **bool** | Если в указанном мастере нет подходящей компоновки, будет клонирована компоновка исходного слайда (если allowCloneMissingLayout true) или будет выброшено PptxEditException (если allowCloneMissingLayout false). |

### Исключения

| Исключение | Описание |
| :- | :- |
| [`PptxEditException`](/slides/python-net/ru/aspose.slides/pptxeditexception) | Выбрасывается, если в указанном мастере нет подходящей компоновки и allowCloneMissingLayout false. |



### См. также
* класс [`ILayoutSlide`](/slides/python-net/ru/aspose.slides/ilayoutslide)
* класс [`IMasterSlide`](/slides/python-net/ru/aspose.slides/imasterslide)
* класс [`ISection`](/slides/python-net/ru/aspose.slides/isection)
* класс [`ISlide`](/slides/python-net/ru/aspose.slides/islide)
* класс [`ISlideCollection`](/slides/python-net/ru/aspose.slides/islidecollection)
* класс [`PptxEditException`](/slides/python-net/ru/aspose.slides/pptxeditexception)
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)