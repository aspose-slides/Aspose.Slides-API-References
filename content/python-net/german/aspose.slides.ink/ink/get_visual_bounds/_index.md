---
title: get_visual_bounds method
second_title: Aspose.Slides für Python via .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides.ink/ink/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
Ermittelt die visuellen Grenzen der Form, die aus ihrem gerenderten Inhalt berechnet werden.

### Rückgabewert

Ein [`RectangleF`](/slides/python-net/de/aspose.slides/rectanglef) das die visuellen Grenzen der Form
             in Folienkoordinaten.

```python
def get_visual_bounds(self):
    ...
```

### Bemerkungen

Das zurückgegebene Rechteck stellt die achsen-aligierten Grenzen aller Inhalte
            dar, die vom Shape während des Renderns im Folienkoordinatenraum erzeugt werden.

Diese Grenzen können von den Modellgrenzen des Shapes abweichen
            ([`Shape.x`](/slides/python-net/de/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/de/aspose.slides/shape/y),
            [`Shape.width`](/slides/python-net/de/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/de/aspose.slides/shape/height))
            und können negative Koordinaten enthalten, wenn der gerenderte Inhalt
            über den Ursprung der Folie hinausgeht.

Die visuellen Grenzen berücksichtigen renderbezogene Aspekte wie
            Transformationen (zum Beispiel Drehung), Strichstärke und Verbindungen,
            Textlayout und Überlauf, SmartArt-Geometrie und andere Layout-Effekte,
            die das endgültige gerenderte Erscheinungsbild der Form beeinflussen.

Die zurückgegebenen Grenzen sind nicht auf das Folienrechteck gekürzt.

### Siehe auch
* class [`Ink`](/slides/python-net/de/aspose.slides.ink/ink)
* class [`RectangleF`](/slides/python-net/de/aspose.slides/rectanglef)
* module [`aspose.slides.ink`](/slides/python-net/de/aspose.slides.ink)
* library [`Aspose.Slides`](/slides/python-net)