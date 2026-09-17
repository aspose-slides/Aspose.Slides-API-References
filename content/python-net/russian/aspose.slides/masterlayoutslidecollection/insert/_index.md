---
title: insert method
second_title: Aspose.Slides для Python через .NET Справочник API
description: 
type: docs
url: /ru/aspose.slides/masterlayoutslidecollection/insert/
weight: 40
---
## insert(self, index, layout_type, layout_name) {#int-slidelayouttype-str}
Вставляет новый слайд-макет в указанную позицию коллекции.

### Возвращает
Вставленный слайд.

```python
def insert(self, index, layout_type, layout_name):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| index | **int** | Индекс нового слайда. |
| layout_type | [`SlideLayoutType`](/slides/python-net/ru/aspose.slides/slidelayouttype) | Тип макета для нового макета.<br/><br/>            Поддерживаемые типы макетов: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom.<br/><br/>            Другие типы макетов в настоящее время не поддерживаются: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layout_name | **str** | Имя нового макета. Если переданное имя уже используется, будет выброшено исключение ArgumentException.<br/><br/>            Если передан параметр None, имя будет сгенерировано автоматически в соответствии с переданным типом макета <br/><br/>            (например "Title Slide" или "1_Title Slide", "2_..", и т.д.). |

### Примечания
Вставленный макет для значения SlideLayoutType.Custom параметра `layout_type` не содержит заполнителей и фигур.

### Исключения

| Исключение | Описание |
| :- | :- |
| **RuntimeError(Proxy error(NotImplementedException))** | Выбрасывается, если передано неподдерживаемое значение параметра `layout_type`. Типы макетов, которые в настоящее время не поддерживаются: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| **RuntimeError(Proxy error(ArgumentException))** | Выбрасывается, если значение имени макета `layout_name` уже используется в <br/>            этой коллекции макетов. |

### См. также
* класс [`ILayoutSlide`](/slides/python-net/ru/aspose.slides/ilayoutslide)
* класс [`MasterLayoutSlideCollection`](/slides/python-net/ru/aspose.slides/masterlayoutslidecollection)
* перечисление [`SlideLayoutType`](/slides/python-net/ru/aspose.slides/slidelayouttype)
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* библиотека [`Aspose.Slides`](/slides/python-net)