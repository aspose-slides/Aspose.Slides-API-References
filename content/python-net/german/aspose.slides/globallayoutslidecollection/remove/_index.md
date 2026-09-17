---
title: remove method
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides/globallayoutslidecollection/remove/
weight: 40
---
## remove(self, value) {#ilayoutslide}
Entfernt ein Layout aus der Sammlung.

```python
def remove(self, value):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| value | [`ILayoutSlide`](/slides/python-net/de/aspose.slides/ilayoutslide) | Die Layout-Folien, die aus der Sammlung entfernt werden sollen. |

### Anmerkungen

1) Um das Werfen der PptxEditException zu vermeiden, prüfen Sie vorher die Eigenschaft HasDependingSlides des Layouts.  
2) Sie können außerdem die Methode [`ILayoutSlide.remove`](/slides/python-net/de/aspose.slides/ilayoutslide/remove) verwenden, um den Code zu vereinfachen.

### Ausnahmen

| Ausnahme | Beschreibung |
| :- | :- |
| [`PptxEditException`](/slides/python-net/de/aspose.slides/pptxeditexception) | Wird ausgelöst, wenn das Layout in der Präsentation verwendet wird (seine HasDependingSlides-Eigenschaft ist wahr). |

### Siehe auch
* Klasse [`GlobalLayoutSlideCollection`](/slides/python-net/de/aspose.slides/globallayoutslidecollection)
* Klasse [`ILayoutSlide`](/slides/python-net/de/aspose.slides/ilayoutslide)
* Klasse [`PptxEditException`](/slides/python-net/de/aspose.slides/pptxeditexception)
* Modul [`aspose.slides`](/slides/python-net/de/aspose.slides)
* Bibliothek [`Aspose.Slides`](/slides/python-net)