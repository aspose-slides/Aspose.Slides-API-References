---
title: get_visual_bounds method
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides/videoframe/get_visual_bounds/
weight: 60
---
## get_visual_bounds(self) {#}
Ermittelt die visuellen Grenzen der Form, die aus ihrem gerenderten Inhalt berechnet werden.

### Rückgabewert

Ein [`RectangleF`](/slides/python-net/de/aspose.slides/rectanglef), der die visuellen Grenzen der Form
             in Folienkoordinaten darstellt.



```python
def get_visual_bounds(self):
    ...
```


### Hinweise

Das zurückgegebene Rechteck stellt die achsen-ausgerichteten Grenzen aller Inhalte dar
             die vom Form während des Renderns im Folienkoordinatenraum erzeugt werden.
            
             Diese Grenzen können von den Modellgrenzen der Form
             ([`Shape.x`](/slides/python-net/de/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/de/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/de/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/de/aspose.slides/shape/height))
             abweichen und negative Koordinaten enthalten, falls der gerenderte Inhalt über den Ursprung der Folie hinausreicht.
            
             Die visuellen Grenzen berücksichtigen renderebezogene Aspekte wie
             Transformationen (z. B. Rotation), Strichbreite und Verbindungen,
             Textlayout und Überlauf, SmartArt-Geometrie und andere Layout-Effekte,
             die das endgültige gerenderte Erscheinungsbild der Form beeinflussen.
            
             Die zurückgegebenen Grenzen werden nicht auf das Folienrechteck zugeschnitten.



### Siehe auch
* Klasse [`VideoFrame`](/slides/python-net/de/aspose.slides/videoframe)
* Klasse [`RectangleF`](/slides/python-net/de/aspose.slides/rectanglef)
* Modul [`aspose.slides`](/slides/python-net/de/aspose.slides)
* Bibliothek [`Aspose.Slides`](/slides/python-net)