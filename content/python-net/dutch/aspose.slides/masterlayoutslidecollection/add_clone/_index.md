---
title: add_clone method
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides/masterlayoutslidecollection/add_clone/
weight: 20
---
## add_clone(self, source_layout) {#ilayoutslide}
Voegt een kopie van een opgegeven layout-dia toe aan het einde van de collectie.

### Retour

Toegevoegde dia.



```python
def add_clone(self, source_layout):
    ...
```


| Parameter | Type | Beschrijving |
| :- | :- | :- |
| source_layout | [`ILayoutSlide`](/slides/python-net/nl/aspose.slides/ilayoutslide) | Dia om te klonen. |

### Opmerkingen

1) De nieuwe layout wordt gekoppeld aan de bovenliggende master-dia voor deze collectie layout-dia’s.  
   Dit is dus een equivalent van kopiëren/plakken met de optie "Use Destination Theme" in PowerPoint.  
2) Het equivalent van deze methode is methode **Aspose.Slides.IGlobalLayoutSlideCollection.AddClone(Aspose.Slides.ILayoutSlide,Aspose.Slide** toegankelijk via de [`IPresentation.layout_slides`](/slides/python-net/nl/aspose.slides/ipresentation/layout_slides)-eigenschap.



### Zie ook
* klasse [`ILayoutSlide`](/slides/python-net/nl/aspose.slides/ilayoutslide)
* klasse [`MasterLayoutSlideCollection`](/slides/python-net/nl/aspose.slides/masterlayoutslidecollection)
* module [`aspose.slides`](/slides/python-net/nl/aspose.slides)
* bibliotheek [`Aspose.Slides`](/slides/python-net)