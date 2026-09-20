---
title: get_visual_bounds method
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides/geometryshape/get_visual_bounds/
weight: 60
---
## get_visual_bounds(self) {#}
Hämtar de visuella gränserna för formen beräknade utifrån dess renderade innehåll.

### Returnerar

En **aspose.slides.RectangleF** som representerar de visuella gränserna för formen i bildspelskoordinater.



```python
def get_visual_bounds(self):
    ...
```

### Anmärkningar

Den returnerade rektangeln representerar de axeljusterade gränserna för allt innehåll som produceras av formen under rendering i bildspelskoordinatrymden.

Dessa gränser kan skilja sig från formens modelgränser.
             ([`Shape.x`](/slides/python-net/sv/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/sv/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/sv/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/sv/aspose.slides/shape/height))
             och kan innehålla negativa koordinater om det renderade innehållet sträcker sig utanför bildens ursprung.

             De visuella gränserna tar hänsyn till renderingsrelaterade aspekter såsom transformationer (till exempel rotation), linjebredd och sammanfogningar, textlayout och översvämning, SmartArt-geometri och andra layout-effekter som påverkar den slutliga renderade utseendet på formen.

             De returnerade gränserna klipps inte till bildens rektangel.



### Se också
* klass [`GeometryShape`](/slides/python-net/sv/aspose.slides/geometryshape)
* modul [`aspose.slides`](/slides/python-net/sv/aspose.slides)
* bibliotek [`Aspose.Slides`](/slides/python-net)