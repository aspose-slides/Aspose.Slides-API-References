---
title: remove_at method
second_title: Aspose.Slides voor Python via .NET API Referentie
description: 
type: docs
url: /nl/aspose.slides/imasterlayoutslidecollection/remove_at/
weight: 70
---
## remove_at(self, index) {#int}
Verwijdert het element op de opgegeven index van de collectie.

```python
def remove_at(self, index):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| index | **int** | De nulgebaseerde index van het element dat verwijderd moet worden. |

### Opmerkingen

1) Om een PptxEditException te voorkomen, controleer eerst de HasDependingSlides-eigenschap van layout.
2) Je kunt ook de [`ILayoutSlide.remove`](/slides/python-net/nl/aspose.slides/ilayoutslide/remove)-methode gebruiken om de code te vereenvoudigen.

### Uitzonderingen

| Uitzondering | Beschrijving |
| :- | :- |
| [`PptxEditException`](/slides/python-net/nl/aspose.slides/pptxeditexception) | Wordt gegooid als layout wordt gebruikt in de presentatie (de HasDependingSlides-eigenschap is true). |

### Zie ook
* klasse [`IMasterLayoutSlideCollection`](/slides/python-net/nl/aspose.slides/imasterlayoutslidecollection)
* klasse [`PptxEditException`](/slides/python-net/nl/aspose.slides/pptxeditexception)
* module [`aspose.slides`](/slides/python-net/nl/aspose.slides)
* bibliotheek [`Aspose.Slides`](/slides/python-net)