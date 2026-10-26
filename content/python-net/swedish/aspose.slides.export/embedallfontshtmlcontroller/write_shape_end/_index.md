---
title: write_shape_end method
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides.export/embedallfontshtmlcontroller/write_shape_end/
weight: 60
---
## write_shape_end(self, generator, shape) {#ihtmlgenerator-ishape}
Kallas innan formens rendering. Kallas en gång för varje form. Om den här funktionen skriver något till generatorn, avslutas den aktuella bildgenereringen för bilden, det tillagda html-fragmentet infogas och en ny bild startas ovanpå den föregående.


```python
def write_shape_end(self, generator, shape):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| generator | [`IHtmlGenerator`](/slides/python-net/sv/aspose.slides.export/ihtmlgenerator) | Utdataobjekt. |
| shape | [`IShape`](/slides/python-net/sv/aspose.slides/ishape) | Form som renderas sist. |



### Se även
* klass [`EmbedAllFontsHtmlController`](/slides/python-net/sv/aspose.slides.export/embedallfontshtmlcontroller)
* klass [`IHtmlGenerator`](/slides/python-net/sv/aspose.slides.export/ihtmlgenerator)
* klass [`IShape`](/slides/python-net/sv/aspose.slides/ishape)
* modul [`aspose.slides.export`](/slides/python-net/sv/aspose.slides.export)
* library [`Aspose.Slides`](/slides/python-net)