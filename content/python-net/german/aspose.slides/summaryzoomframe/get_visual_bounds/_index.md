---
title: get_visual_bounds method
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides/summaryzoomframe/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
Ermittelt die visuellen Begrenzungen der Form, die aus ihrem gerenderten Inhalt berechnet werden.

### Rückgabewert

Ein [`RectangleF`](/slides/python-net/de/aspose.slides/rectanglef), das die visuellen Begrenzungen der Form in Folienkoordinaten darstellt.



```python
def get_visual_bounds(self):
    ...
```


### Bemerkungen

Das zurückgegebene Rechteck stellt die Achsen-ausgerichteten Begrenzungen aller Inhalte dar, die von der Form während des Renderns im Folienkoordinatensystem erzeugt werden.

Diese Begrenzungen können von den Modellbegrenzungen der Form ([`Shape.x`](/slides/python-net/de/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/de/aspose.slides/shape/y), [`Shape.width`](/slides/python-net/de/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/de/aspose.slides/shape/height)) abweichen und negative Koordinaten enthalten, wenn der gerenderte Inhalt über den Ursprung der Folie hinausgeht.

Die visuellen Begrenzungen berücksichtigen Rendering-bezogene Aspekte wie Transformationen (z. B. Drehung), Strichbreite und -verbindungen, Textlayout und Überlauf, SmartArt-Geometrie sowie weitere Layout-Effekte, die das endgültige gerenderte Aussehen der Form beeinflussen.

Die zurückgegebenen Begrenzungen werden nicht auf das Folienrechteck beschnitten.



### Siehe auch
* Klasse [`SummaryZoomFrame`](/slides/python-net/de/aspose.slides/summaryzoomframe)
* Klasse [`RectangleF`](/slides/python-net/de/aspose.slides/rectanglef)
* Modul [`aspose.slides`](/slides/python-net/de/aspose.slides)
* Bibliothek [`Aspose.Slides`](/slides/python-net)