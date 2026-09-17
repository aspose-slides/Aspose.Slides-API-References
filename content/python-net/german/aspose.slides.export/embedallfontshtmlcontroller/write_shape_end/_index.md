---
title: write_shape_end method
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides.export/embedallfontshtmlcontroller/write_shape_end/
weight: 60
---
## write_shape_end(self, generator, shape) {#ihtmlgenerator-ishape}
Wird vor dem Rendern der Form aufgerufen. Wird für jede Form einmal aufgerufen. Wenn diese Funktion etwas in den Generator schreibt, wird die aktuelle Folienbildgenerierung beendet, das hinzugefügte HTML-Fragment eingefügt und ein neues Bild über dem vorherigen gestartet.

```python
def write_shape_end(self, generator, shape):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| generator | [`IHtmlGenerator`](/slides/python-net/de/aspose.slides.export/ihtmlgenerator) | Ausgabeobjekt. |
| shape | [`IShape`](/slides/python-net/de/aspose.slides/ishape) | Form, die zuletzt gerendert wird. |

### Siehe auch
* class [`EmbedAllFontsHtmlController`](/slides/python-net/de/aspose.slides.export/embedallfontshtmlcontroller)
* class [`IHtmlGenerator`](/slides/python-net/de/aspose.slides.export/ihtmlgenerator)
* class [`IShape`](/slides/python-net/de/aspose.slides/ishape)
* module [`aspose.slides.export`](/slides/python-net/de/aspose.slides.export)
* library [`Aspose.Slides`](/slides/python-net)