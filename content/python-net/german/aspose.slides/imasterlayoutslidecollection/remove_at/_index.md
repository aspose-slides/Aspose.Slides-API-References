---
title: remove_at method
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides/imasterlayoutslidecollection/remove_at/
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

### Bemerkungen

1) Um das Werfen der PptxEditException zu vermeiden, prüfen Sie vorher die Eigenschaft HasDependingSlides des Layouts.  
2) Sie können auch die Methode [`ILayoutSlide.remove`](/slides/python-net/de/aspose.slides/ilayoutslide/remove) verwenden, um den Code zu vereinfachen.

### Ausnahmen

| Ausnahme | Beschreibung |
| :- | :- |
| [`PptxEditException`](/slides/python-net/de/aspose.slides/pptxeditexception) | Ausgelöst, wenn das Layout in einer Präsentation verwendet wird (seine Eigenschaft HasDependingSlides ist true). |

### Siehe auch
* Klasse [`IMasterLayoutSlideCollection`](/slides/python-net/de/aspose.slides/imasterlayoutslidecollection)
* Klasse [`PptxEditException`](/slides/python-net/de/aspose.slides/pptxeditexception)
* Modul [`aspose.slides`](/slides/python-net/de/aspose.slides)
* Bibliothek [`Aspose.Slides`](/slides/python-net)