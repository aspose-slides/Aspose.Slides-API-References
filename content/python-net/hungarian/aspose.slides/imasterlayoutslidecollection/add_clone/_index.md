---
title: add_clone method
second_title: Aspose.Slides Pythonhoz .NET-en keresztül API hivatkozás
description: 
type: docs
url: /hu/aspose.slides/imasterlayoutslidecollection/add_clone/
weight: 20
---
## add_clone(self, source_layout) {#ilayoutslide}
Hozzáad egy megadott elrendezési dia másolatát a gyűjtemény végéhez.

### Visszatérési érték

Hozzáadott dia.



```python
def add_clone(self, source_layout):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| source_layout | [`ILayoutSlide`](/slides/python-net/hu/aspose.slides/ilayoutslide) | Clonálandó dia. |

### Megjegyzések

1) Az új elrendezés a szülő fő diához lesz kapcsolva ebben az elrendezési diasorozat gyűjteményben.
            Ez egyenértékű a másolás/beillesztés "Use Destination Theme" opcióval a PowerPointban.
            2) Az e módszer analógiája a **Aspose.Slides.IGlobalLayoutSlideCollection.AddClone(Aspose.Slides.ILayoutSlide,Aspose.Slide** metódus, amely a [`IPresentation.layout_slides`](/slides/python-net/hu/aspose.slides/ipresentation/layout_slides) tulajdonnal érhető el.



### Lásd még
* osztály [`ILayoutSlide`](/slides/python-net/hu/aspose.slides/ilayoutslide)
* osztály [`IMasterLayoutSlideCollection`](/slides/python-net/hu/aspose.slides/imasterlayoutslidecollection)
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)