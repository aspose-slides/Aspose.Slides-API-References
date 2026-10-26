---
title: add method
second_title: Aspose.Slides pro Python přes .NET – referenční příručka API
description: 
type: docs
url: /cs/aspose.slides/globallayoutslidecollection/add/
weight: 10
---
## add(self, master, layout_type, layout_name) {#imasterslide-slidelayouttype-str}
Přidá nový snímek rozložení do prezentace.

### Návratová hodnota

Přidaný snímek.



```python
def add(self, master, layout_type, layout_name):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| master | [`IMasterSlide`](/slides/python-net/cs/aspose.slides/imasterslide) | Hlavní snímek pro nové rozložení. |
| layout_type | [`SlideLayoutType`](/slides/python-net/cs/aspose.slides/slidelayouttype) | Typ rozložení pro nové rozložení.<br/><br/>            Podporované typy rozložení: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom.<br/><br/>            Jiné typy rozložení nejsou nyní podporovány: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layout_name | **str** | Název pro nové rozložení. Pokud je předaný název již používán, bude vyhozena výjimka ArgumentException.<br/><br/>            Pokud je předán parametr None, bude název vygenerován automaticky podle předaného typu rozložení (například "Title Slide" nebo "1_Title Slide", "2_..", atd.). |

### Poznámky

1) Přidané rozložení pro hodnotu SlideLayoutType.Custom parametru `layout_type` neobsahuje žádné zástupné symboly ani tvary.  
2) Analogie této metody je metoda **Aspose.Slides.IMasterLayoutSlideCollection.Add(Aspose.Slides.SlideLayoutType,Syste** přístupná pomocí vlastnosti [`IMasterSlide.layout_slides`](/slides/python-net/cs/aspose.slides/imasterslide/layout_slides).

### Výjimky

| Výjimka | Popis |
| :- | :- |
| **RuntimeError(Proxy error(NotImplementedException))** | Vyvolána, pokud je předána nepodporovaná hodnota parametru `layout_type`. Typy rozložení, které nejsou nyní podporovány: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| **RuntimeError(Proxy error(ArgumentNullException))** | Vyvolána, pokud je `master` None. |
| **RuntimeError(Proxy error(ArgumentException))** | Vyvolána, pokud `master` patří do jiné prezentace. |
| **RuntimeError(Proxy error(ArgumentException))** | Vyvolána, pokud je hodnota názvu rozložení `layout_name` již použita ve sbírce rozložení `master`. |

### Viz také
* třída [`GlobalLayoutSlideCollection`](/slides/python-net/cs/aspose.slides/globallayoutslidecollection)
* třída [`ILayoutSlide`](/slides/python-net/cs/aspose.slides/ilayoutslide)
* třída [`IMasterSlide`](/slides/python-net/cs/aspose.slides/imasterslide)
* výčtové typy [`SlideLayoutType`](/slides/python-net/cs/aspose.slides/slidelayouttype)
* modul [`aspose.slides`](/slides/python-net/cs/aspose.slides)
* knihovna [`Aspose.Slides`](/slides/python-net)