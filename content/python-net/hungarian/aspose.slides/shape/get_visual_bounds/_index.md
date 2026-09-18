---
title: get_visual_bounds method
second_title: Aspose.Slides Pythonhoz .NET API hivatkozás
description: 
type: docs
url: /hu/aspose.slides/shape/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
Lekéri a forma vizuális határait, amelyeket a renderelt tartalma alapján számítanak ki.

### Visszatérési érték
Egy **aspose.slides.RectangleF**, amely a forma vizuális határait jelöli a
             dia koordinátáiban.

```python
def get_visual_bounds(self):
    ...
```

### Megjegyzések
A visszaadott téglalap a forma által a renderelés során előállított minden tartalom
             tengelyre igazított határait képviseli a dia koordináta térben.

Ezek a határok eltérhetnek a forma modellhatáraitól ([`Shape.x`](/slides/python-net/hu/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/hu/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/hu/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/hu/aspose.slides/shape/height)) és negatív koordinátákat is tartalmazhatnak, ha a renderelt tartalom túlnyúlik a dia origón.

A vizuális határok figyelembe veszik a rendereléshez kapcsolódó szempontokat, mint például a transzformációk (például forgatás),
             vonalvastagság és illeszkedések, szöveg elrendezés és túlcsordulás, SmartArt geometria, valamint egyéb elrendezési hatások, amelyek befolyásolják a forma végleges megjelenését.

A visszaadott határok nincsenek levágva a dia téglalapra.

### Lásd még
* osztály [`Shape`](/slides/python-net/hu/aspose.slides/shape)
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)