---
title: get_visual_bounds method
second_title: Aspose.Slides für Python via .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides.smartart/smartart/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
Ermittelt die visuellen Begrenzungen der Form, die anhand ihres gerenderten Inhalts berechnet werden.

### Returns

Ein **aspose.slides.RectangleF**, das die visuellen Begrenzungen der Form in Folienkoordinaten darstellt.



```python
def get_visual_bounds(self):
    ...
```


### Remarks

Das zurückgegebene Rechteck stellt die achsenparallelen Begrenzungen aller Inhalte dar,
die von der Form während des Renderns im Folienkoordinatenraum erzeugt werden.

Diese Begrenzungen können von den Modellbegrenzungen der Form abweichen
([`Shape.x`](/slides/python-net/de/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/de/aspose.slides/shape/y),
[`Shape.width`](/slides/python-net/de/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/de/aspose.slides/shape/height))
und können negative Koordinaten enthalten, wenn der gerenderte Inhalt über den Folienursprung hinausgeht.

Die visuellen Begrenzungen berücksichtigen rendertypische Aspekte wie
Transformationen (zum Beispiel Drehung), Strichbreite und Verbindungen,
Textlayout und Überlauf, SmartArt-Geometrie sowie weitere Layout-Effekte,
die das endgültige gerenderte Erscheinungsbild der Form beeinflussen.

Die zurückgegebenen Begrenzungen werden nicht auf das Folienrechteck zugeschnitten.



### See Also
* Klasse [`SmartArt`](/slides/python-net/de/aspose.slides.smartart/smartart)
* Modul [`aspose.slides.smartart`](/slides/python-net/de/aspose.slides.smartart)
* Bibliothek [`Aspose.Slides`](/slides/python-net)