---
title: get_visual_bounds method
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides/shape/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
Hämtar de visuella gränserna för formen beräknade från dess renderade innehåll.

### Returnerar

En **aspose.slides.RectangleF** som representerar de visuella gränserna för formen i diakoordinater.



```python
def get_visual_bounds(self):
    ...
```


### Anmärkningar

Den returnerade rektangeln representerar de axeljusterade gränserna för allt innehåll som formen producerar under rendering i diakoordinatrymden.

Dessa gränser kan skilja sig från formens modellgränser ([`Shape.x`](/slides/python-net/sv/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/sv/aspose.slides/shape/y), [`Shape.width`](/slides/python-net/sv/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/sv/aspose.slides/shape/height)) och kan innehålla negativa koordinater om det renderade innehållet sträcker sig bortom bildens ursprung.

De visuella gränserna tar hänsyn till renderingsrelaterade aspekter såsom transformationer (till exempel rotation), linjebredd och hörn, textlayout och översvämning, SmartArt-geometri och andra layouteffekter som påverkar den slutgiltiga renderade utseendet på formen.

De returnerade gränserna klipps inte till diaraketangen.



### Se också
* klass [`Shape`](/slides/python-net/sv/aspose.slides/shape)
* modul [`aspose.slides`](/slides/python-net/sv/aspose.slides)
* bibliotek [`Aspose.Slides`](/slides/python-net)