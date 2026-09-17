---
title: get_visual_bounds method
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides/connector/get_visual_bounds/
weight: 60
---
## get_visual_bounds(self) {#}
Gibt die visuellen Begrenzungen der Form zurück, die aus ihrem gerenderten Inhalt berechnet werden.

### Rückgabewert

Ein **aspose.slides.RectangleF**, das die visuellen Begrenzungen der Form in Folienkoordinaten repräsentiert.



```python
def get_visual_bounds(self):
    ...
```


### Hinweise

Das zurückgegebene Rechteck stellt die achsen-ausgerichteten Begrenzungen sämtlichen Inhalts dar,
 der von der Form beim Rendern im Folienkoordinatenraum erzeugt wird.

Diese Begrenzungen können von den Modellbegrenzungen der Form abweichen
([`Shape.x`](/slides/python-net/de/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/de/aspose.slides/shape/y),
[`Shape.width`](/slides/python-net/de/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/de/aspose.slides/shape/height))
und können negative Koordinaten enthalten, wenn der gerenderte Inhalt über den Ursprung der Folie hinausgeht.

Die visuellen Begrenzungen berücksichtigen renderbezogene Aspekte wie
Transformationen (zum Beispiel Rotation), Strichbreite und Verbindungen,
Textlayout und Überlauf, SmartArt-Geometrie sowie weitere Layout-Effekte,
die das endgültige gerenderte Erscheinungsbild der Form beeinflussen.

Die zurückgegebenen Begrenzungen werden nicht auf das Folienrechteck zugeschnitten.



### Siehe auch
* Klasse [`Connector`](/slides/python-net/de/aspose.slides/connector)
* Modul [`aspose.slides`](/slides/python-net/de/aspose.slides)
* Bibliothek [`Aspose.Slides`](/slides/python-net)