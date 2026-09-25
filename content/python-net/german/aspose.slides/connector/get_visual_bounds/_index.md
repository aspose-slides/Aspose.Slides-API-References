---
title: get_visual_bounds method
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides/connector/get_visual_bounds/
weight: 60
---
## get_visual_bounds(self) {#}
Ermittelt die visuellen Begrenzungen der Form, die aus ihrem gerenderten Inhalt berechnet werden.

### Rückgabewert

Ein [`RectangleF`](/slides/python-net/de/aspose.slides/rectanglef), das die visuellen Begrenzungen der Form in Folienkoordinaten darstellt
             in slide coordinates.



```python
def get_visual_bounds(self):
    ...
```


### Bemerkungen

Das zurückgegebene Rechteck stellt die achsenparallelen Begrenzungen aller Inhalte dar,
            die von der Form während des Renderns im Folienkoordinatenraum erzeugt werden.

            Diese Begrenzungen können von den Modellgrenzen der Form abweichen
            ([`Shape.x`](/slides/python-net/de/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/de/aspose.slides/shape/y),
            [`Shape.width`](/slides/python-net/de/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/de/aspose.slides/shape/height))
            und können negative Koordinaten enthalten, wenn der gerenderte Inhalt
            über den Folienursprung hinausgeht.

            Die visuellen Begrenzungen berücksichtigen renderbezogene Aspekte wie
            Transformationen (z. B. Drehung), Strichbreite und -verbindungen,
            Textlayout und Überlauf, SmartArt-Geometrie und andere Layout-Effekte,
            die das endgültige gerenderte Aussehen der Form beeinflussen.

            Die zurückgegebenen Begrenzungen werden nicht auf das Folienrechteck beschnitten.



### Siehe auch
* Klasse [`Connector`](/slides/python-net/de/aspose.slides/connector)
* Klasse [`RectangleF`](/slides/python-net/de/aspose.slides/rectanglef)
* Modul [`aspose.slides`](/slides/python-net/de/aspose.slides)
* Bibliothek [`Aspose.Slides`](/slides/python-net)