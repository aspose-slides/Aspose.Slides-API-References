---
title: add_clone method
second_title: Aspose.Slides Pythonhoz .NET-en keresztül API Referencia
description: 
type: docs
url: /hu/aspose.slides/masterlayoutslidecollection/add_clone/
weight: 20
---
## add_clone(self, source_layout) {#ilayoutslide}
Hozzáad egy másolatot a megadott elrendezés-diáról a gyűjtemény végéhez.

### Visszatérési érték

Hozzáadott dia.

```python
def add_clone(self, source_layout):
    ...
```

| Paraméter | Típus | Leírás |
| :- | :- | :- |
| source_layout | [`ILayoutSlide`](/slides/python-net/hu/aspose.slides/ilayoutslide) | Klónozandó dia. |

### Megjegyzés

1) Az új elrendezés összekapcsolásra kerül a szülő fő diával ebben az elrendezési diák gyűjteményében.  
   Ez az analógja a másolás/beillesztésnek a "Use Destination Theme" beállítással a PowerPointban.  
2) Ennek a metódusnak az analógja a **Aspose.Slides.IGlobalLayoutSlideCollection.AddClone(Aspose.Slides.ILayoutSlide,Aspose.Slide** metódus, amely a [`IPresentation.layout_slides`](/slides/python-net/hu/aspose.slides/ipresentation/layout_slides) tulajdonnal érhető el.

### Lásd még
* osztály [`ILayoutSlide`](/slides/python-net/hu/aspose.slides/ilayoutslide)
* osztály [`MasterLayoutSlideCollection`](/slides/python-net/hu/aspose.slides/masterlayoutslidecollection)
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)