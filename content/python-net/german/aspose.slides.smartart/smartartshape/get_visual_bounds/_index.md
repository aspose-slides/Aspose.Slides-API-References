---
title: get_visual_bounds method
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides.smartart/smartartshape/get_visual_bounds/
weight: 60
---
## get_visual_bounds(self) {#}
Ermittelt die visuellen Grenzen der Form, die aus ihrem gerenderten Inhalt berechnet werden.

### Rückgabewert

Ein [`RectangleF`](/slides/python-net/de/aspose.slides/rectanglef), das die visuellen Grenzen der Form in Folienkoordinaten darstellt.



```python
def get_visual_bounds(self):
    ...
```


### Hinweise

Das zurückgegebene Rechteck stellt die achsen-ausgerichteten Grenzen aller Inhalte dar,
die von der Form während des Renderns im Folienkoordinatenraum erzeugt werden.

Diese Grenzen können von den Modellgrenzen der Form ([`Shape.x`](/slides/python-net/de/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/de/aspose.slides/shape/y),
[`Shape.width`](/slides/python-net/de/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/de/aspose.slides/shape/height))
abweichen und negative Koordinaten enthalten, wenn der gerenderte Inhalt über den Folienursprung hinausgeht.

Die visuellen Grenzen berücksichtigen renderebezogene Aspekte wie Transformationen (z. B. Drehung), Linienstärken und Verbindungen,
Textlayout und Überlauf, SmartArt-Geometrie sowie andere Layout-Effekte, die das endgültige gerenderte Aussehen der Form beeinflussen.

Die zurückgegebenen Grenzen sind nicht auf das Folienrechteck zugeschnitten.



### Siehe auch
* Klasse [`SmartArtShape`](/slides/python-net/de/aspose.slides.smartart/smartartshape)
* Klasse [`RectangleF`](/slides/python-net/de/aspose.slides/rectanglef)
* Modul [`aspose.slides.smartart`](/slides/python-net/de/aspose.slides.smartart)
* library [`Aspose.Slides`](/slides/python-net)