---
title: add_clone method
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides/imasterlayoutslidecollection/add_clone/
weight: 20
---
## add_clone(self, source_layout) {#ilayoutslide}
Voegt een kopie van een opgegeven lay-out-slide toe aan het einde van de collectie.

### Retour

Toegevoegde slide.



```python
def add_clone(self, source_layout):
    ...
```


| Parameter | Type | Beschrijving |
| :- | :- | :- |
| source_layout | [`ILayoutSlide`](/slides/python-net/nl/aspose.slides/ilayoutslide) | Slide om te klonen. |

### Opmerkingen

1) Nieuwe lay-out wordt gekoppeld aan de bovenliggende master-slide voor deze lay-out-slides-collectie.  
   Dit is dus het equivalent van kopiëren/plakken met de optie "Use Destination Theme" in PowerPoint.  
2) Het equivalent van deze methode is de methode **Aspose.Slides.IGlobalLayoutSlideCollection.AddClone(Aspose.Slides.ILayoutSlide,Aspose.Slide** toegankelijk via [`IPresentation.layout_slides`](/slides/python-net/nl/aspose.slides/ipresentation/layout_slides) eigenschap.



### Zie ook
* klasse [`ILayoutSlide`](/slides/python-net/nl/aspose.slides/ilayoutslide)
* klasse [`IMasterLayoutSlideCollection`](/slides/python-net/nl/aspose.slides/imasterlayoutslidecollection)
* module [`aspose.slides`](/slides/python-net/nl/aspose.slides)
* bibliotheek [`Aspose.Slides`](/slides/python-net)