---
title: get_visual_bounds method
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides/audioframe/get_visual_bounds/
weight: 60
---
## get_visual_bounds(self) {#}
Hämtar den visuella gränsen för formen beräknad från dess renderade innehåll.

### Returnerar

En [`RectangleF`](/slides/python-net/sv/aspose.slides/rectanglef) som representerar den visuella gränsen för formen i bildens koordinater.



```python
def get_visual_bounds(self):
    ...
```


### Anmärkningar

Den returnerade rektangeln representerar de axeljusterade gränserna för allt innehåll som formen genererar under rendering i bildens koordinatrymd.

Dessa gränser kan skilja sig från formens modelgränser ([`Shape.x`](/slides/python-net/sv/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/sv/aspose.slides/shape/y), [`Shape.width`](/slides/python-net/sv/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/sv/aspose.slides/shape/height)) och kan innehålla negativa koordinater om det renderade innehållet sträcker sig bortom bildens ursprung.

De visuella gränserna tar hänsyn till renderingsrelaterade aspekter såsom transformationer (till exempel rotation), linjebredd och fogar, textlayout och överspill, SmartArt-geometri och andra layout-effekter som påverkar den slutliga renderade utformningen av formen.

De returnerade gränserna klipps inte till bildens rektangel.



### Se även
* klass [`AudioFrame`](/slides/python-net/sv/aspose.slides/audioframe)
* klass [`RectangleF`](/slides/python-net/sv/aspose.slides/rectanglef)
* modul [`aspose.slides`](/slides/python-net/sv/aspose.slides)
* bibliotek [`Aspose.Slides`](/slides/python-net)