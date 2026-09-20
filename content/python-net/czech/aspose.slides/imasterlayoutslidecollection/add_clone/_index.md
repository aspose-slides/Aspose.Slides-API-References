---
title: add_clone method
second_title: Aspose.Slides pro Python přes .NET API Reference
description: 
type: docs
url: /cs/aspose.slides/imasterlayoutslidecollection/add_clone/
weight: 20
---
## add_clone(self, source_layout) {#ilayoutslide}
Přidá kopii určeného snímku rozložení na konec kolekce.

### Návratová hodnota
Přidaný snímek.

```python
def add_clone(self, source_layout):
    ...
```

| Parametr | Typ | Popis |
| :- | :- | :- |
| source_layout | [`ILayoutSlide`](/slides/python-net/cs/aspose.slides/ilayoutslide) | Snímek ke klonování. |

### Poznámky
1) Nové rozložení bude propojeno s nadřazeným hlavním snímkem pro tuto kolekci snímků rozložení. Tedy jde o ekvivalent kopírování/vkládání s volbou "Use Destination Theme" v PowerPointu.  
2) Ekvivalent této metody je metoda **Aspose.Slides.IGlobalLayoutSlideCollection.AddClone(Aspose.Slides.ILayoutSlide,Aspose.Slide** přístupná pomocí vlastnosti [`IPresentation.layout_slides`](/slides/python-net/cs/aspose.slides/ipresentation/layout_slides).

### Viz také
* třída [`ILayoutSlide`](/slides/python-net/cs/aspose.slides/ilayoutslide)
* třída [`IMasterLayoutSlideCollection`](/slides/python-net/cs/aspose.slides/imasterlayoutslidecollection)
* modul [`aspose.slides`](/slides/python-net/cs/aspose.slides)
* knihovna [`Aspose.Slides`](/slides/python-net)