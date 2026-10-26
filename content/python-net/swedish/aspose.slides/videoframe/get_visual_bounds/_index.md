---
title: get_visual_bounds method
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides/videoframe/get_visual_bounds/
weight: 60
---
## get_visual_bounds(self) {#}
Hämtar den visuella gränsen för formen beräknad från dess renderade innehåll.

### Returnerar

Ett [`RectangleF`](/slides/python-net/sv/aspose.slides/rectanglef) som representerar den visuella gränsen för formen i bildkoordinater.



```python
def get_visual_bounds(self):
    ...
```


### Anmärkningar
Den returnerade rektangeln representerar de axeljusterade gränserna för allt innehåll
             som produceras av formen under rendering i bildkoordinatsystemet.

Dessa gränser kan skilja sig från formens modellgränser
             ([`Shape.x`](/slides/python-net/sv/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/sv/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/sv/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/sv/aspose.slides/shape/height))
             och kan innehålla negativa koordinater om det renderade innehållet sträcker sig
             bortom bildens ursprung.

Den visuella gränsen tar hänsyn till rendering-relaterade aspekter såsom
             transformationer (till exempel rotation), linjebredd och fogar,
             textlayout och överspill, SmartArt-geometri och andra layout-effekter
             som påverkar formens slutgiltiga renderade utseende.

De returnerade gränserna klipps inte till bildrektangeln.



### Se också
* klass [`VideoFrame`](/slides/python-net/sv/aspose.slides/videoframe)
* klass [`RectangleF`](/slides/python-net/sv/aspose.slides/rectanglef)
* modul [`aspose.slides`](/slides/python-net/sv/aspose.slides)
* bibliotek [`Aspose.Slides`](/slides/python-net)