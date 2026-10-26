---
title: write_shape_start method
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides.export/embedallfontshtmlcontroller/write_shape_start/
weight: 70
---
## write_shape_start(self, generator, shape) {#ihtmlgenerator-ishape}
Kallas innan shape renderas. Kallas en gång för varje shape. Om denna funktion skriver något till generator kommer den aktuella bildgenereringen för slidern att avslutas, det tillagda HTML-fragmentet infogas och en ny bild startas ovanpå den föregående.

```python
def write_shape_start(self, generator, shape):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| generator | [`IHtmlGenerator`](/slides/python-net/sv/aspose.slides.export/ihtmlgenerator) | Utdataobjekt. |
| shape | [`IShape`](/slides/python-net/sv/aspose.slides/ishape) | Shape som håller på att renderas. |

### Se även
* klass [`EmbedAllFontsHtmlController`](/slides/python-net/sv/aspose.slides.export/embedallfontshtmlcontroller)
* klass [`IHtmlGenerator`](/slides/python-net/sv/aspose.slides.export/ihtmlgenerator)
* klass [`IShape`](/slides/python-net/sv/aspose.slides/ishape)
* modul [`aspose.slides.export`](/slides/python-net/sv/aspose.slides.export)
* bibliotek [`Aspose.Slides`](/slides/python-net)