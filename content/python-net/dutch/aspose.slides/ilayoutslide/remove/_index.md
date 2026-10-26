---
title: remove method
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides/ilayoutslide/remove/
weight: 60
---
## remove(self) {#}
Verwijdert layout uit de presentatie.

```python
def remove(self):
    ...
```

### Opmerkingen
Om het werpen van de PptxEditException te voorkomen, controleer eerst de HasDependingSlides-eigenschap van layout.

### Uitzonderingen

| Uitzondering | Beschrijving |
| :- | :- |
| [`PptxEditException`](/slides/python-net/nl/aspose.slides/pptxeditexception) | Wordt gegooid als de layout al uit de presentatie is verwijderd of als de layout in de presentatie wordt gebruikt (zijn <br/>            HasDependingSlides-eigenschap is true). |

### Zie ook
* klasse [`ILayoutSlide`](/slides/python-net/nl/aspose.slides/ilayoutslide)
* klasse [`PptxEditException`](/slides/python-net/nl/aspose.slides/pptxeditexception)
* module [`aspose.slides`](/slides/python-net/nl/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)