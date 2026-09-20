---
title: insert method
second_title: Aspose.Slides pro Python pomocí .NET API Reference
description: 
type: docs
url: /cs/aspose.slides/imasterlayoutslidecollection/insert/
weight: 40
---
## insert(self, index, layout_type, layout_name) {#int-slidelayouttype-str}
Vloží nový snímek rozvržení na určenou pozici ve sbírce.

### Vrací

Vložený snímek.



```python
def insert(self, index, layout_type, layout_name):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| index | **int** | Index nového snímku. |
| layout_type | [`SlideLayoutType`](/slides/python-net/cs/aspose.slides/slidelayouttype) | Typ rozvržení pro nový rozvrh.<br/><br/>            Podporované typy rozvržení: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom.<br/><br/>            Ostatní typy rozvržení nejsou v současné době podporovány: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layout_name | **str** | Název nového rozvržení. Pokud je předaný název již používán, bude vyhozena výjimka ArgumentException.<br/><br/>            Pokud je předán parametr None, pak je název vygenerován automaticky na základě předaného typu rozvržení <br/><br/>            (například "Title Slide" nebo "1_Title Slide", "2_..", atd.). |

### Poznámky

Vložené rozvržení pro hodnotu SlideLayoutType.Custom parametru `layout_type` neobsahuje žádné zástupné symboly ani žádné tvary.

### Výjimky

| Výjimka | Popis |
| :- | :- |
| **RuntimeError(Proxy error(NotImplementedException))** | Vyhozena, pokud je předána nepodporovaná hodnota parametru `layout_type`. Typy rozvržení, které nejsou v současné době podporovány: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| **RuntimeError(Proxy error(ArgumentException))** | Vyhozena, pokud je hodnota názvu rozvržení `layout_name` již použita v této kolekci rozvržení. |



### Viz také
* třída [`ILayoutSlide`](/slides/python-net/cs/aspose.slides/ilayoutslide)
* třída [`IMasterLayoutSlideCollection`](/slides/python-net/cs/aspose.slides/imasterlayoutslidecollection)
* výčet [`SlideLayoutType`](/slides/python-net/cs/aspose.slides/slidelayouttype)
* modul [`aspose.slides`](/slides/python-net/cs/aspose.slides)
* knihovna [`Aspose.Slides`](/slides/python-net)