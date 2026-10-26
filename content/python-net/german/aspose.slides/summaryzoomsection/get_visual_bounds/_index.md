---
title: get_visual_bounds method
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides/summaryzoomsection/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
Ermittelt die visuellen Begrenzungen der Form, die aus ihrem gerenderten Inhalt berechnet werden.

### Rückgabewert
Ein [`RectangleF`](/slides/python-net/de/aspose.slides/rectanglef), der die visuellen Begrenzungen der Form
             in Folienkoordinaten darstellt.

```python
def get_visual_bounds(self):
    ...
```

### Anmerkungen
Das zurückgegebene Rechteck stellt die achsenparallel ausgerichteten Begrenzungen sämtlichen Inhalts dar,
             der von der Form beim Rendern im Folienkoordinatensystem erzeugt wird.

Diese Begrenzungen können von den Modellbegrenzungen der Form ([`Shape.x`](/slides/python-net/de/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/de/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/de/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/de/aspose.slides/shape/height))
             und negative Koordinaten enthalten, wenn der gerenderte Inhalt über den Ursprung der Folie hinausreicht.

Die visuellen Begrenzungen berücksichtigen renderebezogene Aspekte wie
             Transformationen (z. B. Drehung), Strichstärke und -verbindungen,
             Textlayout und Überlauf, SmartArt-Geometrie sowie andere Layout-Effekte
             die das endgültige gerenderte Erscheinungsbild der Form beeinflussen.

Die zurückgegebenen Begrenzungen werden nicht auf das Folienrechteck beschränkt.

### Siehe auch
* Klasse [`SummaryZoomSection`](/slides/python-net/de/aspose.slides/summaryzoomsection)
* Klasse [`RectangleF`](/slides/python-net/de/aspose.slides/rectanglef)
* Modul [`aspose.slides`](/slides/python-net/de/aspose.slides)
* Bibliothek [`Aspose.Slides`](/slides/python-net)