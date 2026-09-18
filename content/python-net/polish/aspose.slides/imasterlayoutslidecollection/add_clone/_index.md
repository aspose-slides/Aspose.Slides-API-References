---
title: add_clone method
second_title: Aspose.Slides dla Pythona poprzez .NET Referencja API
description: 
type: docs
url: /pl/aspose.slides/imasterlayoutslidecollection/add_clone/
weight: 20
---
## add_clone(self, source_layout) {#ilayoutslide}
Dodaje kopię określonego slajdu układu na koniec kolekcji.

### Zwraca

Dodany slajd.



```python
def add_clone(self, source_layout):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| source_layout | [`ILayoutSlide`](/slides/python-net/pl/aspose.slides/ilayoutslide) | Slajd do sklonowania. |

### Uwaga

1) Nowy układ będzie powiązany z nadrzędnym slajdem głównym dla tej kolekcji slajdów układu.  
   Jest to więc odpowiednik operacji kopiuj/wklej z opcją „Use Destination Theme” w programie PowerPoint.  
2) Odpowiednikiem tej metody jest metoda **Aspose.Slides.IGlobalLayoutSlideCollection.AddClone(Aspose.Slides.ILayoutSlide,Aspose.Slide** dostępna przez własność [`IPresentation.layout_slides`](/slides/python-net/pl/aspose.slides/ipresentation/layout_slides).



### Zobacz także
* klasa [`ILayoutSlide`](/slides/python-net/pl/aspose.slides/ilayoutslide)
* klasa [`IMasterLayoutSlideCollection`](/slides/python-net/pl/aspose.slides/imasterlayoutslidecollection)
* moduł [`aspose.slides`](/slides/python-net/pl/aspose.slides)
* biblioteka [`Aspose.Slides`](/slides/python-net)