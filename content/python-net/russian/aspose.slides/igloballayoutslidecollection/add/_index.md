---
title: add method
second_title: Aspose.Slides для Python через .NET справка API
description: 
type: docs
url: /ru/aspose.slides/igloballayoutslidecollection/add/
weight: 10
---
## add(self, master, layout_type, layout_name) {#imasterslide-slidelayouttype-str}
Добавляет новый слайд макета в презентацию.

### Возвращаемое значение

Добавленный слайд.



```python
def add(self, master, layout_type, layout_name):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| master | [`IMasterSlide`](/slides/python-net/ru/aspose.slides/imasterslide) | Основной слайд для нового макета. |
| layout_type | [`SlideLayoutType`](/slides/python-net/ru/aspose.slides/slidelayouttype) | Тип макета для нового макета.<br/><br/>            Поддерживаемые типы макетов: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom.<br/><br/>            Другие типы макетов в данный момент не поддерживаются: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layout_name | **str** | Имя для нового макета. Если переданное имя уже используется, будет выброшено ArgumentException.<br/><br/>            Если передан параметр None, то имя генерируется автоматически в зависимости от переданного типа макета <br/><br/>            (например, "Title Slide" или "1_Title Slide", "2_..", и т.д.). |

### Примечания

1) Добавленный макет для значения SlideLayoutType.Custom параметра `layout_type`  
            не содержит заполнителей и фигур.  
2) Аналогом этого метода является метод **Aspose.Slides.IMasterLayoutSlideCollection.Add(Aspose.Slides.SlideLayoutType,Syste**  
            доступный через свойство [`IMasterSlide.layout_slides`](/slides/python-net/ru/aspose.slides/imasterslide/layout_slides).

### Исключения

| Исключение | Описание |
| :- | :- |
| **RuntimeError(Proxy error(NotImplementedException))** | Выбрасывается, если передано неподдерживаемое значение параметра `layout_type`. Типы макетов, которые в данный момент не поддерживаются: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| **RuntimeError(Proxy error(ArgumentNullException))** | Выбрасывается, если `master` равен None. |
| **RuntimeError(Proxy error(ArgumentException))** | Выбрасывается, если `master` относится к другой презентации. |
| **RuntimeError(Proxy error(ArgumentException))** | Выбрасывается, если значение имени макета `layout_name` уже используется в <br/>            коллекции макетов `master`. |



### См. также
* класс [`IGlobalLayoutSlideCollection`](/slides/python-net/ru/aspose.slides/igloballayoutslidecollection)
* класс [`ILayoutSlide`](/slides/python-net/ru/aspose.slides/ilayoutslide)
* класс [`IMasterSlide`](/slides/python-net/ru/aspose.slides/imasterslide)
* перечисление [`SlideLayoutType`](/slides/python-net/ru/aspose.slides/slidelayouttype)
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* библиотека [`Aspose.Slides`](/slides/python-net)