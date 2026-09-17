---
title: insert_clone method
second_title: Справочник API Aspose.Slides для Python через .NET
description: 
type: docs
url: /ru/aspose.slides/islidecollection/insert_clone/
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

При клонировании слайда между различными презентациями мастер слайда также может быть клонирован.  
Внутренний реестр используется для отслеживания автоматически клонированных мастеров, чтобы предотвратить создание нескольких копий одного и того же мастер-слайда.  
Ручное клонирование мастер-слайдов ни предотвращается, ни регистрируется.  
Если вам нужен больший контроль над процессом клонирования, используйте  
**Aspose.Slides.ISlideCollection.InsertClone(System.Int32,Aspose.Slides.ISlide,Aspose.Slide** или  
**Aspose.Slides.ISlideCollection.InsertClone(System.Int32,Aspose.Slides.ISlide,Aspose.Slides.IMasterSlide,Syste** для клонирования слайдов и  
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
| dest_layout | [`ILayoutSlide`](/slides/python-net/ru/aspose.slides/ilayoutslide) | Слайд-макет для нового слайда. |

## insert_clone(self, index, source_slide, dest_master, allow_clone_missing_layout) {#int-islide-imasterslide-bool}
Вставляет копию указанного исходного слайда в указанную позицию коллекции.  
Подходящий макет будет выбран автоматически из указанного мастера (подходящий макет — это макет с тем же Type или Name, что и макет исходного слайда). Если подходящего макета нет, макет исходного слайда будет клонирован (если allowCloneMissingLayout равно true) или будет выброшено PptxEditException (если allowCloneMissingLayout равно false).

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
| allow_clone_missing_layout | **bool** | Если в указанном мастере нет подходящего макета, то макет <br/><br/> исходного слайда будет клонирован (если allowCloneMissingLayout равно true) или <br/><br/> будет выброшено PptxEditException (если allowCloneMissingLayout равно false). |

### Исключения

| Исключение | Описание |
| :- | :- |
| [`PptxEditException`](/slides/python-net/ru/aspose.slides/pptxeditexception) | Выбрасывается, если в указанном мастере нет подходящего макета и <br/> allowCloneMissingLayout равно false. |

### Смотрите также
* класс [`ILayoutSlide`](/slides/python-net/ru/aspose.slides/ilayoutslide)
* класс [`IMasterSlide`](/slides/python-net/ru/aspose.slides/imasterslide)
* класс [`ISlide`](/slides/python-net/ru/aspose.slides/islide)
* класс [`ISlideCollection`](/slides/python-net/ru/aspose.slides/islidecollection)
* класс [`PptxEditException`](/slides/python-net/ru/aspose.slides/pptxeditexception)
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* библиотека [`Aspose.Slides`](/slides/python-net)