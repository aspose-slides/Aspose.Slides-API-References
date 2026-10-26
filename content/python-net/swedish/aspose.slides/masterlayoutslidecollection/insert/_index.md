---
title: insert method
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides/masterlayoutslidecollection/insert/
weight: 40
---
## insert(self, index, layout_type, layout_name) {#int-slidelayouttype-str}
Infogar en ny layoutbild på angiven position i samlingen.

### Returnerar

Infogad bild.



```python
def insert(self, index, layout_type, layout_name):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| index | **int** | Index för den nya bilden. |
| layout_type | [`SlideLayoutType`](/slides/python-net/sv/aspose.slides/slidelayouttype) | Layouttyp för en ny layout.<br/><br/>            Supported layout types: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom.<br/><br/>            Other layout types are not supported now: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layout_name | **str** | Namn för en ny layout. Om det angivna namnet redan används kastas ArgumentException.<br/><br/>            Om parametern None skickas in genereras namnet automatiskt med hänsyn till den angivna layouttypen <br/><br/>            (till exempel "Title Slide" eller "1_Title Slide", "2_..", etc.). |

### Anmärkningar

Infogad layout för värdet SlideLayoutType.Custom av `layout_type` 
            innehåller inga platshållare och inga former.

### Undantag

| Undantag | Beskrivning |
| :- | :- |
| **RuntimeError(Proxy error(NotImplementedException))** | Kastas om ett ej stödformat värde för parametern `layout_type` skickas. Layouttyper som för närvarande inte stöds: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| **RuntimeError(Proxy error(ArgumentException))** | Kastas om layoutnamnet `layout_name` redan är i bruk i <br/>            den här samlingen av layouter. |



### Se även
* klass [`ILayoutSlide`](/slides/python-net/sv/aspose.slides/ilayoutslide)
* klass [`MasterLayoutSlideCollection`](/slides/python-net/sv/aspose.slides/masterlayoutslidecollection)
* enumeration [`SlideLayoutType`](/slides/python-net/sv/aspose.slides/slidelayouttype)
* modul [`aspose.slides`](/slides/python-net/sv/aspose.slides)
* bibliotek [`Aspose.Slides`](/slides/python-net)