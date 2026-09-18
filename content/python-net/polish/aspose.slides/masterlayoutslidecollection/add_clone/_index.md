---
title: add_clone method
second_title: Aspose.Slides dla Pythona za pośrednictwem .NET – Dokumentacja API
description: 
type: docs
url: /pl/aspose.slides/masterlayoutslidecollection/add_clone/
weight: 20
---
## add_clone(self, source_layout) {#ilayoutslide}
Dodaje kopię określonego slajdu układu na koniec kolekcji.

### Returns
Zwraca

Dodany slajd.

```python
def add_clone(self, source_layout):
    ...
```

| Parametr | Typ | Opis |
| :- | :- | :- |
| source_layout | [`ILayoutSlide`](/slides/python-net/pl/aspose.slides/ilayoutslide) | Slajd do sklonowania. |

### Remarks
Uwagi

1) Nowy układ będzie powiązany z nadrzędnym slajdem master dla tej kolekcji slajdów układu.
            Jest to odpowiednik kopiuj/wklej z opcją „Use Destination Theme” w PowerPoint.
            2) Odpowiednikiem tej metody jest metoda **Aspose.Slides.IGlobalLayoutSlideCollection.AddClone(Aspose.Slides.ILayoutSlide,Aspose.Slide**
            dostępna przez właściwość [`IPresentation.layout_slides`](/slides/python-net/pl/aspose.slides/ipresentation/layout_slides).

### See Also
Zobacz także
* klasa [`ILayoutSlide`](/slides/python-net/pl/aspose.slides/ilayoutslide)
* klasa [`MasterLayoutSlideCollection`](/slides/python-net/pl/aspose.slides/masterlayoutslidecollection)
* moduł [`aspose.slides`](/slides/python-net/pl/aspose.slides)
* biblioteka [`Aspose.Slides`](/slides/python-net)