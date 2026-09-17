---
title: get_visual_bounds method
second_title: Aspose.Slides für Python via .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides/sectionzoomframe/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
Ermittelt die visuellen Begrenzungen der Form, die aus ihrem gerenderten Inhalt berechnet werden.

### Rückgabe

Ein **aspose.slides.RectangleF**, das die visuellen Begrenzungen der Form
             in Folienkoordinaten darstellt.



```python
def get_visual_bounds(self):
    ...
```


### Bemerkungen

Das zurückgegebene Rechteck stellt die achsen-ausgerichteten Begrenzungen aller Inhalte dar,
             die von der Form während des Renderns im Folienkoordinatenraum erzeugt werden.
            
             Diese Begrenzungen können von den Modell-Begrenzungen der Form
             ([`Shape.x`](/slides/python-net/de/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/de/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/de/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/de/aspose.slides/shape/height))
             abweichen und negative Koordinaten enthalten, wenn der gerenderte Inhalt über den Folienursprung hinaus reicht.
            
             Die visuellen Begrenzungen berücksichtigen renderbezogene Aspekte wie
             Transformationen (zum Beispiel Drehung), Strichstärke und -verbindungen,
             Textlayout und Überlauf, SmartArt-Geometrie sowie weitere Layout-Effekte,
             die das endgültige gerenderte Aussehen der Form beeinflussen.
            
             Die zurückgegebenen Begrenzungen werden nicht auf das Folienrechteck zugeschnitten.



### Siehe auch
* Klasse [`SectionZoomFrame`](/slides/python-net/de/aspose.slides/sectionzoomframe)
* Modul [`aspose.slides`](/slides/python-net/de/aspose.slides)
* Bibliothek [`Aspose.Slides`](/slides/python-net)