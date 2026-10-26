---
title: remove method
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides/ilayoutslidecollection/remove/
weight: 20
---
## remove(self, value) {#ilayoutslide}
Entfernt ein Layout aus der Sammlung.

```python
def remove(self, value):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| value | [`ILayoutSlide`](/slides/python-net/de/aspose.slides/ilayoutslide) | Die Layout-Folie, die aus der Sammlung entfernt werden soll. |

### Hinweise

1) Um das Werfen der PptxEditException zu vermeiden, prüfen Sie vorab die HasDependingSlides-Eigenschaft des Layouts.
2) Sie können außerdem die [`ILayoutSlide.remove`](/slides/python-net/de/aspose.slides/ilayoutslide/remove)-Methode verwenden, um den Code zu vereinfachen.

### Ausnahmen

| Ausnahme | Beschreibung |
| :- | :- |
| [`PptxEditException`](/slides/python-net/de/aspose.slides/pptxeditexception) | Wird ausgelöst, wenn das Layout in einer Präsentation verwendet wird (seine HasDependingSlides-Eigenschaft ist true). |

### Siehe auch
* Klasse [`ILayoutSlide`](/slides/python-net/de/aspose.slides/ilayoutslide)
* Klasse [`ILayoutSlideCollection`](/slides/python-net/de/aspose.slides/ilayoutslidecollection)
* Klasse [`PptxEditException`](/slides/python-net/de/aspose.slides/pptxeditexception)
* Modul [`aspose.slides`](/slides/python-net/de/aspose.slides)
* Bibliothek [`Aspose.Slides`](/slides/python-net)