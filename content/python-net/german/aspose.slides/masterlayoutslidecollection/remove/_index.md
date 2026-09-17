---
title: remove method
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides/masterlayoutslidecollection/remove/
weight: 60
---
## remove(self, value) {#ilayoutslide}
Entfernt ein Layout aus der Sammlung.

```python
def remove(self, value):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| value | [`ILayoutSlide`](/slides/python-net/de/aspose.slides/ilayoutslide) | Das Layout-Folie, das aus der Sammlung entfernt werden soll. |

### Bemerkungen

1) Um das Werfen der PptxEditException zu vermeiden, prüfen Sie vorab die Eigenschaft HasDependingSlides des Layouts.  
2) Sie können auch die Methode [`ILayoutSlide.remove`](/slides/python-net/de/aspose.slides/ilayoutslide/remove) verwenden, um den Code zu vereinfachen.

### Ausnahmen

| Ausnahme | Beschreibung |
| :- | :- |
| [`PptxEditException`](/slides/python-net/de/aspose.slides/pptxeditexception) | Wird ausgelöst, wenn das Layout in der Präsentation verwendet wird (seine Eigenschaft HasDependingSlides ist wahr). |

### Siehe auch
* Klasse [`ILayoutSlide`](/slides/python-net/de/aspose.slides/ilayoutslide)
* Klasse [`MasterLayoutSlideCollection`](/slides/python-net/de/aspose.slides/masterlayoutslidecollection)
* Klasse [`PptxEditException`](/slides/python-net/de/aspose.slides/pptxeditexception)
* Modul [`aspose.slides`](/slides/python-net/de/aspose.slides)
* Bibliothek [`Aspose.Slides`](/slides/python-net)