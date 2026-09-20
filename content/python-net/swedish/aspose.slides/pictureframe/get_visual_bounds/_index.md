---
title: get_visual_bounds method
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides/pictureframe/get_visual_bounds/
weight: 60
---
## get_visual_bounds(self) {#}
Hämtar den visuella gränsen för formen beräknad utifrån dess renderade innehåll.

### Returnerar

En **aspose.slides.RectangleF** som representerar den visuella gränsen för formen i bildspelskoordinater.



```python
def get_visual_bounds(self):
    ...
```


### Anmärkningar

Den returnerade rektangeln representerar de axeljusterade gränserna för allt innehåll som produceras av formen under rendering i bildspelskoordinatrummet.

Dessa gränser kan skilja sig från formens modellgränser ([`Shape.x`](/slides/python-net/sv/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/sv/aspose.slides/shape/y), [`Shape.width`](/slides/python-net/sv/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/sv/aspose.slides/shape/height)) och kan innehålla negativa koordinater om det renderade innehållet sträcker sig bortom bildspelsursprunget.

De visuella gränserna tar hänsyn till renderingsrelaterade aspekter såsom transformationer (till exempel rotation), linjebredd och fogar, textlayout och överflöde, SmartArt-geometri och andra layout-effekter som påverkar det slutliga renderade utseendet på formen.

De returnerade gränserna klipps inte till bildspelsrektangeln.



### Se också
* klass [`PictureFrame`](/slides/python-net/sv/aspose.slides/pictureframe)
* modul [`aspose.slides`](/slides/python-net/sv/aspose.slides)
* bibliotek [`Aspose.Slides`](/slides/python-net)