---
title: remove_at method
second_title: Aspose.Slides für Python via .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides/masterslidecollection/remove_at/
weight: 40
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

Um das Werfen der PptxEditException zu vermeiden, prüfen Sie vorher die Eigenschaft HasDependingSlides des Masters.

### Ausnahmen

| Ausnahme | Beschreibung |
| :- | :- |
| [`PptxEditException`](/slides/python-net/de/aspose.slides/pptxeditexception) | Wird ausgelöst, wenn der zu entfernende Master in der Präsentation verwendet wird (seine HasDependingSlides-Eigenschaft ist wahr). |

### Siehe auch
* class [`MasterSlideCollection`](/slides/python-net/de/aspose.slides/masterslidecollection)
* class [`PptxEditException`](/slides/python-net/de/aspose.slides/pptxeditexception)
* module [`aspose.slides`](/slides/python-net/de/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)