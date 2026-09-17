---
title: write_shape_end method
second_title: Aspose.Slides für Python via .NET API Referenz
description: 
type: docs
url: /de/aspose.slides.export/ihtmlformattingcontroller/write_shape_end/
weight: 30
---
## write_shape_end(self, generator, shape) {#ihtmlgenerator-ishape}
Wird vor der Renderung von shape aufgerufen. Wird einmal pro shape aufgerufen. Wenn diese Funktion irgendetwas in generator schreibt, wird die aktuelle Folienbildgenerierung abgeschlossen, das hinzugefügte html-Fragment eingefügt und ein neues Bild oberhalb des vorherigen gestartet.


```python
def write_shape_end(self, generator, shape):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| generator | [`IHtmlGenerator`](/slides/python-net/de/aspose.slides.export/ihtmlgenerator) | Ausgabeobjekt. |
| shape | [`IShape`](/slides/python-net/de/aspose.slides/ishape) | Shape, das zuletzt gerendert wird. |



### Siehe auch
* Klasse [`IHtmlFormattingController`](/slides/python-net/de/aspose.slides.export/ihtmlformattingcontroller)
* Klasse [`IHtmlGenerator`](/slides/python-net/de/aspose.slides.export/ihtmlgenerator)
* Klasse [`IShape`](/slides/python-net/de/aspose.slides/ishape)
* Modul [`aspose.slides.export`](/slides/python-net/de/aspose.slides.export)
* Bibliothek [`Aspose.Slides`](/slides/python-net)