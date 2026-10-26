---
title: insert method
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides/imasterlayoutslidecollection/insert/
weight: 40
---
## insert(self, index, layout_type, layout_name) {#int-slidelayouttype-str}
Infogar en ny layoutbild på angiven position i samlingen.

### Returns
Inserted slide.

```python
def insert(self, index, layout_type, layout_name):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| index | **int** | Index för den nya bilden. |
| layout_type | [`SlideLayoutType`](/slides/python-net/sv/aspose.slides/slidelayouttype) | Layouttyp för en ny layout.<br/><br/>            Stödda layouttyper: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom.<br/><br/>            Andra layouttyper stöds inte för närvarande: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layout_name | **str** | Namn för en ny layout. Om det angivna namnet redan används kommer ArgumentException att kastas.<br/><br/>            Om parametern None skickas kommer namnet genereras automatiskt i förhållande till den angivna layouttypen <br/><br/>            (till exempel "Title Slide" eller "1_Title Slide", "2_..", osv.). |

### Remarks
Infogad layout för värdet SlideLayoutType.Custom av `layout_type` innehåller inga platshållare och inga former.

### Exceptions
| Undantag | Beskrivning |
| :- | :- |
| **RuntimeError(Proxy error(NotImplementedException))** | Kastas om ett otillåtet värde för parametern `layout_type` skickas. Layouttyper som inte stöds för närvarande: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| **RuntimeError(Proxy error(ArgumentException))** | Kastas om layoutnamnet `layout_name` redan används i <br/>            denna samling av layouter. |

### See Also
* klass [`ILayoutSlide`](/slides/python-net/sv/aspose.slides/ilayoutslide)
* klass [`IMasterLayoutSlideCollection`](/slides/python-net/sv/aspose.slides/imasterlayoutslidecollection)
* enumeration [`SlideLayoutType`](/slides/python-net/sv/aspose.slides/slidelayouttype)
* modul [`aspose.slides`](/slides/python-net/sv/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)