---
title: get_visual_bounds method
second_title: Aspose.Slides a Pythonhoz .NET API referencia
description: 
type: docs
url: /hu/aspose.slides/geometryshape/get_visual_bounds/
weight: 60
---
## get_visual_bounds(self) {#}
A forma megjelenített tartalma alapján kiszámított vizuális határait adja vissza.

### Visszatérési érték

Egy [`RectangleF`](/slides/python-net/hu/aspose.slides/rectanglef), amely a forma vizuális határait reprezentálja a diára vonatkozó koordinátákban.
             
             
```python
def get_visual_bounds(self):
    ...
```
             
             
### Megjegyzés

A visszaadott téglalap a forma által a renderelés során előállított összes tartalom tengelyre igazított határait jelöli a diákoordináta térben.
             
             
Ezek a határok eltérhetnek a forma modellhatáraitól ([`Shape.x`](/slides/python-net/hu/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/hu/aspose.slides/shape/y), [`Shape.width`](/slides/python-net/hu/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/hu/aspose.slides/shape/height)) és negatív koordinátákat is tartalmazhatnak, ha a renderelt tartalom túlnyúlik a dia origón.
             
             
A vizuális határok figyelembe veszik a rendereléshez kapcsolódó szempontokat, mint például a transzformációk (például forgatás), a vonalvastagság és illeszkedések, a szövegelrendezés és túlcsordulás, a SmartArt geometria, valamint egyéb elrendezési hatások, amelyek befolyásolják a forma végső megjelenését.
             
             
A visszaadott határok nincsenek levágva a dia téglalapjára.
             
             
### Lásd még
* osztály [`GeometryShape`](/slides/python-net/hu/aspose.slides/geometryshape)
* osztály [`RectangleF`](/slides/python-net/hu/aspose.slides/rectanglef)
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)