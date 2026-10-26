---
title: remove method
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides/layoutslide/remove/
weight: 60
---
## remove(self) {#}
Entfernt das Layout aus der Präsentation.


```python
def remove(self):
    ...
```


### Hinweise

Um das Werfen der PptxEditException zu vermeiden, prüfen Sie vorher die HasDependingSlides-Eigenschaft des Layouts.

### Ausnahmen

| Ausnahme | Beschreibung |
| :- | :- |
| [`PptxEditException`](/slides/python-net/de/aspose.slides/pptxeditexception) | Wird ausgelöst, wenn das Layout bereits aus der Präsentation entfernt wurde oder wenn das Layout in der Präsentation verwendet wird (seine <br/>            HasDependingSlides-Eigenschaft ist true). |



### Siehe auch
* Klasse [`LayoutSlide`](/slides/python-net/de/aspose.slides/layoutslide)
* Klasse [`PptxEditException`](/slides/python-net/de/aspose.slides/pptxeditexception)
* Modul [`aspose.slides`](/slides/python-net/de/aspose.slides)
* Bibliothek [`Aspose.Slides`](/slides/python-net)