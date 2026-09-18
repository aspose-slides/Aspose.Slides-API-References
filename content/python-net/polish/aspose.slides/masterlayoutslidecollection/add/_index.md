---
title: add method
second_title: Aspose.Slides dla Pythona poprzez .NET – dokumentacja API
description: 
type: docs
url: /pl/aspose.slides/masterlayoutslidecollection/add/
weight: 10
---
## add(self, layout_type, layout_name) {#slidelayouttype-str}
Dodaje nowy slajd układu na koniec kolekcji.

### Zwraca

Dodany slajd.



```python
def add(self, layout_type, layout_name):
    ...
```


| Parametr | Typ | Opis |
| :- | :- | :- |
| layout_type | [`SlideLayoutType`](/slides/python-net/pl/aspose.slides/slidelayouttype) | Typ układu dla nowego układu.<br/><br/>            Obsługiwane typy układów: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom.<br/><br/>            Inne typy układów nie są obecnie obsługiwane: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layout_name | **str** | Nazwa dla nowego układu. Jeśli podana nazwa jest już używana, zostanie rzucony ArgumentException.<br/><br/>            Jeśli przekazany zostanie parametr None, nazwa zostanie wygenerowana automatycznie w zależności od podanego typu układu <br/><br/>            (na przykład “Title Slide” lub “1_Title Slide”, “2_..”, itd.). |

### Uwagi

1) Dodany układ dla wartości SlideLayoutType.Custom parametru `layout_type` 
            nie zawiera żadnych pól zastępczych ani kształtów.
2) Odpowiednikiem tej metody jest 
            metoda **Aspose.Slides.IGlobalLayoutSlideCollection.Add(Aspose.Slides.IMasterSlide,Aspose.Slides.SlideLayoutType,Syste**
            dostępna za pośrednictwem właściwości [`IPresentation.layout_slides`](/slides/python-net/pl/aspose.slides/ipresentation/layout_slides).

### Wyjątki

| Wyjątek | Opis |
| :- | :- |
| **RuntimeError(Proxy error(NotImplementedException))** | Rzucany, jeśli przekazana zostanie nieobsługiwana wartość parametru `layout_type`. Typy układów, które nie są obecnie obsługiwane: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| **RuntimeError(Proxy error(ArgumentException))** | Rzucany, jeśli wartość nazwy układu `layout_name` jest już używana w <br/>            tej kolekcji układów. |

### Zobacz także
* klasa [`ILayoutSlide`](/slides/python-net/pl/aspose.slides/ilayoutslide)
* klasa [`MasterLayoutSlideCollection`](/slides/python-net/pl/aspose.slides/masterlayoutslidecollection)
* enumeracja [`SlideLayoutType`](/slides/python-net/pl/aspose.slides/slidelayouttype)
* moduł [`aspose.slides`](/slides/python-net/pl/aspose.slides)
* biblioteka [`Aspose.Slides`](/slides/python-net)