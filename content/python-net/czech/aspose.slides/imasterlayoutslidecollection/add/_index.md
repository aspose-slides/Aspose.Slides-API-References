---
title: add method
second_title: Aspose.Slides pro Python prostřednictvím .NET API Reference
description: 
type: docs
url: /cs/aspose.slides/imasterlayoutslidecollection/add/
weight: 10
---
## add(self, layout_type, layout_name) {#slidelayouttype-str}
Přidá nový snímek rozvržení na konec kolekce.

### Vrací

Přidaný snímek.



```python
def add(self, layout_type, layout_name):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| layout_type | [`SlideLayoutType`](/slides/python-net/cs/aspose.slides/slidelayouttype) | Typ rozvržení pro nové rozvržení.<br/><br/>            Supported layout types: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom.<br/><br/>            Other layout types are not supported now: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layout_name | **str** | Název pro nové rozvržení. Pokud je předaný název již používán, bude vyvolána výjimka ArgumentException.<br/><br/>            Pokud je předán parametr None, pak je název vygenerován automaticky na základě předaného typu rozvržení (například "Title Slide" nebo "1_Title Slide", "2_..", atd.). |

### Poznámky

1) Přidané rozvržení pro hodnotu SlideLayoutType.Custom parametru `layout_type` neobsahuje žádné zástupné symboly a žádné tvary.  
2) Analogie této metody je metoda **Aspose.Slides.IGlobalLayoutSlideCollection.Add(Aspose.Slides.IMasterSlide,Aspose.Slides.SlideLayoutType,Syste** přístupná prostřednictvím vlastnosti [`IPresentation.layout_slides`](/slides/python-net/cs/aspose.slides/ipresentation/layout_slides).

### Výjimky

| Výjimka | Popis |
| :- | :- |
| **RuntimeError(Proxy error(NotImplementedException))** | Vyvolána, pokud je předána nepodporovaná hodnota parametru `layout_type`. Typy rozvržení, které nejsou v současnosti podporovány: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| **RuntimeError(Proxy error(ArgumentException))** | Vyvolána, pokud je hodnota názvu rozvržení `layout_name` již v této kolekci rozvržení použita. |

### Viz také
* class [`ILayoutSlide`](/slides/python-net/cs/aspose.slides/ilayoutslide)
* class [`IMasterLayoutSlideCollection`](/slides/python-net/cs/aspose.slides/imasterlayoutslidecollection)
* enumeration [`SlideLayoutType`](/slides/python-net/cs/aspose.slides/slidelayouttype)
* module [`aspose.slides`](/slides/python-net/cs/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)