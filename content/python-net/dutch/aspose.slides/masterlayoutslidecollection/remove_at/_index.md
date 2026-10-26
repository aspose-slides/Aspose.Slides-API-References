---
title: remove_at method
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides/masterlayoutslidecollection/remove_at/
weight: 70
---
## remove_at(self, index) {#int}
Verwijdert het element op de gespecificeerde index van de collectie.


```python
def remove_at(self, index):
    ...
```


| Parameter | Type | Beschrijving |
| :- | :- | :- |
| index | **int** | The zero-based index of the element to remove. |

### Opmerkingen

1) Om het werpen van de PptxEditException te voorkomen, controleer vóóraf de HasDependingSlides-eigenschap van de lay-out.  
2) U kunt ook de [`ILayoutSlide.remove`](/slides/python-net/nl/aspose.slides/ilayoutslide/remove)-methode gebruiken om de code te vereenvoudigen.

### Uitzonderingen

| Uitzondering | Beschrijving |
| :- | :- |
| [`PptxEditException`](/slides/python-net/nl/aspose.slides/pptxeditexception) | Wordt gegooid als de lay-out wordt gebruikt in een presentatie (de HasDependingSlides-eigenschap is waar). |



### Zie ook
* klasse [`MasterLayoutSlideCollection`](/slides/python-net/nl/aspose.slides/masterlayoutslidecollection)
* klasse [`PptxEditException`](/slides/python-net/nl/aspose.slides/pptxeditexception)
* module [`aspose.slides`](/slides/python-net/nl/aspose.slides)
* bibliotheek [`Aspose.Slides`](/slides/python-net)