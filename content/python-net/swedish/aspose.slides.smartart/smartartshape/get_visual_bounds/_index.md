---
title: get_visual_bounds method
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides.smartart/smartartshape/get_visual_bounds/
weight: 60
---
## get_visual_bounds(self) {#}
Hämtar den visuella begränsningen av formen beräknad från dess renderade innehåll.

### Returnerar

En **aspose.slides.RectangleF** som representerar den visuella begränsningen av formen
             i bildens koordinater.



```python
def get_visual_bounds(self):
    ...
```


### Anmärkningar

Den returnerade rektangeln representerar de axeljusterade begränsningarna för allt innehåll
             som produceras av formen under rendering i bildens koordinatrymd.
            
             Dessa begränsningar kan skilja sig från formens modellgränser
             ([`Shape.x`](/slides/python-net/sv/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/sv/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/sv/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/sv/aspose.slides/shape/height))
             och kan innehålla negativa koordinater om det renderade innehållet sträcker sig
             bortom bildens ursprung.
            
             De visuella begränsningarna tar hänsyn till renderingsrelaterade aspekter såsom
             transformationer (till exempel rotation), linjebredd och fogar,
             textlayout och overflow, SmartArt-geometri, och andra layout-effekter
             som påverkar det slutgiltiga renderade utseendet på formen.
            
             De returnerade begränsningarna klipps inte till bildens rektangel.



### Se också
* klass [`SmartArtShape`](/slides/python-net/sv/aspose.slides.smartart/smartartshape)
* modul [`aspose.slides.smartart`](/slides/python-net/sv/aspose.slides.smartart)
* bibliotek [`Aspose.Slides`](/slides/python-net)