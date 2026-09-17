---
title: get_visual_bounds method
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides.charts/chart/get_visual_bounds/
weight: 50
---
## get_visual_bounds(self) {#}
Ermittelt die visuellen Begrenzungen der Form, berechnet aus ihrem gerenderten Inhalt.

### Rückgabewert

Ein **aspose.slides.RectangleF**, das die visuellen Begrenzungen der Form in Folienkoordinaten darstellt.



```python
def get_visual_bounds(self):
    ...
```


### Hinweise

Das zurückgegebene Rechteck stellt die achsenbündigen Begrenzungen aller Inhalte dar, die von der Form während des Renderns im Folienkoordinatenraum erzeugt werden.

Diese Begrenzungen können von den Modellbegrenzungen der Form ([`Shape.x`](/slides/python-net/de/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/de/aspose.slides/shape/y), [`Shape.width`](/slides/python-net/de/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/de/aspose.slides/shape/height)) abweichen und negative Koordinaten enthalten, wenn der gerenderte Inhalt über den Ursprung der Folie hinausgeht.

Die visuellen Begrenzungen berücksichtigen rendervorgangsbezogene Aspekte wie Transformationen (z. B. Drehung), Strichbreite und -verbindungen, Textlayout und Überlauf, SmartArt-Geometrie und andere Layout-Effekte, die das endgültige gerenderte Erscheinungsbild der Form beeinflussen.

Die zurückgegebenen Begrenzungen werden nicht auf das Folienrechteck beschränkt.



### Siehe auch
* Klasse [`Chart`](/slides/python-net/de/aspose.slides.charts/chart)
* Modul [`aspose.slides.charts`](/slides/python-net/de/aspose.slides.charts)
* Bibliothek [`Aspose.Slides`](/slides/python-net)