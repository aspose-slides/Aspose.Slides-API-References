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

### Rückgabe

Ein [`RectangleF`](/slides/python-net/de/aspose.slides/rectanglef) der die visuellen Begrenzungen der Form
             in Folienkoordinaten darstellt.



```python
def get_visual_bounds(self):
    ...
```


### Hinweise

Das zurückgegebene Rechteck repräsentiert die achsenbündigen Begrenzungen aller Inhalte,
             die von der Form während des Renderns im Koordinatenraum der Folie erzeugt werden.
            
             Diese Begrenzungen können von den Modellgrenzen der Form
             ([`Shape.x`](/slides/python-net/de/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/de/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/de/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/de/aspose.slides/shape/height))
             abweichen und negative Koordinaten enthalten, wenn der gerenderte Inhalt über
             den Ursprung der Folie hinausreicht.
            
             Die visuellen Begrenzungen berücksichtigen renderebezogene Aspekte wie
             Transformationen (z. B. Drehung), Strichstärke und -verbindungen,
             Textlayout und -überlauf, SmartArt-Geometrie und weitere Layout-Effekte,
             die das endgültige gerenderte Aussehen der Form beeinflussen.
            
             Die zurückgegebenen Begrenzungen werden nicht auf das Folienrechteck begrenzt.



### Siehe auch
* Klasse [`InkActions`](/slides/python-net/de/aspose.slides.ink/inkactions)
* Klasse [`RectangleF`](/slides/python-net/de/aspose.slides/rectanglef)
* Modul [`aspose.slides.ink`](/slides/python-net/de/aspose.slides.ink)
* Bibliothek [`Aspose.Slides`](/slides/python-net)