---
title: add_clone method
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides/masterlayoutslidecollection/add_clone/
weight: 20
---
## add_clone(self, source_layout) {#ilayoutslide}
Lägger till en kopia av en specificerad layout-bild till slutet av samlingen.

### Returns

Tillagd bild.



```python
def add_clone(self, source_layout):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| source_layout | [`ILayoutSlide`](/slides/python-net/sv/aspose.slides/ilayoutslide) | Bild att klona. |

### Remarks

1) Den nya layouten kommer att länkas till den överordnade huvud-bilden för den här layout-bildsamlingen.  
   Så detta är motsvarigheten till kopiera/klistra in med alternativet "Use Destination Theme" i PowerPoint.  
2) Motsvarigheten till denna metod är metoden **Aspose.Slides.IGlobalLayoutSlideCollection.AddClone(Aspose.Slides.ILayoutSlide,Aspose.Slide** som nås med egenskapen [`IPresentation.layout_slides`](/slides/python-net/sv/aspose.slides/ipresentation/layout_slides).



### See Also
* klass [`ILayoutSlide`](/slides/python-net/sv/aspose.slides/ilayoutslide)
* klass [`MasterLayoutSlideCollection`](/slides/python-net/sv/aspose.slides/masterlayoutslidecollection)
* modul [`aspose.slides`](/slides/python-net/sv/aspose.slides)
* bibliotek [`Aspose.Slides`](/slides/python-net)