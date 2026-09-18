---
title: get_visual_bounds method
second_title: Aspose.Slides a Python számára a .NET API hivatkozás
description: 
type: docs
url: /hu/aspose.slides/groupshape/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
Lekérdezi a forma vizuális határait, amely a megjelenített tartalom alapján számítódik.

### Visszatérési érték

Egy **aspose.slides.RectangleF**, amely a forma vizuális határait jelöli diavetítési koordinátákban.



```python
def get_visual_bounds(self):
    ...
```


### Megjegyzések

A visszaadott téglalap a forma által a rendering során előállított teljes tartalom tengely-irányú határait jelöli diavetítési koordinátarendszerben.
             
Ezek a határok eltérhetnek a forma modell határaitól
([`Shape.x`](/slides/python-net/hu/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/hu/aspose.slides/shape/y),
[`Shape.width`](/slides/python-net/hu/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/hu/aspose.slides/shape/height))
és negatív koordinátákat is tartalmazhatnak, ha a megjelenített tartalom a dia eredetén túlra nyúlik.
             
A vizuális határok figyelembe veszik a rendereléshez kapcsolódó szempontokat, mint például a transzformációk (például forgatás), vonalvastagság és csatlakozások,
szöveg elrendezése és túlcsordulása, SmartArt geometria, valamint egyéb elrendezési hatások, amelyek befolyásolják a forma végleges megjelenését.
             
A visszaadott határok nincsenek levágva a dia téglalapjára.



### Lásd még
* osztály [`GroupShape`](/slides/python-net/hu/aspose.slides/groupshape)
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)