---
title: write_shape_end method
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides.export/ihtmlformattingcontroller/write_shape_end/
weight: 30
---
## write_shape_end(self, generator, shape) {#ihtmlgenerator-ishape}
Kallas innan shape's rendering. Kallas en gång per varje shape. Om den här funktionen skriver något till generator, avslutas den aktuella bildgenereringen för bilden, det tillagda html fragmentet infogas och en ny bild påbörjas ovanpå den föregående.

```python
def write_shape_end(self, generator, shape):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| generator | [`IHtmlGenerator`](/slides/python-net/sv/aspose.slides.export/ihtmlgenerator) | Utdatobjekt. |
| shape | [`IShape`](/slides/python-net/sv/aspose.slides/ishape) | Shape som renderas sist. |

### Se också
* klass [`IHtmlFormattingController`](/slides/python-net/sv/aspose.slides.export/ihtmlformattingcontroller)
* klass [`IHtmlGenerator`](/slides/python-net/sv/aspose.slides.export/ihtmlgenerator)
* klass [`IShape`](/slides/python-net/sv/aspose.slides/ishape)
* modul [`aspose.slides.export`](/slides/python-net/sv/aspose.slides.export)
* bibliotek [`Aspose.Slides`](/slides/python-net)