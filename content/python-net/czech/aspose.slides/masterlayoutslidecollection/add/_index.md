---
title: add method
second_title: Aspose.Slides pro Python prostřednictvím .NET API Reference
description: 
type: docs
url: /cs/aspose.slides/masterlayoutslidecollection/add/
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
| layout_type | [`SlideLayoutType`](/slides/python-net/cs/aspose.slides/slidelayouttype) | Typ rozvržení pro nové rozvržení.<br/><br/>Podporované typy rozvržení: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom.<br/><br/>Další typy rozvržení nejsou nyní podporovány: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layout_name | **str** | Název pro nové rozvržení. Pokud je předaný název již používán, bude vyvolána výjimka ArgumentException.<br/><br/>Pokud je předán parametr None, pak je název generován automaticky vzhledem k předanému typu rozvržení<br/><br/>(například "Title Slide" nebo "1_Title Slide", "2_..", atd.). |

### Poznámky

1) Přidané rozvržení pro hodnotu SlideLayoutType.Custom parametru `layout_type` neobsahuje žádné zástupné znaky ani tvary. 2) Analogie této metody je metoda **Aspose.Slides.IGlobalLayoutSlideCollection.Add(Aspose.Slides.IMasterSlide,Aspose.Slides.SlideLayoutType,Syste** přístupná pomocí vlastnosti [`IPresentation.layout_slides`](/slides/python-net/cs/aspose.slides/ipresentation/layout_slides).

### Výjimky

| Výjimka | Popis |
| :- | :- |
| **RuntimeError(Proxy error(NotImplementedException))** | Vyvolána, pokud je předána nepodporovaná hodnota parametru `layout_type`. Typy rozvržení, které nejsou nyní podporovány: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| **RuntimeError(Proxy error(ArgumentException))** | Vyvolána, pokud je hodnota názvu rozvržení `layout_name` již použita v <br/>            této kolekci rozvržení. |



### Viz také
* třída [`ILayoutSlide`](/slides/python-net/cs/aspose.slides/ilayoutslide)
* třída [`MasterLayoutSlideCollection`](/slides/python-net/cs/aspose.slides/masterlayoutslidecollection)
* enumerace [`SlideLayoutType`](/slides/python-net/cs/aspose.slides/slidelayouttype)
* modul [`aspose.slides`](/slides/python-net/cs/aspose.slides)
* knihovna [`Aspose.Slides`](/slides/python-net)