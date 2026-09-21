---
title: add_clone method
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides/globallayoutslidecollection/add_clone/
weight: 20
---
## add_clone(self, source_layout) {#ilayoutslide}
Voegt een kopie van een opgegeven lay-outdia toe aan de presentatie.

### Retourneert

Toegevoegde dia.



```python
def add_clone(self, source_layout):
    ...
```


| Parameter | Type | Beschrijving |
| :- | :- | :- |
| source_layout | [`ILayoutSlide`](/slides/python-net/nl/aspose.slides/ilayoutslide) | Dia om te klonen. |

### Opmerkingen

When cloning a layout between different presentations layout's master can be cloned too
            to keep source formatting.
            Internal registry is used to track automatically cloned masters to prevent creation of 
            multiple clones of the same master slide.
            Manual cloning of master slides will be neither prevented nor registered.


## add_clone(self, source_layout, dest_master) {#ilayoutslide-imasterslide}
Voegt een kopie van een opgegeven lay-outdia toe aan de presentatie.

### Retourneert

Toegevoegde dia.



```python
def add_clone(self, source_layout, dest_master):
    ...
```


| Parameter | Type | Beschrijving |
| :- | :- | :- |
| source_layout | [`ILayoutSlide`](/slides/python-net/nl/aspose.slides/ilayoutslide) | Dia om te klonen. |
| dest_master | [`IMasterSlide`](/slides/python-net/nl/aspose.slides/imasterslide) | Masterdia voor een nieuwe lay-out. |

### Opmerkingen

1) Nieuwe lay-out wordt gekoppeld aan de gedefinieerde master in de bestemmingspresentatie.
            Dit is dus analoog aan kopiëren/plakken met de optie "Use Destination Theme" option in PowerPoint.
            2) Analogue of this method is method **Aspose.Slides.IMasterLayoutSlideCollection.AddClone(Aspose.Slide**
            toegankelijk via de eigenschap [`IMasterSlide.layout_slides`](/slides/python-net/nl/aspose.slides/imasterslide/layout_slides).


### Zie ook
* klasse [`GlobalLayoutSlideCollection`](/slides/python-net/nl/aspose.slides/globallayoutslidecollection)
* klasse [`ILayoutSlide`](/slides/python-net/nl/aspose.slides/ilayoutslide)
* klasse [`IMasterSlide`](/slides/python-net/nl/aspose.slides/imasterslide)
* module [`aspose.slides`](/slides/python-net/nl/aspose.slides)
* bibliotheek [`Aspose.Slides`](/slides/python-net)