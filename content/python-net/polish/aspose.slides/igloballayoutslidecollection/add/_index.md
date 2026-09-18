---
title: add method
second_title: Aspose.Slides dla Pythona za pośrednictwem .NET – dokumentacja API
description: 
type: docs
url: /pl/aspose.slides/igloballayoutslidecollection/add/
weight: 10
---
## add(self, master, layout_type, layout_name) {#imasterslide-slidelayouttype-str}
Dodaje nowy slajd układu do prezentacji.

### Zwraca

Dodany slajd.



```python
def add(self, master, layout_type, layout_name):
    ...
```


| Parametr | Typ | Opis |
| :- | :- | :- |
| master | [`IMasterSlide`](/slides/python-net/pl/aspose.slides/imasterslide) | Slajd główny dla nowego układu. |
| layout_type | [`SlideLayoutType`](/slides/python-net/pl/aspose.slides/slidelayouttype) | Typ układu dla nowego układu.<br/><br/>            Obsługiwane typy układów: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom.<br/><br/>            Inne typy układów nie są obecnie obsługiwane: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layout_name | **str** | Nazwa dla nowego układu. Jeśli podana nazwa jest już używana, zostanie zgłoszony ArgumentException.<br/><br/>            Jeśli przekazany jest parametr None, nazwa zostanie wygenerowana automatycznie w zależności od podanego typu układu (na przykład "Title Slide" lub "1_Title Slide", "2_..", itd.). |

### Uwagi

1) Dodany układ dla wartości SlideLayoutType.Custom w `layout_type` nie zawiera żadnych pól zastępczych ani kształtów.  
2) Odpowiednikiem tej metody jest metoda **Aspose.Slides.IMasterLayoutSlideCollection.Add(Aspose.Slides.SlideLayoutType,Syste** dostępna za pośrednictwem właściwości [`IMasterSlide.layout_slides`](/slides/python-net/pl/aspose.slides/imasterslide/layout_slides).

### Wyjątki

| Wyjątek | Opis |
| :- | :- |
| **RuntimeError(Proxy error(NotImplementedException))** | Rzucany, jeśli podano nieobsługiwaną wartość parametru `layout_type`. Typy układów, które nie są obecnie obsługiwane: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| **RuntimeError(Proxy error(ArgumentNullException))** | Rzucany, jeśli `master` jest równy None. |
| **RuntimeError(Proxy error(ArgumentException))** | Rzucany, jeśli `master` należy do innej prezentacji. |
| **RuntimeError(Proxy error(ArgumentException))** | Rzucany, jeśli wartość nazwy układu `layout_name` jest już używana w kolekcji układów `master`. |



### Zobacz także
* klasa [`IGlobalLayoutSlideCollection`](/slides/python-net/pl/aspose.slides/igloballayoutslidecollection)
* klasa [`ILayoutSlide`](/slides/python-net/pl/aspose.slides/ilayoutslide)
* klasa [`IMasterSlide`](/slides/python-net/pl/aspose.slides/imasterslide)
* enumeracja [`SlideLayoutType`](/slides/python-net/pl/aspose.slides/slidelayouttype)
* moduł [`aspose.slides`](/slides/python-net/pl/aspose.slides)
* biblioteka [`Aspose.Slides`](/slides/python-net)