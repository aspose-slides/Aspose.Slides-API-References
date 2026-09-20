---
title: add_clone method
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides/imasterlayoutslidecollection/add_clone/
weight: 20
---
## add_clone(self, source_layout) {#ilayoutslide}
Lägger till en kopia av en angiven layoutbild i slutet av samlingen.

### Returnerar

Tillagd bild.



```python
def add_clone(self, source_layout):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| source_layout | [`ILayoutSlide`](/slides/python-net/sv/aspose.slides/ilayoutslide) | Bild att klona. |

### Anmärkningar

1) Ny layout kommer att länkas till föräldermaster-bilden för den här layout-bilder-samlingen.
            Så detta är motsvarigheten till kopiera/klistra med alternativet "Use Destination Theme" i PowerPoint.
            2) Motsvarigheten till denna metod är metoden **Aspose.Slides.IGlobalLayoutSlideCollection.AddClone(Aspose.Slides.ILayoutSlide,Aspose.Slide**
            som nås via [`IPresentation.layout_slides`](/slides/python-net/sv/aspose.slides/ipresentation/layout_slides) egenskap.



### Se även
* klass [`ILayoutSlide`](/slides/python-net/sv/aspose.slides/ilayoutslide)
* klass [`IMasterLayoutSlideCollection`](/slides/python-net/sv/aspose.slides/imasterlayoutslidecollection)
* modul [`aspose.slides`](/slides/python-net/sv/aspose.slides)
* bibliotek [`Aspose.Slides`](/slides/python-net)