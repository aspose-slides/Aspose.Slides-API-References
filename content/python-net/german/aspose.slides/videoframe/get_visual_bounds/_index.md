---
title: get_visual_bounds method
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides/videoframe/get_visual_bounds/
weight: 60
---
## get_visual_bounds(self) {#}
Ermittelt die visuellen Begrenzungen der Form, die anhand ihres gerenderten Inhalts berechnet werden.

### Rückgabewert

Ein **aspose.slides.RectangleF**, das die visuellen Begrenzungen der Form in Folienkoordinaten darstellt.



```python
def get_visual_bounds(self):
    ...
```


### Anmerkungen
Das zurückgegebene Rechteck stellt die achsen-ausgerichteten Begrenzungen aller Inhalte
             dar, die von der Form beim Rendern im Folienkoordinatenraum erzeugt werden.

Diese Begrenzungen können von den Modellbegrenzungen der Form abweichen
             ([`Shape.x`](/slides/python-net/de/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/de/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/de/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/de/aspose.slides/shape/height))
             und können negative Koordinaten enthalten, wenn der gerenderte Inhalt über
             den Folienursprung hinausreicht.

Die visuellen Begrenzungen berücksichtigen renderebezogene Aspekte wie
             Transformationen (z. B. Rotation), Strichstärke und Verbindungsformen,
             Textlayout und Überlauf, SmartArt-Geometrie und andere Layout-Effekte
             die das endgültige gerenderte Erscheinungsbild der Form beeinflussen.

Die zurückgegebenen Begrenzungen werden nicht auf das Folienrechteck beschränkt.



### Siehe auch
* Klasse [`VideoFrame`](/slides/python-net/de/aspose.slides/videoframe)
* Modul [`aspose.slides`](/slides/python-net/de/aspose.slides)
* Bibliothek [`Aspose.Slides`](/slides/python-net)