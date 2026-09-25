---
title: get_visual_bounds method
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides.smartart/smartart/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
Ermittelt die visuellen Begrenzungen der Form, berechnet aus ihrem gerenderten Inhalt.

### Rückgabewert

Ein [`RectangleF`](/slides/python-net/de/aspose.slides/rectanglef), das die visuellen Begrenzungen der Form in Folienkoordinaten darstellt.



```python
def get_visual_bounds(self):
    ...
```


### Hinweise
             Das zurückgegebene Rechteck stellt die achsen ausgerichteten Begrenzungen aller Inhalte dar
             erzeugt von der Form während des Renderns im Folienkoordinatenraum.

             Diese Begrenzungen können von den Modellbegrenzungen der Form abweichen
             ([`Shape.x`](/slides/python-net/de/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/de/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/de/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/de/aspose.slides/shape/height))
             und können negative Koordinaten enthalten, wenn der gerenderte Inhalt sich
             über den Folienursprung hinaus erstreckt.

             Die visuellen Begrenzungen berücksichtigen renderebezogene Aspekte wie
             Transformationen (zum Beispiel Rotation), Linienstärke und Verbindungen,
             Textlayout und Überlauf, SmartArt-Geometrie und weitere Layout-Effekte
             die das endgültige gerenderte Erscheinungsbild der Form beeinflussen.

             Die zurückgegebenen Begrenzungen werden nicht auf das Folienrechteck beschnitten.



### Siehe auch
* Klasse [`SmartArt`](/slides/python-net/de/aspose.slides.smartart/smartart)
* Klasse [`RectangleF`](/slides/python-net/de/aspose.slides/rectanglef)
* Modul [`aspose.slides.smartart`](/slides/python-net/de/aspose.slides.smartart)
* Bibliothek [`Aspose.Slides`](/slides/python-net)