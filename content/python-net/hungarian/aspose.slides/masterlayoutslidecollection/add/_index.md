---
title: add method
second_title: Aspose.Slides a Pythonhoz .NET-en keresztül API Referencia
description: 
type: docs
url: /hu/aspose.slides/masterlayoutslidecollection/add/
weight: 10
---
## add(self, layout_type, layout_name) {#slidelayouttype-str}
Új elrendezésdiát ad a gyűjtemény végéhez.

### Returns
Hozzáadott dia.

```python
def add(self, layout_type, layout_name):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| layout_type | [`SlideLayoutType`](/slides/python-net/hu/aspose.slides/slidelayouttype) | Új elrendezéshez tartozó elrendezéstípus.<br/><br/>            Támogatott elrendezéstípusok: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom.<br/><br/>            Jelenleg nem támogatott elrendezéstípusok: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layout_name | **str** | Az új elrendezés neve. Ha a megadott név már használatban van, ArgumentException kerül dobásra.<br/><br/>            Ha a None paramétert adják meg, a név automatikusan a megadott elrendezéstípus alapján kerül generálásra <br/><br/>            (például "Title Slide" vagy "1_Title Slide", "2_..", stb.). |

### Remarks
1) A `layout_type` értékének SlideLayoutType.Custom esetén hozzáadott elrendezés nem tartalmaz helyőrzőket és alakzatokat. 2) Ennek a metódusnak az analógiája a **Aspose.Slides.IGlobalLayoutSlideCollection.Add(Aspose.Slides.IMasterSlide,Aspose.Slides.SlideLayoutType,Syste** metódus, amely a [`IPresentation.layout_slides`](/slides/python-net/hu/aspose.slides/ipresentation/layout_slides) tulajdonnal érhető el.

### Exceptions
| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(NotImplementedException))** | Az `layout_type` paraméter nem támogatott értékének megadása esetén dobódik. Jelenleg nem támogatott elrendezéstípusok: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| **RuntimeError(Proxy error(ArgumentException))** | Az `layout_name` elrendezésnév már használatban van ebben az elrendezések gyűjteményében, ezért dobódik. |

### See Also
* osztály [`ILayoutSlide`](/slides/python-net/hu/aspose.slides/ilayoutslide)
* osztály [`MasterLayoutSlideCollection`](/slides/python-net/hu/aspose.slides/masterlayoutslidecollection)
* enumeráció [`SlideLayoutType`](/slides/python-net/hu/aspose.slides/slidelayouttype)
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)