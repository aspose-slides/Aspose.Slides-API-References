---
title: get_visual_bounds method
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides.charts/chart/get_visual_bounds/
weight: 50
---
## get_visual_bounds(self) {#}
Hämtar de visuella gränserna för formen som beräknas från dess renderade innehåll.

### Returnerar

A **aspose.slides.RectangleF** som representerar de visuella gränserna för formen
             i bildspelskoordinater.



```python
def get_visual_bounds(self):
    ...
```


### Anmärkningar

Den returnerade rektangeln representerar de axeljusterade gränserna för allt innehåll
             som produceras av formen under rendering i bildspelskoordinatrymden.
            
             Dessa gränser kan skilja sig från formens modellgränser
             ([`Shape.x`](/slides/python-net/sv/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/sv/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/sv/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/sv/aspose.slides/shape/height))
             och kan innehålla negativa koordinater om det renderade innehållet sträcker sig
             utanför bildspelsursprunget.
            
             De visuella gränserna tar hänsyn till renderingrelaterade aspekter såsom
             transformationer (t.ex. rotation), linjebredd och hörn,
             textlayout och översvämning, SmartArt-geometri, och andra layoutseffekter
             som påverkar formens slutgiltiga renderade utseende.
            
             De returnerade gränserna klipps inte till bildspelsrektangeln.



### Se även
* klass [`Chart`](/slides/python-net/sv/aspose.slides.charts/chart)
* modul [`aspose.slides.charts`](/slides/python-net/sv/aspose.slides.charts)
* bibliotek [`Aspose.Slides`](/slides/python-net)