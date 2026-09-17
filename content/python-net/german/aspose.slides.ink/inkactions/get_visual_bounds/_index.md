---
title: get_visual_bounds method
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides.ink/inkactions/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
Ermittelt die visuellen Begrenzungen der Form, die aus ihrem gerenderten Inhalt berechnet werden.

### Rückgabewert

Ein **aspose.slides.RectangleF**, das die visuellen Begrenzungen der Form in Folienkoordinaten darstellt.



```python
def get_visual_bounds(self):
    ...
```


### Hinweise

Das zurückgegebene Rechteck stellt die achsenausgerichteten Begrenzungen aller Inhalte dar, die von der Form während des Renderns im Folienkoordinatenraum erzeugt werden.

Diese Begrenzungen können von den Modellbegrenzungen der Form ([`Shape.x`](/slides/python-net/de/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/de/aspose.slides/shape/y), [`Shape.width`](/slides/python-net/de/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/de/aspose.slides/shape/height)) abweichen und negative Koordinaten enthalten, wenn der gerenderte Inhalt über den Folienursprung hinaus reicht.

Die visuellen Begrenzungen berücksichtigen renderbezogene Aspekte wie Transformationen (z. B. Drehung), Strichstärke und -verbindungen, Textlayout und -überlauf, SmartArt-Geometrie sowie andere Layout-Effekte, die das endgültige gerenderte Erscheinungsbild der Form beeinflussen.

Die zurückgegebenen Begrenzungen werden nicht auf das Folienrechteck zugeschnitten.



### Siehe auch
* Klasse [`InkActions`](/slides/python-net/de/aspose.slides.ink/inkactions)
* Modul [`aspose.slides.ink`](/slides/python-net/de/aspose.slides.ink)
* Bibliothek [`Aspose.Slides`](/slides/python-net)