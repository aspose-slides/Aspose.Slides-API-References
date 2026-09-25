---
title: get_visual_bounds method
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides/pictureframe/get_visual_bounds/
weight: 60
---
## get_visual_bounds(self) {#}
Hämtar de visuella gränserna för formen som beräknas från dess renderade innehåll.

### Returnerar

Ett [`RectangleF`](/slides/python-net/sv/aspose.slides/rectanglef) som representerar formens visuella gränser i bildspelskoordinater.



```python
def get_visual_bounds(self):
    ...
```


### Anmärkningar

Den returnerade rektangeln representerar de axiellt justerade gränserna för allt innehåll
             som produceras av formen under rendering i bildspelskoordinatrymden.
            
             Dessa gränser kan skilja sig från formens modellgränser
             ([`Shape.x`](/slides/python-net/sv/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/sv/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/sv/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/sv/aspose.slides/shape/height))
             och kan innehålla negativa koordinater om det renderade innehållet sträcker sig
             utanför bildspelsursprunget.
            
             De visuella gränserna tar hänsyn till renderingsrelaterade aspekter såsom
             transformeringar (till exempel rotation), linjebredd och hörn,
             textlayout och overflow, SmartArt-geometri, och andra layout-effekter
             som påverkar formens slutgiltiga renderade utseende.
            
             De returnerade gränserna klipps inte av till bildrektangeln.



### Se även
* klass [`PictureFrame`](/slides/python-net/sv/aspose.slides/pictureframe)
* klass [`RectangleF`](/slides/python-net/sv/aspose.slides/rectanglef)
* modul [`aspose.slides`](/slides/python-net/sv/aspose.slides)
* bibliotek [`Aspose.Slides`](/slides/python-net)