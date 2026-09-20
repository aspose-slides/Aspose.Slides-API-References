---
title: insert method
second_title: Aspose.Slides pro Python přes .NET API Reference
description: 
type: docs
url: /cs/aspose.slides/masterlayoutslidecollection/insert/
weight: 40
---
## insert(self, index, layout_type, layout_name) {#int-slidelayouttype-str}
Vloží nový snímek rozvržení na určenou pozici ve sbírce.

### Returns
Vložený snímek.

```python
def insert(self, index, layout_type, layout_name):
    ...
```

| Parametr | Typ | Popis |
| :- | :- | :- |
| index | **int** | Index nového snímku. |
| layout_type | [`SlideLayoutType`](/slides/python-net/cs/aspose.slides/slidelayouttype) | Typ rozvržení pro nové rozvržení.<br/><br/>            Podporované typy rozvržení: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom.<br/><br/>            Ostatní typy rozvržení nejsou momentálně podporovány: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layout_name | **str** | Název nového rozvržení. Pokud je předaný název již použit, bude vyhozena výjimka ArgumentException.<br/><br/>            Pokud je předán parametr None, název bude vygenerován automaticky podle předaného typu rozvržení <br/><br/>            (například "Title Slide" nebo "1_Title Slide", "2_..", atd.). |

### Remarks
Vložené rozvržení pro hodnotu SlideLayoutType.Custom parametru `layout_type` 
            neobsahuje žádné zástupné objekty ani tvary.

### Exceptions

| Výjimka | Popis |
| :- | :- |
| **RuntimeError(Proxy error(NotImplementedException))** | Vyvolána, pokud je předána nepodporovaná hodnota parametru `layout_type`. Typy rozvržení, které nyní nejsou podporovány: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| **RuntimeError(Proxy error(ArgumentException))** | Vyvolána, pokud je hodnota názvu rozvržení `layout_name` již použita v <br/>            této kolekci rozvržení. |

### See Also
* třída [`ILayoutSlide`](/slides/python-net/cs/aspose.slides/ilayoutslide)
* třída [`MasterLayoutSlideCollection`](/slides/python-net/cs/aspose.slides/masterlayoutslidecollection)
* výčtový typ [`SlideLayoutType`](/slides/python-net/cs/aspose.slides/slidelayouttype)
* modul [`aspose.slides`](/slides/python-net/cs/aspose.slides)
* knihovna [`Aspose.Slides`](/slides/python-net)