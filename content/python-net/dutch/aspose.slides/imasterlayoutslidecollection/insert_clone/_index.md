---
title: insert_clone method
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides/imasterlayoutslidecollection/insert_clone/
weight: 50
---
## insert_clone(self, index, source_layout) {#int-ilayoutslide}
Voegt een kopie van een opgegeven lay-out-slide toe op een opgegeven positie in de collectie.

### Retourwaarde

Ingevoegde slide.

```python
def insert_clone(self, index, source_layout):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| index | **int** | Index van de nieuwe slide. |
| source_layout | [`ILayoutSlide`](/slides/python-net/nl/aspose.slides/ilayoutslide) | Slide om te klonen. |

### Opmerkingen

De nieuwe lay-out wordt gekoppeld aan de bovenliggende master-slide voor deze lay-out-slides-verzameling.  
Dit is dus analoog aan kopiëren/plakken met de optie "Use Destination Theme" in PowerPoint.

### Zie ook
* klasse [`ILayoutSlide`](/slides/python-net/nl/aspose.slides/ilayoutslide)
* klasse [`IMasterLayoutSlideCollection`](/slides/python-net/nl/aspose.slides/imasterlayoutslidecollection)
* module [`aspose.slides`](/slides/python-net/nl/aspose.slides)
* bibliotheek [`Aspose.Slides`](/slides/python-net)