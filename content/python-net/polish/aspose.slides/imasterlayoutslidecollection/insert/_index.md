---
title: insert method
second_title: Aspose.Slides dla Pythona via .NET referencja API
description: 
type: docs
url: /pl/aspose.slides/imasterlayoutslidecollection/insert/
weight: 40
---
## insert(self, index, layout_type, layout_name) {#int-slidelayouttype-str}
Wstawia nowy slajd układu w określone miejsce kolekcji.

### Returns
Wstawiony slajd.

```python
def insert(self, index, layout_type, layout_name):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| index | **int** | Indeks nowego slajdu. |
| layout_type | [`SlideLayoutType`](/slides/python-net/pl/aspose.slides/slidelayouttype) | Typ układu dla nowego układu.<br/><br/>            Obsługiwane typy układów: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom.<br/><br/>            Inne typy układów nie są obecnie obsługiwane: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layout_name | **str** | Nazwa nowego układu. Jeśli podana nazwa jest już używana, zostanie zgłoszony ArgumentException.<br/><br/>            Jeśli parametr None zostanie przekazany, nazwa zostanie wygenerowana automatycznie w zależności od podanego typu układu <br/><br/>            (np. "Title Slide" lub "1_Title Slide", "2_..", itp.). |

### Remarks
Wstawiony układ o wartości SlideLayoutType.Custom parametru `layout_type` nie zawiera żadnych symboli zastępczych ani kształtów.

### Exceptions

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(NotImplementedException))** | Zgłaszany, gdy przekazano nieobsługiwaną wartość parametru `layout_type`. Typy układów, które nie są obsługiwane: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| **RuntimeError(Proxy error(ArgumentException))** | Zgłaszany, gdy wartość nazwy układu `layout_name` jest już używana w <br/>            tej kolekcji układów. |

### See Also
* class [`ILayoutSlide`](/slides/python-net/pl/aspose.slides/ilayoutslide)
* class [`IMasterLayoutSlideCollection`](/slides/python-net/pl/aspose.slides/imasterlayoutslidecollection)
* enumeration [`SlideLayoutType`](/slides/python-net/pl/aspose.slides/slidelayouttype)
* module [`aspose.slides`](/slides/python-net/pl/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)