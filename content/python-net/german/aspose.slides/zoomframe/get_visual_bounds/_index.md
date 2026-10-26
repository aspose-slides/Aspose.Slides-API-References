---
title: get_visual_bounds method
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides/zoomframe/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
Ermittelt die visuellen Begrenzungen der Form, die aus ihrem gerenderten Inhalt berechnet werden.

### Rückgabe

Ein [`RectangleF`](/slides/python-net/de/aspose.slides/rectanglef), das die visuellen Begrenzungen der Form in Folienkoordinaten darstellt.
```python
def get_visual_bounds(self):
    ...
```

### Bemerkungen

Das zurückgegebene Rechteck stellt die achsenbündigen Begrenzungen aller Inhalte dar,
             die von der Form während des Renderns im Folienkoordinatenraum erzeugt werden.

Diese Begrenzungen können von den Modellbegrenzungen der Form ([`Shape.x`](/slides/python-net/de/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/de/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/de/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/de/aspose.slides/shape/height)) und negative Koordinaten enthalten, wenn der gerenderte Inhalt über den Folienursprung hinausgeht.

Die visuellen Begrenzungen berücksichtigen renderbezogene Aspekte wie
             Transformationen (zum Beispiel Rotation), Strichbreite und Verbindungen, Textlayout und Überlauf, SmartArt-Geometrie und andere Layout-Effekte, die das endgültige gerenderte Erscheinungsbild der Form beeinflussen.

Die zurückgegebenen Begrenzungen werden nicht auf das Folienrechteck zugeschnitten.

### Siehe auch
* Klasse [`ZoomFrame`](/slides/python-net/de/aspose.slides/zoomframe)
* Klasse [`RectangleF`](/slides/python-net/de/aspose.slides/rectanglef)
* Modul [`aspose.slides`](/slides/python-net/de/aspose.slides)
* Bibliothek [`Aspose.Slides`](/slides/python-net)