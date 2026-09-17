---
title: remove_at method
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides/masterlayoutslidecollection/remove_at/
weight: 70
---
## remove_at(self, index) {#int}
Entfernt das Element am angegebenen Index der Sammlung.

```python
def remove_at(self, index):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| index | **int** | Der nullbasierte Index des zu entfernenden Elements. |

### Hinweise

1) Um das Auslösen der PptxEditException zu vermeiden, prüfen Sie vorher die Eigenschaft HasDependingSlides des Layouts.
2) Sie können auch die Methode [`ILayoutSlide.remove`](/slides/python-net/de/aspose.slides/ilayoutslide/remove) verwenden, um den Code zu vereinfachen.

### Ausnahmen

| Ausnahme | Beschreibung |
| :- | :- |
| [`PptxEditException`](/slides/python-net/de/aspose.slides/pptxeditexception) | Wird ausgelöst, wenn das Layout in einer Präsentation verwendet wird (seine HasDependingSlides Eigenschaft ist true). |

### Siehe auch
* Klasse [`MasterLayoutSlideCollection`](/slides/python-net/de/aspose.slides/masterlayoutslidecollection)
* Klasse [`PptxEditException`](/slides/python-net/de/aspose.slides/pptxeditexception)
* Modul [`aspose.slides`](/slides/python-net/de/aspose.slides)
* Bibliothek [`Aspose.Slides`](/slides/python-net)