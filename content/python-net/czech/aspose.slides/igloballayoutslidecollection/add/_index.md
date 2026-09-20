---
title: add method
second_title: Aspose.Slides pro Python pomocí .NET API Reference
description: 
type: docs
url: /cs/aspose.slides/igloballayoutslidecollection/add/
weight: 10
---
## add(self, master, layout_type, layout_name) {#imasterslide-slidelayouttype-str}
Přidá nový rozložení snímku do prezentace.

### Vrací

Přidaný snímek.



```python
def add(self, master, layout_type, layout_name):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| master | [`IMasterSlide`](/slides/python-net/cs/aspose.slides/imasterslide) | Hlavní snímek pro nové rozložení. |
| layout_type | [`SlideLayoutType`](/slides/python-net/cs/aspose.slides/slidelayouttype) | Typ rozložení pro nové rozložení.<br/><br/>            Podporované typy rozložení: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom.<br/><br/>            Ostatní typy rozložení nyní nejsou podporovány: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layout_name | **str** | Název pro nové rozložení. Pokud je předán název, který již je používán, bude vyhozena výjimka ArgumentException.<br/><br/>            Pokud je předán parametr None, bude název vygenerován automaticky vzhledem k předanému typu rozložení <br/><br/>            (například "Title Slide" nebo "1_Title Slide", "2_..", atd.). |

### Poznámky

1) Přidané rozložení pro hodnotu SlideLayoutType.Custom parametru `layout_type` 
            neobsahuje žádné zástupné symboly ani tvary.
2) Analogie této metody je metoda **Aspose.Slides.IMasterLayoutSlideCollection.Add(Aspose.Slides.SlideLayoutType,Syste**
            přístupná přes vlastnost [`IMasterSlide.layout_slides`](/slides/python-net/cs/aspose.slides/imasterslide/layout_slides).

### Výjimky

| Výjimka | Popis |
| :- | :- |
| **RuntimeError(Proxy error(NotImplementedException))** | Vyvoláno, pokud je předána nepodporovaná hodnota parametru `layout_type`. Typy rozložení, které nyní nejsou podporovány: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| **RuntimeError(Proxy error(ArgumentNullException))** | Vyvoláno, pokud je `master` None. |
| **RuntimeError(Proxy error(ArgumentException))** | Vyvoláno, pokud `master` patří do jiné prezentace. |
| **RuntimeError(Proxy error(ArgumentException))** | Vyvoláno, pokud je hodnota názvu rozložení `layout_name` již použita ve <br/>            kolekci rozložení `master`. |



### Viz také
* class [`IGlobalLayoutSlideCollection`](/slides/python-net/cs/aspose.slides/igloballayoutslidecollection)
* class [`ILayoutSlide`](/slides/python-net/cs/aspose.slides/ilayoutslide)
* class [`IMasterSlide`](/slides/python-net/cs/aspose.slides/imasterslide)
* enumeration [`SlideLayoutType`](/slides/python-net/cs/aspose.slides/slidelayouttype)
* module [`aspose.slides`](/slides/python-net/cs/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)