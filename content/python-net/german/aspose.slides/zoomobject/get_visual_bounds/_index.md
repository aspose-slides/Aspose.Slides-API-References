---
title: get_visual_bounds method
second_title: Aspose.Slides für Python via .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides/zoomobject/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
Ermittelt die visuellen Grenzen der Form, die aus ihrem gerenderten Inhalt berechnet werden.

### Rückgabewert

Ein **aspose.slides.RectangleF**, das die visuellen Grenzen der Form
             in Folienkoordinaten darstellt.



```python
def get_visual_bounds(self):
    ...
```


### Anmerkungen

Das zurückgegebene Rechteck stellt die achsenparallelen Grenzen aller Inhalte
             dar, die von der Form während der Renderung im Folienkoordinatenraum erzeugt werden.

Diese Grenzen können von den Modellgrenzen der Form abweichen
             ([`Shape.x`](/slides/python-net/de/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/de/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/de/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/de/aspose.slides/shape/height))
             und können negative Koordinaten enthalten, wenn der gerenderte Inhalt erweitert
             über den Folienursprung hinaus.

Die visuellen Grenzen berücksichtigen renderbezogene Aspekte wie
             Transformationen (zum Beispiel Drehung), Strichbreite und Verbindungen,
             Textlayout und Überlauf, SmartArt-Geometrie und andere Layout-Effekte
             die das endgültige gerenderte Erscheinungsbild der Form beeinflussen.

Die zurückgegebenen Grenzen werden nicht an das Folienrechteck angepasst.



### Siehe auch
* Klasse [`ZoomObject`](/slides/python-net/de/aspose.slides/zoomobject)
* Modul [`aspose.slides`](/slides/python-net/de/aspose.slides)
* Bibliothek [`Aspose.Slides`](/slides/python-net)