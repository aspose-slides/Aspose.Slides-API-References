---
title: insert method
second_title: Aspose.Slides dla Pythona – dokumentacja interfejsu API .NET
description: 
type: docs
url: /pl/aspose.slides/masterlayoutslidecollection/insert/
weight: 40
---
## insert(self, index, layout_type, layout_name) {#int-slidelayouttype-str}
Wstawia nowy slajd układu w określone miejsce w kolekcji.

### Zwraca

Wstawiony slajd.



```python
def insert(self, index, layout_type, layout_name):
    ...
```


| Parametr | Typ | Opis |
| :- | :- | :- |
| index | **int** | Indeks nowego slajdu. |
| layout_type | [`SlideLayoutType`](/slides/python-net/pl/aspose.slides/slidelayouttype) | Typ układu dla nowego układu.<br/><br/>            Obsługiwane typy układów: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom.<br/><br/>            Inne typy układów nie są obecnie obsługiwane: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layout_name | **str** | Nazwa dla nowego układu. Jeśli podana nazwa jest już używana, zostanie zgłoszony ArgumentException.<br/><br/>            Jeżeli przekazany jest parametr None, nazwa jest generowana automatycznie w zależności od podanego typu układu <br/><br/>            (na przykład "Title Slide" lub "1_Title Slide", "2_..", itp.). |

### Uwagi

Wstawiony układ dla wartości SlideLayoutType.Custom parametru `layout_type` nie zawiera pól zastępczych ani kształtów.

### Wyjątki

| Wyjątek | Opis |
| :- | :- |
| **RuntimeError(Proxy error(NotImplementedException))** | Zgłaszane, jeśli przekazano nieobsługiwaną wartość parametru `layout_type`. Typy układów, które nie są obecnie obsługiwane: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| **RuntimeError(Proxy error(ArgumentException))** | Zgłaszane, jeśli wartość nazwy układu `layout_name` jest już używana w tej kolekcji układów. |



### Zobacz również
* klasa [`ILayoutSlide`](/slides/python-net/pl/aspose.slides/ilayoutslide)
* klasa [`MasterLayoutSlideCollection`](/slides/python-net/pl/aspose.slides/masterlayoutslidecollection)
* enumeracja [`SlideLayoutType`](/slides/python-net/pl/aspose.slides/slidelayouttype)
* moduł [`aspose.slides`](/slides/python-net/pl/aspose.slides)
* biblioteka [`Aspose.Slides`](/slides/python-net)