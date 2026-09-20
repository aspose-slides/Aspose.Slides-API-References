---
title: add method
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides/igloballayoutslidecollection/add/
weight: 10
---
## add(self, master, layout_type, layout_name) {#imasterslide-slidelayouttype-str}
Lägger till en ny layout-bild i presentationen.

### Returnerar

Tillagd bild.



```python
def add(self, master, layout_type, layout_name):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| master | [`IMasterSlide`](/slides/python-net/sv/aspose.slides/imasterslide) | Master-slide för en ny layout. |
| layout_type | [`SlideLayoutType`](/slides/python-net/sv/aspose.slides/slidelayouttype) | Layout-typ för en ny layout.<br/><br/>            Stödda layouttyper: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom.<br/><br/>            Andra layouttyper stöds för närvarande inte: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layout_name | **str** | Namn för en ny layout. Om det angivna namnet redan används kommer ArgumentException att kastas.<br/><br/>            Om parametern None skickas skapas ett namn automatiskt utifrån den angivna layout-typen <br/><br/>            (till exempel "Title Slide" eller "1_Title Slide", "2_..", etc.). |

### Anmärkningar

1) Layout som lagts till för värdet SlideLayoutType.Custom av `layout_type` 
            innehåller inga platshållare och inga former.
2) Motsvarigheten till denna metod är metod **Aspose.Slides.IMasterLayoutSlideCollection.Add(Aspose.Slides.SlideLayoutType,Syste** som nås via [`IMasterSlide.layout_slides`](/slides/python-net/sv/aspose.slides/imasterslide/layout_slides) egenskap.

### Undantag

| Undantag | Beskrivning |
| :- | :- |
| **RuntimeError(Proxy error(NotImplementedException))** | Kastas om ett ej stödt värde för parametern `layout_type` skickas. Layouttyper som för närvarande inte stöds: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| **RuntimeError(Proxy error(ArgumentNullException))** | Kastas om `master` är None. |
| **RuntimeError(Proxy error(ArgumentException))** | Kastas om `master` tillhör en annan presentation. |
| **RuntimeError(Proxy error(ArgumentException))** | Kastas om layoutnamnsvärdet `layout_name` redan används i <br/>            samlingen av layouter för `master`. |



### Se även
* class [`IGlobalLayoutSlideCollection`](/slides/python-net/sv/aspose.slides/igloballayoutslidecollection)
* class [`ILayoutSlide`](/slides/python-net/sv/aspose.slides/ilayoutslide)
* class [`IMasterSlide`](/slides/python-net/sv/aspose.slides/imasterslide)
* enumeration [`SlideLayoutType`](/slides/python-net/sv/aspose.slides/slidelayouttype)
* module [`aspose.slides`](/slides/python-net/sv/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)