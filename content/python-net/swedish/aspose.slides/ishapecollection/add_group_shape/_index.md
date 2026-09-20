---
title: add_group_shape method
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides/ishapecollection/add_group_shape/
weight: 80
---
## add_group_shape(self) {#}
Skapar en ny tom gruppform och lägger till den i slutet av formsamlingen.
Gruppens ram justeras automatiskt för att passa alla former som läggs till den.

### Returnerar

Den nyss skapade [`IGroupShape`](/slides/python-net/sv/aspose.slides/igroupshape).



```python
def add_group_shape(self):
    ...
```



## add_group_shape(self, svg_image, x, y, width, height) {#isvgimage-float-float-float-float}
Skapar en ny gruppform, konverterar den angivna SVG-bilden till enskilda former och lägger till den resulterande gruppen i slutet av formsamlingen.

### Returnerar

Den nyss skapade [`IGroupShape`](/slides/python-net/sv/aspose.slides/igroupshape).



```python
def add_group_shape(self, svg_image, x, y, width, height):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| svg_image | [`ISvgImage`](/slides/python-net/sv/aspose.slides/isvgimage) | Den [`ISvgImage`](/slides/python-net/sv/aspose.slides/isvgimage) som innehåller vektor innehåll för att konvertera till former. |
| x | **float** | X-koordinaten för gruppens ram, i punkter. |
| y | **float** | Y-koordinaten för gruppens ram, i punkter. |
| width | **float** | Bredden på gruppens ram, i punkter. |
| height | **float** | Höjden på gruppens ram, i punkter. |



### Se även
* klass [`IGroupShape`](/slides/python-net/sv/aspose.slides/igroupshape)
* klass [`IShapeCollection`](/slides/python-net/sv/aspose.slides/ishapecollection)
* klass [`ISvgImage`](/slides/python-net/sv/aspose.slides/isvgimage)
* modul [`aspose.slides`](/slides/python-net/sv/aspose.slides)
* bibliotek [`Aspose.Slides`](/slides/python-net)