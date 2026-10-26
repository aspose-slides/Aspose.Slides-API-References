---
title: add_clone method
second_title: Справочник API Aspose.Slides для Python через .NET
description: 
type: docs
url: /ru/aspose.slides/slidecollection/add_clone/
weight: 10
---
## add_clone(self, source_slide) {#islide}
Добавляет копию указанного слайда в конец коллекции.

### Возврат

Новый слайд.



```python
def add_clone(self, source_slide):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| source_slide | [`ISlide`](/slides/python-net/ru/aspose.slides/islide) | Слайд для клонирования. |

### Примечания

При клонировании слайда между разными презентациями также может быть клонирован мастер-слайд.  
Внутренний реестр используется для отслеживания автоматически клонированных мастеров, чтобы предотвратить создание нескольких копий одного и того же мастер-слайда.  
Ручное клонирование мастер-слайдов не будет ни предотвращено, ни зарегистрировано.  
Если вам нужен больший контроль над процессом клонирования, используйте  
**Aspose.Slides.SlideCollection.AddClone(Aspose.Slides.ISlide,Aspose.Slide** или  
**Aspose.Slides.SlideCollection.AddClone(Aspose.Slides.ISlide,Aspose.Slides.IMasterSlide,Syste** для клонирования слайдов,  
**Aspose.Slides.IGlobalLayoutSlideCollection.AddClone(Aspose.Slide** или  
**Aspose.Slides.IGlobalLayoutSlideCollection.AddClone(Aspose.Slides.ILayoutSlide,Aspose.Slide** для клонирования макетов и  
**Aspose.Slides.IMasterSlideCollection.AddClone(Aspose.Slide** для клонирования мастеров.


## add_clone(self, source_slide, section) {#islide-isection}
Добавляет копию указанного слайда в конец указанного раздела.

### Возврат

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

### Возврат

Новый слайд.



```python
def add_clone(self, source_slide, dest_layout):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| source_slide | [`ISlide`](/slides/python-net/ru/aspose.slides/islide) | Слайд для клонирования. |
| dest_layout | [`ILayoutSlide`](/slides/python-net/ru/aspose.slides/ilayoutslide) | Макетный слайд для нового слайда. |


## add_clone(self, source_slide, dest_master, allow_clone_missing_layout) {#islide-imasterslide-bool}
Добавляет копию указанного исходного слайда в конец коллекции.  
Подходящий макет будет выбран автоматически из указанного  
мастера (подходящий макет — это макет с тем же Type или Name, что и макет исходного слайда). Если подходящего макета нет,  
макет исходного слайда будет клонирован (если allowCloneMissingLayout  
равно true) или будет выброшено исключение PptxEditException (если allowCloneMissingLayout  
равно false).

### Возврат

Новый слайд.



```python
def add_clone(self, source_slide, dest_master, allow_clone_missing_layout):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| source_slide | [`ISlide`](/slides/python-net/ru/aspose.slides/islide) | Слайд для клонирования. |
| dest_master | [`IMasterSlide`](/slides/python-net/ru/aspose.slides/imasterslide) | Мастер-слайд для нового слайда. |
| allow_clone_missing_layout | **bool** | Если в указанном мастере нет подходящего макета, то макет исходного слайда будет клонирован (если allowCloneMissingLayout true) или <br/><br/>            PptxEditException будет выброшено (если allowCloneMissingLayout false). |

### Исключения

| Исключение | Описание |
| :- | :- |
| [`PptxEditException`](/slides/python-net/ru/aspose.slides/pptxeditexception) | Выбрасывается, если в указанном мастере нет подходящего макета и <br/>            allowCloneMissingLayout равно false. |



### См. также
* класс [`ILayoutSlide`](/slides/python-net/ru/aspose.slides/ilayoutslide)
* класс [`IMasterSlide`](/slides/python-net/ru/aspose.slides/imasterslide)
* класс [`ISection`](/slides/python-net/ru/aspose.slides/isection)
* класс [`ISlide`](/slides/python-net/ru/aspose.slides/islide)
* класс [`PptxEditException`](/slides/python-net/ru/aspose.slides/pptxeditexception)
* класс [`SlideCollection`](/slides/python-net/ru/aspose.slides/slidecollection)
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* библиотека [`Aspose.Slides`](/slides/python-net)