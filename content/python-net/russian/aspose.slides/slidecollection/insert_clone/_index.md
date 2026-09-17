---
title: insert_clone method
second_title: Aspose.Slides для Python через .NET API Reference
description: 
type: docs
url: /ru/aspose.slides/slidecollection/insert_clone/
weight: 60
---
## insert_clone(self, index, source_slide) {#int-islide}
Вставляет копию указанного слайда в указанную позицию коллекции.

### Возвращаемое значение

Вставленный слайд.



```python
def insert_clone(self, index, source_slide):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| index | **int** | Индекс нового слайда. |
| source_slide | [`ISlide`](/slides/python-net/ru/aspose.slides/islide) | Слайд для клонирования. |

### Примечания

При клонировании слайда между различными презентациями мастер-слайд также может быть клонирован.  
Внутренний реестр используется для отслеживания автоматически клонированных мастеров, чтобы предотвратить создание нескольких копий одного и того же мастер-слайда.  
Ручное клонирование мастер-слайдов не будет ни предотвращено, ни зарегистрировано.  
Если вам нужен больший контроль над процессом клонирования, используйте  
**Aspose.Slides.SlideCollection.InsertClone(System.Int32,Aspose.Slides.ISlide,Aspose.Slide** или  
**Aspose.Slides.SlideCollection.InsertClone(System.Int32,Aspose.Slides.ISlide,Aspose.Slides.IMasterSlide,Syste** для клонирования слайдов и  
**Aspose.Slides.IMasterSlideCollection.AddClone(Aspose.Slide** для клонирования мастеров.


## insert_clone(self, index, source_slide, dest_layout) {#int-islide-ilayoutslide}
Вставляет копию указанного слайда в указанную позицию коллекции.

### Возвращаемое значение

Вставленный слайд.



```python
def insert_clone(self, index, source_slide, dest_layout):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| index | **int** | Индекс нового слайда. |
| source_slide | [`ISlide`](/slides/python-net/ru/aspose.slides/islide) | Слайд для клонирования. |
| dest_layout | [`ILayoutSlide`](/slides/python-net/ru/aspose.slides/ilayoutslide) | Макетный слайд для нового слайда. |


## insert_clone(self, index, source_slide, dest_master, allow_clone_missing_layout) {#int-islide-imasterslide-bool}
Вставляет копию указанного исходного слайда в указанную позицию коллекции.  
Соответствующий макет будет выбран автоматически из указанного  
мастера (соответствующим считается макет с тем же типом или именем, что  
у макета исходного слайда). Если подходящий макет отсутствует, то  
макет исходного слайда будет клонирован (если allowCloneMissingLayout  
истина) или будет выброшено исключение PptxEditException (если allowCloneMissingLayout  
ложно).

### Возвращаемое значение

Вставленный слайд.



```python
def insert_clone(self, index, source_slide, dest_master, allow_clone_missing_layout):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| index | **int** | Индекс нового слайда. |
| source_slide | [`ISlide`](/slides/python-net/ru/aspose.slides/islide) | Слайд для клонирования. |
| dest_master | [`IMasterSlide`](/slides/python-net/ru/aspose.slides/imasterslide) | Мастер-слайд для нового слайда. |
| allow_clone_missing_layout | **bool** | Если в указанном мастере нет подходящего макета, то макет <br/><br/>            исходного слайда будет клонирован (если allowCloneMissingLayout равно true) или <br/><br/>            будет выброшено исключение PptxEditException (если allowCloneMissingLayout равно false). |

### Исключения

| Исключение | Описание |
| :- | :- |
| [`PptxEditException`](/slides/python-net/ru/aspose.slides/pptxeditexception) | Выбрасывается, если в указанном мастере нет подходящего макета и allowCloneMissingLayout равно false. |



### См. также
* класс [`ILayoutSlide`](/slides/python-net/ru/aspose.slides/ilayoutslide)
* класс [`IMasterSlide`](/slides/python-net/ru/aspose.slides/imasterslide)
* класс [`ISlide`](/slides/python-net/ru/aspose.slides/islide)
* класс [`PptxEditException`](/slides/python-net/ru/aspose.slides/pptxeditexception)
* класс [`SlideCollection`](/slides/python-net/ru/aspose.slides/slidecollection)
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)