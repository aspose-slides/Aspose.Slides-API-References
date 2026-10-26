---
title: write_shape_start method
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides.export/ihtmlformattingcontroller/write_shape_start/
weight: 40
---
## write_shape_start(self, generator, shape) {#ihtmlgenerator-ishape}
Kallas innan shape renderas. Kallas en gång för varje shape. Om den här funktionen skriver något till generator kommer den aktuella bildgenereringen för bildspelet att avslutas, det tillagda html-fragmentet infogas och en ny bild startas ovanpå den föregående.


```python
def write_shape_start(self, generator, shape):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| generator | [`IHtmlGenerator`](/slides/python-net/sv/aspose.slides.export/ihtmlgenerator) | Utdatobjekt. |
| shape | [`IShape`](/slides/python-net/sv/aspose.slides/ishape) | Shape som ska renderas. |



### Se även
* klass [`IHtmlFormattingController`](/slides/python-net/sv/aspose.slides.export/ihtmlformattingcontroller)
* klass [`IHtmlGenerator`](/slides/python-net/sv/aspose.slides.export/ihtmlgenerator)
* klass [`IShape`](/slides/python-net/sv/aspose.slides/ishape)
* modul [`aspose.slides.export`](/slides/python-net/sv/aspose.slides.export)
* bibliotek [`Aspose.Slides`](/slides/python-net)