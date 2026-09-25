---
title: get_visual_bounds method
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides.charts/chart/get_visual_bounds/
weight: 50
---
## get_visual_bounds(self) {#}
Ermittelt die visuellen Begrenzungen der Form, die aus ihrem gerenderten Inhalt berechnet werden.

### Rückgabewert

Ein [`RectangleF`](/slides/python-net/de/aspose.slides/rectanglef), das die visuellen Begrenzungen der Form
             in Folienkoordinaten darstellt.



```python
def get_visual_bounds(self):
    ...
```


### Bemerkungen

Das zurückgegebene Rechteck stellt die achsenbasierten Begrenzungen aller Inhalte dar,
             die von der Form während der Darstellung im Folienkoordinatenraum erzeugt werden.
            
             Diese Begrenzungen können von den Modellbegrenzungen der Form
             ([`Shape.x`](/slides/python-net/de/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/de/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/de/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/de/aspose.slides/shape/height))
             abweichen und negative Koordinaten enthalten, wenn der gerenderte Inhalt über
             den Folienursprung hinausreicht.
            
             Die visuellen Begrenzungen berücksichtigen renderebezogene Aspekte wie
             Transformationen (z. B. Drehung), Strichbreite und -verbindungen,
             Textlayout und Überlauf, SmartArt-Geometrie sowie andere Layout-Effekte,
             die das endgültige gerenderte Erscheinungsbild der Form beeinflussen.
            
             Die zurückgegebenen Begrenzungen werden nicht auf das Folienrechteck beschränkt.



### Siehe auch
* Klasse [`Chart`](/slides/python-net/de/aspose.slides.charts/chart)
* Klasse [`RectangleF`](/slides/python-net/de/aspose.slides/rectanglef)
* Modul [`aspose.slides.charts`](/slides/python-net/de/aspose.slides.charts)
* Bibliothek [`Aspose.Slides`](/slides/python-net)