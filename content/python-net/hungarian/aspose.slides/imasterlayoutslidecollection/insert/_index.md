---
title: insert method
second_title: Aspose.Slides a Pythonhoz .NET API referencia
description: 
type: docs
url: /hu/aspose.slides/imasterlayoutslidecollection/insert/
weight: 40
---
## insert(self, index, layout_type, layout_name) {#int-slidelayouttype-str}
Beszúr egy új elrendezési diát a gyűjtemény megadott pozíciójába.

### Visszatérési érték

Beszúrt dia.

```python
def insert(self, index, layout_type, layout_name):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| index | **int** | Az új dia indexe. |
| layout_type | [`SlideLayoutType`](/slides/python-net/hu/aspose.slides/slidelayouttype) | Az új elrendezés típusa.<br/><br/>            Támogatott elrendezéstípusok: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom.<br/><br/>            Jelenleg nem támogatott egyéb elrendezéstípusok: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layout_name | **str** | Az új elrendezés neve. Ha a megadott név már használatban van, ArgumentException kerül dobásra.<br/><br/>            Ha a None paraméter kerül átadásra, akkor a név automatikusan generálódik a megadott elrendezéstípus alapján <br/><br/>            (például "Title Slide" vagy "1_Title Slide", "2_..", stb.). |

### Megjegyzés

A `layout_type` SlideLayoutType.Custom értékéhez beszúrt elrendezés nem tartalmaz helyőrzőket és alakzatokat.

### Kivételek

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(NotImplementedException))** | Kivétel kerül dobásra, ha a `layout_type` paraméterhez nem támogatott érték kerül megadásra. Jelenleg nem támogatott elrendezéstípusok: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| **RuntimeError(Proxy error(ArgumentException))** | Kivétel kerül dobásra, ha a `layout_name` elrendezésnév már használatban van <br/>            ebben az elrendezések gyűjteményében. |

### Lásd még
* osztály [`ILayoutSlide`](/slides/python-net/hu/aspose.slides/ilayoutslide)
* osztály [`IMasterLayoutSlideCollection`](/slides/python-net/hu/aspose.slides/imasterlayoutslidecollection)
* felsorolás [`SlideLayoutType`](/slides/python-net/hu/aspose.slides/slidelayouttype)
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)