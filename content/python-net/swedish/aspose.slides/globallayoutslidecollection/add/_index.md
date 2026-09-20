---
title: add method
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides/globallayoutslidecollection/add/
weight: 10
---
## add(self, master, layout_type, layout_name) {#imasterslide-slidelayouttype-str}
Lägger till en ny layoutbild i presentationen.

### Returns
Tillagd bild.

```python
def add(self, master, layout_type, layout_name):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| master | [`IMasterSlide`](/slides/python-net/sv/aspose.slides/imasterslide) | Masterbild för en ny layout. |
| layout_type | [`SlideLayoutType`](/slides/python-net/sv/aspose.slides/slidelayouttype) | Layouttyp för en ny layout.<br/><br/>            Stödda layouttyper: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom.<br/><br/>            Andra layouttyper stöds för närvarande inte: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layout_name | **str** | Namn för en ny layout. Om det angivna namnet redan används kommer ArgumentException att kastas.<br/><br/>            Om parametern None skickas så genereras namn automatiskt baserat på den angivna layouttypen <br/><br/>            (till exempel "Title Slide" eller "1_Title Slide", "2_..", osv.). |

### Remarks
1) Tillagd layout för värdet SlideLayoutType.Custom av `layout_type` 
            innehåller inga platshållare och inga former.
2) Motsvarigheten till denna metod är metoden **Aspose.Slides.IMasterLayoutSlideCollection.Add(Aspose.Slides.SlideLayoutType,Syste**
            åtkomlig via [`IMasterSlide.layout_slides`](/slides/python-net/sv/aspose.slides/imasterslide/layout_slides)-egenskapen.

### Exceptions
| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(NotImplementedException))** | Kastas om ett ej stödjande värde för parametern `layout_type` skickas. Layouttyper som för närvarande inte stöds: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| **RuntimeError(Proxy error(ArgumentNullException))** | Kastas om `master` är None. |
| **RuntimeError(Proxy error(ArgumentException))** | Kastas om `master` tillhör en annan presentation. |
| **RuntimeError(Proxy error(ArgumentException))** | Kastas om layoutnamns-värdet `layout_name` redan är i bruk i <br/>            samlingen av layouter för `master`. |

### See Also
* klass [`GlobalLayoutSlideCollection`](/slides/python-net/sv/aspose.slides/globallayoutslidecollection)
* klass [`ILayoutSlide`](/slides/python-net/sv/aspose.slides/ilayoutslide)
* klass [`IMasterSlide`](/slides/python-net/sv/aspose.slides/imasterslide)
* enumeration [`SlideLayoutType`](/slides/python-net/sv/aspose.slides/slidelayouttype)
* modul [`aspose.slides`](/slides/python-net/sv/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)