---
title: get_visual_bounds method
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides/connector/get_visual_bounds/
weight: 60
---
## get_visual_bounds(self) {#}
Hämtar de visuella gränserna för formen beräknade från dess renderade innehåll.

### Returnerar

A **aspose.slides.RectangleF** som representerar de visuella gränserna för formen
             i bildkoordinater.



```python
def get_visual_bounds(self):
    ...
```


### Anmärkningar

Den returnerade rektangeln representerar de axeljusterade gränserna för allt innehåll
             producerat av formen under rendering i bildkoordinatrymden.
            
             Dessa gränser kan skilja sig från formens modellgränser
             ([`Shape.x`](/slides/python-net/sv/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/sv/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/sv/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/sv/aspose.slides/shape/height))
             och kan innehålla negativa koordinater om det renderade innehållet sträcker sig
             utanför bildens ursprung.
            
             De visuella gränserna tar hänsyn till renderingsrelaterade aspekter såsom
             transformationer (t.ex. rotation), linjebredd och hörn,
             textlayout och överspill, SmartArt-geometri och andra layout-effekter
             som påverkar formens slutgiltiga renderade utseende.
            
             De returnerade gränserna är inte beskurna till bildrektangeln.



### Se också
* klass [`Connector`](/slides/python-net/sv/aspose.slides/connector)
* modul [`aspose.slides`](/slides/python-net/sv/aspose.slides)
* bibliotek [`Aspose.Slides`](/slides/python-net)