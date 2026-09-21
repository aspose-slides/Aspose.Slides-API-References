---
title: remove method
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides/layoutslide/remove/
weight: 60
---
## remove(self) {#}
Verwijdert layout uit de presentatie.


```python
def remove(self):
    ...
```


### Opmerkingen

Om de PptxEditException te voorkomen, controleer de HasDependingSlides-eigenschap van layout van tevoren.

### Uitzonderingen

| Uitzondering | Beschrijving |
| :- | :- |
| [`PptxEditException`](/slides/python-net/nl/aspose.slides/pptxeditexception) | Wordt gegooid als layout al uit de presentatie is verwijderd of als layout wordt gebruikt in de presentatie (de <br/>            HasDependingSlides property is true). |



### Zie ook
* klasse [`LayoutSlide`](/slides/python-net/nl/aspose.slides/layoutslide)
* klasse [`PptxEditException`](/slides/python-net/nl/aspose.slides/pptxeditexception)
* module [`aspose.slides`](/slides/python-net/nl/aspose.slides)
* bibliotheek [`Aspose.Slides`](/slides/python-net)