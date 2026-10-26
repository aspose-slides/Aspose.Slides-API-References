---
title: add method
second_title: Aspose.Slides Pythonhoz a .NET API referencia
description: 
type: docs
url: /hu/aspose.slides/imasterlayoutslidecollection/add/
weight: 10
---
## add(self, layout_type, layout_name) {#slidelayouttype-str}
Új elrendezésdiátét ad hozzá a gyűjtemény végéhez.

### Visszatér

Hozzáadott dia.

```python
def add(self, layout_type, layout_name):
    ...
```

| Paraméter | Típus | Leírás |
| :- | :- | :- |
| layout_type | [`SlideLayoutType`](/slides/python-net/hu/aspose.slides/slidelayouttype) | Új elrendezéshez tartozó elrendezéstípus.<br/><br/>            Támogatott elrendezéstípusok: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom.<br/><br/>            Egyéb elrendezéstípusok jelenleg nem támogatottak: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layout_name | **str** | Az új elrendezés neve. Ha a megadott név már használatban van, akkor ArgumentException keletkezik.<br/><br/>            Ha a None paramétert adjuk meg, akkor a név automatikusan generálódik a megadott elrendezéstípus alapján <br/><br/>            (például "Title Slide" vagy "1_Title Slide", "2_..", stb.). |

### Megjegyzések

1) A `layout_type` értékének SlideLayoutType.Custom esetén hozzáadott elrendezés nem tartalmaz helyőrzőket és alakzatokat.
2) Ennek a metódusnak az analógja a 
            **Aspose.Slides.IGlobalLayoutSlideCollection.Add(Aspose.Slides.IMasterSlide,Aspose.Slides.SlideLayoutType,Syste**
            amely a [`IPresentation.layout_slides`](/slides/python-net/hu/aspose.slides/ipresentation/layout_slides) tulajdonsággal érhető el.

### Kivételek

| Kivétel | Leírás |
| :- | :- |
| **RuntimeError(Proxy error(NotImplementedException))** | Kivétel, ha nem támogatott `layout_type` érték kerül átadásra. Jelenleg nem támogatott elrendezéstípusok: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| **RuntimeError(Proxy error(ArgumentException))** | Kivétel, ha a `layout_name` érték már használatban van ebben az elrendezésgyűjteményben. |

### Lásd még
* osztály [`ILayoutSlide`](/slides/python-net/hu/aspose.slides/ilayoutslide)
* osztály [`IMasterLayoutSlideCollection`](/slides/python-net/hu/aspose.slides/imasterlayoutslidecollection)
* enumeráció [`SlideLayoutType`](/slides/python-net/hu/aspose.slides/slidelayouttype)
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)