---
title: add method
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides/imasterlayoutslidecollection/add/
weight: 10
---
## add(self, layout_type, layout_name) {#slidelayouttype-str}
Lägger till en ny layoutslide i slutet av samlingen.

### Returnerar

Tillagd slide.

```python
def add(self, layout_type, layout_name):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| layout_type | [`SlideLayoutType`](/slides/python-net/sv/aspose.slides/slidelayouttype) | Layouttyp för en ny layout.<br/><br/>            Följande layouttyper stöds: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom.<br/><br/>            Andra layouttyper stöds för närvarande inte: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layout_name | **str** | Namn för en ny layout. Om det angivna namnet redan används, kommer ArgumentException att kastas.<br/><br/>            Om parametern None skickas, genereras namn automatiskt med hänsyn till angiven layouttyp <br/><br/>            (till exempel "Title Slide" eller "1_Title Slide", "2_..", osv.). |

### Anmärkningar

1) Tillagd layout för värdet SlideLayoutType.Custom av `layout_type` 
            innehåller inga platshållare och inga former.
2) Motsvarigheten till denna metod är 
            metod **Aspose.Slides.IGlobalLayoutSlideCollection.Add(Aspose.Slides.IMasterSlide,Aspose.Slides.SlideLayoutType,Syste**
            åtkomlig med [`IPresentation.layout_slides`](/slides/python-net/sv/aspose.slides/ipresentation/layout_slides)-egenskapen.

### Undantag

| Undantag | Beskrivning |
| :- | :- |
| **RuntimeError(Proxy error(NotImplementedException))** | Kastas om ett ej stödjat värde på parametern `layout_type` skickas. Layouttyper som för närvarande inte stöds: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| **RuntimeError(Proxy error(ArgumentException))** | Kastas om layoutnamnsvärdet `layout_name` redan används i <br/>            denna samling av layouter. |

### Se också
* klass [`ILayoutSlide`](/slides/python-net/sv/aspose.slides/ilayoutslide)
* klass [`IMasterLayoutSlideCollection`](/slides/python-net/sv/aspose.slides/imasterlayoutslidecollection)
* enumeration [`SlideLayoutType`](/slides/python-net/sv/aspose.slides/slidelayouttype)
* modul [`aspose.slides`](/slides/python-net/sv/aspose.slides)
* bibliotek [`Aspose.Slides`](/slides/python-net)