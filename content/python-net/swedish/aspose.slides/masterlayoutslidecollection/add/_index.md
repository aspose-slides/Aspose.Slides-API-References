---
title: add method
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides/masterlayoutslidecollection/add/
weight: 10
---
## add(self, layout_type, layout_name) {#slidelayouttype-str}
Lägger till en ny layoutbild i slutet av samlingen.

### Returns

Tillagd bild.



```python
def add(self, layout_type, layout_name):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| layout_type | [`SlideLayoutType`](/slides/python-net/sv/aspose.slides/slidelayouttype) | Layouttyp för en ny layout.<br/><br/>            Stödda layouttyper: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom.<br/><br/>            Andra layouttyper som för närvarande inte stöds: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layout_name | **str** | Namn för en ny layout. Om det angivna namnet redan används kommer ArgumentException att kastas.<br/><br/>            Om parametern None ges genereras namnet automatiskt utifrån den angivna layouttypen <br/><br/>            (till exempel "Title Slide" eller "1_Title Slide", "2_..", osv.). |

### Remarks

1) Tillagd layout för värdet SlideLayoutType.Custom av `layout_type` 
            innehåller inga platshållare och inga former.
2) Motsvarigheten till denna metod är 
            metod **Aspose.Slides.IGlobalLayoutSlideCollection.Add(Aspose.Slides.IMasterSlide,Aspose.Slides.SlideLayoutType,Syste**
            åtkomlig via [`IPresentation.layout_slides`](/slides/python-net/sv/aspose.slides/ipresentation/layout_slides)-egenskapen.

### Exceptions

| Undantag | Beskrivning |
| :- | :- |
| **RuntimeError(Proxy error(NotImplementedException))** | Kastas om ett ej stödt värde på parametern `layout_type` skickas. Layouttyper som för närvarande inte stöds: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| **RuntimeError(Proxy error(ArgumentException))** | Kastas om layoutnamnsvärdet `layout_name` redan är i bruk i <br/>            den här samlingen av layouter. |



### See Also
* klass [`ILayoutSlide`](/slides/python-net/sv/aspose.slides/ilayoutslide)
* klass [`MasterLayoutSlideCollection`](/slides/python-net/sv/aspose.slides/masterlayoutslidecollection)
* enumeration [`SlideLayoutType`](/slides/python-net/sv/aspose.slides/slidelayouttype)
* modul [`aspose.slides`](/slides/python-net/sv/aspose.slides)
* bibliotek [`Aspose.Slides`](/slides/python-net)