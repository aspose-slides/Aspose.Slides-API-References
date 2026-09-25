---
title: get_visual_bounds method
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides.smartart/smartart/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
Hämtar de visuella gränserna för formen beräknade från dess renderade innehåll.

### Returnerar

En [`RectangleF`](/slides/python-net/sv/aspose.slides/rectanglef) som representerar den visuella gränsen för formen i bildspelskoordinater.



```python
def get_visual_bounds(self):
    ...
```


### Anmärkningar
Den returnerade rektangeln representerar de axeljusterade gränserna för allt innehåll
             producerat av formen under rendering i bildspelskoordinatrymden.

             Dessa gränser kan skilja sig från formens modellgränser
             ([`Shape.x`](/slides/python-net/sv/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/sv/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/sv/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/sv/aspose.slides/shape/height))
             och kan innehålla negativa koordinater om det renderade innehållet sträcker sig
             bortom bildspelsursprunget.

            De visuella gränserna tar hänsyn till renderingsrelaterade aspekter såsom
            transformeringar (till exempel rotation), linjebredd och fogar,
            textlayout och overspill, SmartArt-geometri och andra layout-effekter
            som påverkar formens slutgiltiga renderade utseende.

            De returnerade gränserna klipps inte till bildspelsrektangeln.



### Se också
* klass [`SmartArt`](/slides/python-net/sv/aspose.slides.smartart/smartart)
* klass [`RectangleF`](/slides/python-net/sv/aspose.slides/rectanglef)
* modul [`aspose.slides.smartart`](/slides/python-net/sv/aspose.slides.smartart)
* bibliotek [`Aspose.Slides`](/slides/python-net)