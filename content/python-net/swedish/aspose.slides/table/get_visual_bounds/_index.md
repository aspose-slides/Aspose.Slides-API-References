---
title: get_visual_bounds method
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides/table/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
Hämtar de visuella gränserna för formen som beräknas från dess renderade innehåll.

### Returnerar

En **aspose.slides.RectangleF** som representerar de visuella gränserna för formen i bildspelskoordinater.



```python
def get_visual_bounds(self):
    ...
```


### Anmärkningar

Den returnerade rektangeln representerar de axeljusterade gränserna för allt innehåll som formen producerar under rendering i bildspelskoordinatrymden.

Dessa gränser kan skilja sig från formens modellgränser ([`Shape.x`](/slides/python-net/sv/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/sv/aspose.slides/shape/y), [`Shape.width`](/slides/python-net/sv/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/sv/aspose.slides/shape/height)) och kan innehålla negativa koordinater om det renderade innehållet sträcker sig bortom bildspelsursprunget.

De visuella gränserna tar hänsyn till renderingsrelaterade aspekter såsom transformationer (till exempel rotation), linjebredd och fogar, textlayout och överspill, SmartArt-geometri och andra layout-effekter som påverkar formens slutgiltiga renderade utseende.

De returnerade gränserna klipps inte till bildrektangeln.



### Se även
* klass [`Table`](/slides/python-net/sv/aspose.slides/table)
* modul [`aspose.slides`](/slides/python-net/sv/aspose.slides)
* bibliotek [`Aspose.Slides`](/slides/python-net)