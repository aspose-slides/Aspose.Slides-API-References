---
title: get_visual_bounds method
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides/table/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
Ermittelt die visuellen Grenzen der Form, die aus ihrem gerenderten Inhalt berechnet werden.

### Rückgabe

Ein [`RectangleF`](/slides/python-net/de/aspose.slides/rectanglef), der die visuellen Grenzen der Form in Folienkoordinaten darstellt



```python
def get_visual_bounds(self):
    ...
```


### Anmerkungen

Das zurückgegebene Rechteck stellt die achsenbasierten Grenzen aller Inhalte dar
             erzeugt von der Form während des Renderns im Folienkoordinatenraum.
            
             Diese Grenzen können von den Modellgrenzen der Form abweichen
             ([`Shape.x`](/slides/python-net/de/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/de/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/de/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/de/aspose.slides/shape/height))
             und können negative Koordinaten enthalten, wenn der gerenderte Inhalt sich erstreckt
             über den Ursprung der Folie hinaus.
            
             Die visuellen Grenzen berücksichtigen renderbezogene Aspekte wie
             Transformationen (zum Beispiel Drehung), Strichbreite und Verbindungsstellen,
             Textlayout und Überlauf, SmartArt-Geometrie sowie andere Layout-Effekte
             die das endgültige gerenderte Erscheinungsbild der Form beeinflussen.
            
             Die zurückgegebenen Grenzen werden nicht auf das Folienrechteck beschränkt.



### Siehe auch
* Klasse [`Table`](/slides/python-net/de/aspose.slides/table)
* Klasse [`RectangleF`](/slides/python-net/de/aspose.slides/rectanglef)
* Modul [`aspose.slides`](/slides/python-net/de/aspose.slides)
* Bibliothek [`Aspose.Slides`](/slides/python-net)