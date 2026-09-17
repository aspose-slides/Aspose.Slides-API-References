---
title: get_visual_bounds method
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides/geometryshape/get_visual_bounds/
weight: 60
---
## get_visual_bounds(self) {#}
Ermittelt die visuellen Begrenzungen der Form, die aus ihrem gerenderten Inhalt berechnet werden.

### Rückgabewert

Ein **aspose.slides.RectangleF**, das die visuellen Begrenzungen der Form in Folienkoordinaten darstellt.
             in slide coordinates.



```python
def get_visual_bounds(self):
    ...
```


### Bemerkungen

Das zurückgegebene Rechteck stellt die achsen-ausgerichteten Begrenzungen aller Inhalte dar, die von der Form während des Renderns im Folienkoordinatenraum erzeugt werden.
            
            Diese Begrenzungen können von den Modellbegrenzungen der Form ([`Shape.x`](/slides/python-net/de/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/de/aspose.slides/shape/y), [`Shape.width`](/slides/python-net/de/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/de/aspose.slides/shape/height)) abweichen und können negative Koordinaten enthalten, wenn der gerenderte Inhalt über den Ursprung der Folie hinausgeht.
            
            Die visuellen Begrenzungen berücksichtigen renderebezogene Aspekte wie Transformationen (z.B. Drehung), Strichstärke und Verbindungen, Textlayout und Überlauf, SmartArt-Geometrie sowie andere Layout-Effekte, die das endgültige gerenderte Erscheinungsbild der Form beeinflussen.
            
            Die zurückgegebenen Begrenzungen werden nicht auf das Folienrechteck abgeschnitten.



### Siehe auch
* Klasse [`GeometryShape`](/slides/python-net/de/aspose.slides/geometryshape)
* Modul [`aspose.slides`](/slides/python-net/de/aspose.slides)
* Bibliothek [`Aspose.Slides`](/slides/python-net)