---
title: get_visual_bounds method
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides/zoomobject/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
Hämtar de visuella gränserna för formen beräknade från dess renderade innehåll.

### Returnerar

En [`RectangleF`](/slides/python-net/sv/aspose.slides/rectanglef) som representerar de visuella gränserna för formen i bildspelskoordinater.



```python
def get_visual_bounds(self):
    ...
```


### Anmärkningar

Den återgivna rektangeln representerar de axeljusterade gränserna för allt innehåll som produceras av formen under rendering i bildspelskoordinater.

Dessa gränser kan skilja sig från formens modellgränser ([`Shape.x`](/slides/python-net/sv/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/sv/aspose.slides/shape/y), [`Shape.width`](/slides/python-net/sv/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/sv/aspose.slides/shape/height)) och kan innehålla negativa koordinater om det renderade innehållet sträcker sig bortom bildspelsursprunget.

De visuella gränserna tar hänsyn till renderingsrelaterade aspekter såsom transformationer (till exempel rotation), linjebredd och hörn, textlayout och överspill, SmartArt-geometri och andra layout-effekter som påverkar det slutliga renderade utseendet på formen.

De returnerade gränserna klipps inte till bildspelsrektangeln.



### Se också
* klass [`ZoomObject`](/slides/python-net/sv/aspose.slides/zoomobject)
* klass [`RectangleF`](/slides/python-net/sv/aspose.slides/rectanglef)
* modul [`aspose.slides`](/slides/python-net/sv/aspose.slides)
* bibliotek [`Aspose.Slides`](/slides/python-net)