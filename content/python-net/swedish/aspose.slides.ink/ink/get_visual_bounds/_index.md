---
title: get_visual_bounds method
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides.ink/ink/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
Hämtar de visuella gränserna för formen beräknade från dess renderade innehåll.

### Returnvärde

Ett **aspose.slides.RectangleF** som representerar de visuella gränserna för formen i bildens koordinater.



```python
def get_visual_bounds(self):
    ...
```


### Anmärkningar

Den returnerade rektangeln representerar de axeljusterade gränserna för allt innehåll som produceras av formen under rendering i bildens koordinatrymd.

             Dessa gränser kan skilja sig från formens modellgränser
             ([`Shape.x`](/slides/python-net/sv/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/sv/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/sv/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/sv/aspose.slides/shape/height))
             och kan innehålla negativa koordinater om det renderade innehållet sträcker sig längre än bildens origo.

             De visuella gränserna tar hänsyn till renderingsrelaterade aspekter såsom
             transformationer (till exempel rotation), linjebredd och fogar,
             textlayout och översvämning, SmartArt-geometri, och andra layout-effekter
             som påverkar formens slutgiltiga renderade utseende.

             De returnerade gränserna är inte klippta till bildens rektangel.



### Se även
* klass [`Ink`](/slides/python-net/sv/aspose.slides.ink/ink)
* modul [`aspose.slides.ink`](/slides/python-net/sv/aspose.slides.ink)
* bibliotek [`Aspose.Slides`](/slides/python-net)