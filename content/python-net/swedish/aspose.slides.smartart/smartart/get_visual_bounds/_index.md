---
title: get_visual_bounds method
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides.smartart/smartart/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
Hämtar de visuella gränserna för formen som beräknas från dess renderade innehåll.

### Returns
Ett **aspose.slides.RectangleF** som representerar de visuella gränserna för formen
             i bildkoordinater.

```python
def get_visual_bounds(self):
    ...
```

### Remarks
Den returnerade rektangeln representerar de axeljusterade gränserna för allt innehåll
             som formen producerar under rendering i bildkoordinatrymden.

Dessa gränser kan skilja sig från formens modellgränser ([`Shape.x`](/slides/python-net/sv/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/sv/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/sv/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/sv/aspose.slides/shape/height)) och kan innehålla negativa koordinater om det renderade innehållet sträcker sig
             bortom bildens ursprung.

De visuella gränserna tar hänsyn till renderingsrelaterade aspekter såsom
             transformationer (till exempel rotation), linjebredd och hörn,
             textlayout och överspill, SmartArt-geometri, och andra layout-effekter
             som påverkar det slutgiltiga renderade utseendet av formen.

De returnerade gränserna klipps inte till bildrektangeln.

### See Also
* klass [`SmartArt`](/slides/python-net/sv/aspose.slides.smartart/smartart)
* modul [`aspose.slides.smartart`](/slides/python-net/sv/aspose.slides.smartart)
* bibliotek [`Aspose.Slides`](/slides/python-net)