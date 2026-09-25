---
title: get_visual_bounds method
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides/oleobjectframe/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
Hämtar de visuella gränserna för formen beräknade från dess renderade innehåll.

### Returnerar

Ett [`RectangleF`](/slides/python-net/sv/aspose.slides/rectanglef) som representerar de visuella gränserna för formen i slidekoordinater.



```python
def get_visual_bounds(self):
    ...
```


### Anmärkningar

Den returnerade rektangeln representerar de axeljusterade gränserna för allt innehåll som formen producerar under rendering i slidekoordinatrymden.

Dessa gränser kan skilja sig från formens modellgränser ([`Shape.x`](/slides/python-net/sv/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/sv/aspose.slides/shape/y), [`Shape.width`](/slides/python-net/sv/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/sv/aspose.slides/shape/height)) och kan innehålla negativa koordinater om det renderade innehållet sträcker sig bortom slide-ursprunget.

De visuella gränserna tar hänsyn till renderingsrelaterade aspekter såsom transformationer (t.ex. rotation), linjebredd och fogar, textlayout och överspill, SmartArt-geometri samt andra layout-effekter som påverkar det slutgiltiga renderade utseendet för formen.

De returnerade gränserna klipps inte till slide-rektangeln.



### Se även
* klass [`OleObjectFrame`](/slides/python-net/sv/aspose.slides/oleobjectframe)
* klass [`RectangleF`](/slides/python-net/sv/aspose.slides/rectanglef)
* modul [`aspose.slides`](/slides/python-net/sv/aspose.slides)
* bibliotek [`Aspose.Slides`](/slides/python-net)