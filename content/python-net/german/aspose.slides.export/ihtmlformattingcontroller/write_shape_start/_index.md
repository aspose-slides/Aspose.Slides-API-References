---
title: write_shape_start method
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides.export/ihtmlformattingcontroller/write_shape_start/
weight: 40
---
## write_shape_start(self, generator, shape) {#ihtmlgenerator-ishape}
Wird aufgerufen, bevor die Form gerendert wird. Wird einmal pro jeder Form aufgerufen. Wenn diese Funktion etwas in den Generator schreibt, wird die aktuelle Folienbildgenerierung beendet, das hinzugefügte HTML-Fragment eingefügt und ein neues Bild über dem vorherigen gestartet.


```python
def write_shape_start(self, generator, shape):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| generator | [`IHtmlGenerator`](/slides/python-net/de/aspose.slides.export/ihtmlgenerator) | Ausgabeobjekt. |
| shape | [`IShape`](/slides/python-net/de/aspose.slides/ishape) | Form, die gerade gerendert werden soll. |



### Siehe auch
* Klasse [`IHtmlFormattingController`](/slides/python-net/de/aspose.slides.export/ihtmlformattingcontroller)
* Klasse [`IHtmlGenerator`](/slides/python-net/de/aspose.slides.export/ihtmlgenerator)
* Klasse [`IShape`](/slides/python-net/de/aspose.slides/ishape)
* Modul [`aspose.slides.export`](/slides/python-net/de/aspose.slides.export)
* Bibliothek [`Aspose.Slides`](/slides/python-net)