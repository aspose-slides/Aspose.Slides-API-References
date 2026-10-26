---
title: get_visual_bounds method
second_title: Aspose.Slides a Python számára a .NET API referenciája
description: 
type: docs
url: /hu/aspose.slides/autoshape/get_visual_bounds/
weight: 70
---
## get_visual_bounds(self) {#}
Megkapja a forma megjelenített tartalma alapján kiszámított vizuális határait.

### Returns

Egy [`RectangleF`](/slides/python-net/hu/aspose.slides/rectanglef), amely a forma vizuális határait képviseli diakoordinátákban.



```python
def get_visual_bounds(self):
    ...
```


### Remarks

A visszaadott téglalap a forma által a renderelés során előállított összes tartalom tengelyekhez igazított határait szemlélteti dia koordináta térben.
            
            Ezek a határok eltérhetnek a forma modell határaitól ([`Shape.x`](/slides/python-net/hu/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/hu/aspose.slides/shape/y), [`Shape.width`](/slides/python-net/hu/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/hu/aspose.slides/shape/height)), és negatív koordinátákat is tartalmazhatnak, ha a renderelt tartalom túllépi a dia origót.
            
            A vizuális határok figyelembe veszik a rendereléshez kapcsolódó szempontokat, mint például az átalakítások (például forgatás), a vonalvastagság és csatlakozások, a szöveg elrendezése és túlcsordulása, a SmartArt geometria, valamint egyéb elrendezési hatások, amelyek befolyásolják a forma végső megjelenését.
            
            A visszaadott határok nincsenek levágva a dia téglalapra.



### See Also
* osztály [`AutoShape`](/slides/python-net/hu/aspose.slides/autoshape)
* osztály [`RectangleF`](/slides/python-net/hu/aspose.slides/rectanglef)
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)