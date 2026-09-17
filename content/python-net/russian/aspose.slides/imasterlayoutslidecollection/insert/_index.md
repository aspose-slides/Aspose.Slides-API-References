---
title: insert method
second_title: Aspose.Slides для Python через .NET справка API
description: 
type: docs
url: /ru/aspose.slides/imasterlayoutslidecollection/insert/
weight: 40
---
## insert(self, index, layout_type, layout_name) {#int-slidelayouttype-str}
Вставляет новый слайд макета в указанную позицию коллекции.

### Возврат

Вставленный слайд.



```python
def insert(self, index, layout_type, layout_name):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| index | **int** | Индекс нового слайда. |
| layout_type | [`SlideLayoutType`](/slides/python-net/ru/aspose.slides/slidelayouttype) | Тип макета для нового макета.<br/><br/>            Поддерживаемые типы макетов: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom.<br/><br/>            Другие типы макетов в данный момент не поддерживаются: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layout_name | **str** | Имя для нового макета. Если переданное имя уже используется, будет выброшено ArgumentException.<br/><br/>            Если параметр None передан, имя генерируется автоматически в зависимости от переданного типа макета <br/><br/>            (например, "Title Slide" или "1_Title Slide", "2_..", и т.д.). |

### Примечания

Вставленный макет для значения SlideLayoutType.Custom параметра `layout_type` не содержит заполнителей и фигур.

### Исключения

| Исключение | Описание |
| :- | :- |
| **RuntimeError(Proxy error(NotImplementedException))** | Выбрасывается, если передано неподдерживаемое значение параметра `layout_type`. Типы макетов, которые в данный момент не поддерживаются: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| **RuntimeError(Proxy error(ArgumentException))** | Выбрасывается, если значение имени макета `layout_name` уже используется в <br/>            этой коллекции макетов. |

### См. также
* класс [`ILayoutSlide`](/slides/python-net/ru/aspose.slides/ilayoutslide)
* класс [`IMasterLayoutSlideCollection`](/slides/python-net/ru/aspose.slides/imasterlayoutslidecollection)
* перечисление [`SlideLayoutType`](/slides/python-net/ru/aspose.slides/slidelayouttype)
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* библиотека [`Aspose.Slides`](/slides/python-net)