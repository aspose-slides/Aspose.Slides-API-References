---
title: get_visual_bounds method
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides/autoshape/get_visual_bounds/
weight: 70
---
## get_visual_bounds(self) {#}
Hämtar de visuella gränserna för formen beräknade från dess renderade innehåll.

### Returnerar

Ett **aspose.slides.RectangleF** som representerar de visuella gränserna för formen
             i bildkoordinater.



```python
def get_visual_bounds(self):
    ...
```


### Anmärkningar

Den returnerade rektangeln representerar de axeljusterade gränserna för allt innehåll
             som produceras av formen under rendering i bildkoordinatrummet.
            
Dessa gränser kan skilja sig från formens modellgränser
             ([`Shape.x`](/slides/python-net/sv/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/sv/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/sv/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/sv/aspose.slides/shape/height))
             och kan innehålla **negativa** koordinater om det renderade innehållet sträcker sig utanför bildens ursprung.
            
De visuella gränserna tar hänsyn till rendering-relaterade aspekter såsom
             transformationer (till exempel, rotation), linjebredd och fogar,
             textlayout och överspill, SmartArt-geometri, och andra layout-effekter
             som påverkar det slutgiltiga renderade utseendet på formen.
            
De returnerade gränserna är inte beskurna till bildrektangeln.



### Se även
* klass [`AutoShape`](/slides/python-net/sv/aspose.slides/autoshape)
* modul [`aspose.slides`](/slides/python-net/sv/aspose.slides)
* bibliotek [`Aspose.Slides`](/slides/python-net)