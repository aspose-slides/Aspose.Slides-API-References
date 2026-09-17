---
title: write_shape_start method
second_title: Aspose.Slides für Python via .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides.export/embedallfontshtmlcontroller/write_shape_start/
weight: 70
---
## write_shape_start(self, generator, shape) {#ihtmlgenerator-ishape}
Wird vor dem Rendern der shape aufgerufen. Wird einmal pro shape aufgerufen. Wenn diese Funktion etwas in den generator schreibt, wird die aktuelle Folienbildgenerierung abgeschlossen, das hinzugefügte HTML-Fragment eingefügt und ein neues Bild über dem vorherigen gestartet.


```python
def write_shape_start(self, generator, shape):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| generator | [`IHtmlGenerator`](/slides/python-net/de/aspose.slides.export/ihtmlgenerator) | Ausgabeobjekt. |
| shape | [`IShape`](/slides/python-net/de/aspose.slides/ishape) | Shape, die gerade gerendert werden soll. |



### Siehe auch
* Klasse [`EmbedAllFontsHtmlController`](/slides/python-net/de/aspose.slides.export/embedallfontshtmlcontroller)
* Klasse [`IHtmlGenerator`](/slides/python-net/de/aspose.slides.export/ihtmlgenerator)
* Klasse [`IShape`](/slides/python-net/de/aspose.slides/ishape)
* Modul [`aspose.slides.export`](/slides/python-net/de/aspose.slides.export)
* Bibliothek [`Aspose.Slides`](/slides/python-net)