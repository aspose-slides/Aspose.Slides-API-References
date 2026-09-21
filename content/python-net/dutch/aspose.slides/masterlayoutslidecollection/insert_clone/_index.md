---
title: insert_clone method
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides/masterlayoutslidecollection/insert_clone/
weight: 50
---
## insert_clone(self, index, source_layout) {#int-ilayoutslide}
Voegt een kopie van een opgegeven lay-outdia toe op een specifieke positie van de collectie.

### Retourwaarde

Ingevoegde dia.

```python
def insert_clone(self, index, source_layout):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| index | **int** | Index van de nieuwe dia. |
| source_layout | [`ILayoutSlide`](/slides/python-net/nl/aspose.slides/ilayoutslide) | Dia om te klonen. |

### Opmerkingen

Nieuwe lay-out wordt gekoppeld aan de bovenliggende master-dia voor deze lay-outdia-collectie.
            Dit is dus analoog aan kopiëren/plakken met de optie "Use Destination Theme" in PowerPoint.

### Zie ook
* klasse [`ILayoutSlide`](/slides/python-net/nl/aspose.slides/ilayoutslide)
* klasse [`MasterLayoutSlideCollection`](/slides/python-net/nl/aspose.slides/masterlayoutslidecollection)
* module [`aspose.slides`](/slides/python-net/nl/aspose.slides)
* bibliotheek [`Aspose.Slides`](/slides/python-net)