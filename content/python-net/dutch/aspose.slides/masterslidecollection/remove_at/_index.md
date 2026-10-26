---
title: remove_at method
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides/masterslidecollection/remove_at/
weight: 40
---
## remove_at(self, index) {#int}
Verwijdert het element op de opgegeven index van de collectie.


```python
def remove_at(self, index):
    ...
```


| Parameter | Type | Beschrijving |
| :- | :- | :- |
| index | **int** | De nulgebaseerde index van het te verwijderen element. |

### Opmerkingen

Om het werpen van de PptxEditException te voorkomen, controleer eerst de master's HasDependingSlides property before.

### Uitzonderingen

| Uitzondering | Beschrijving |
| :- | :- |
| [`PptxEditException`](/slides/python-net/nl/aspose.slides/pptxeditexception) | Wordt gegooid als de te verwijderen master wordt gebruikt in presentatie (its HasDependingSlides property is true). |



### Zie ook
* klasse [`MasterSlideCollection`](/slides/python-net/nl/aspose.slides/masterslidecollection)
* klasse [`PptxEditException`](/slides/python-net/nl/aspose.slides/pptxeditexception)
* module [`aspose.slides`](/slides/python-net/nl/aspose.slides)
* bibliotheek [`Aspose.Slides`](/slides/python-net)