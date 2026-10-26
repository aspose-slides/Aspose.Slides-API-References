---
title: add method
second_title: Aspose.Slides для Python через .NET Справочник API
description: 
type: docs
url: /ru/aspose.slides/masterlayoutslidecollection/add/
weight: 10
---
## add(self, layout_type, layout_name) {#slidelayouttype-str}
Добавляет новый слайд макета в конец коллекции.

### Возвращаемое значение

Добавленный слайд.

```python
def add(self, layout_type, layout_name):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| layout_type | [`SlideLayoutType`](/slides/python-net/ru/aspose.slides/slidelayouttype) | Тип макета для нового макета.<br/><br/>            Поддерживаемые типы макетов: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom.<br/><br/>            Другие типы макетов в настоящее время не поддерживаются: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layout_name | **str** | Имя для нового макета. Если переданное имя уже используется, будет выброшено ArgumentException.<br/><br/>            Если передан параметр None, имя генерируется автоматически в зависимости от переданного типа макета <br/><br/>            (например, "Title Slide" или "1_Title Slide", "2_..", и т.д.). |

### Примечания

1) Добавленный макет для значения SlideLayoutType.Custom параметра `layout_type` не содержит заполнителей и фигур.
2) Аналог этого метода – метод **Aspose.Slides.IGlobalLayoutSlideCollection.Add(Aspose.Slides.IMasterSlide,Aspose.Slides.SlideLayoutType,Syste** , доступный через свойство [`IPresentation.layout_slides`](/slides/python-net/ru/aspose.slides/ipresentation/layout_slides).

### Исключения

| Исключение | Описание |
| :- | :- |
| **RuntimeError(Proxy error(NotImplementedException))** | Выбрасывается, если передано неподдерживаемое значение параметра `layout_type`. Типы макетов, которые в настоящее время не поддерживаются: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| **RuntimeError(Proxy error(ArgumentException))** | Выбрасывается, если значение имени макета `layout_name` уже используется в этой коллекции макетов. |

### См. также
* класс [`ILayoutSlide`](/slides/python-net/ru/aspose.slides/ilayoutslide)
* класс [`MasterLayoutSlideCollection`](/slides/python-net/ru/aspose.slides/masterlayoutslidecollection)
* перечисление [`SlideLayoutType`](/slides/python-net/ru/aspose.slides/slidelayouttype)
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* библиотека [`Aspose.Slides`](/slides/python-net)