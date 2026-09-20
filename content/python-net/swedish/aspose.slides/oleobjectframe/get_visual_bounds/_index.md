---
title: get_visual_bounds method
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides/oleobjectframe/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
Hämtar den visuella gränsen för formen beräknad från dess renderade innehåll.

### Returnerar

A **aspose.slides.RectangleF** som representerar den visuella gränsen för formen
 i bildens koordinater.



```python
def get_visual_bounds(self):
    ...
```


### Anmärkningar

Den returnerade rektangeln representerar de axiellt justerade gränserna för allt innehåll som produceras av formen under rendering i bildens koordinatrum.

Dessa gränser kan skilja sig från formens modellgränser ([`Shape.x`](/slides/python-net/sv/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/sv/aspose.slides/shape/y), [`Shape.width`](/slides/python-net/sv/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/sv/aspose.slides/shape/height)) och kan innehålla negativa koordinater om det renderade innehållet sträcker sig bortom bildens ursprung.

De visuella gränserna tar hänsyn till renderingsrelaterade aspekter såsom transformationer (till exempel rotation), linjebredd och fogar, textlayout och överspill, SmartArt-geometri och andra layout-effekter som påverkar formens slutliga renderade utseende.

De returnerade gränserna är inte beskurna till bildens rektangel.



### Se även
* klass [`OleObjectFrame`](/slides/python-net/sv/aspose.slides/oleobjectframe)
* modul [`aspose.slides`](/slides/python-net/sv/aspose.slides)
* bibliotek [`Aspose.Slides`](/slides/python-net)